> This is an assignment to practise our learning of our session on microservices


## Overview

We have already converted a monolithic app (https://github.com/rjcool100/monolith) to a collection of microservices.
Now our app is working fine scaling good but we need to add a new feature to it.The management wants us to create a signup api where people sign up using an email id which can be used as the username and then when the signup is complete a welcome email be sent to them.

## What you have to do?

Create another route/microservice for signup, again its your decision but a signup route and api exists is a pre-requisite but not the end goal of this task remember.
Once that is done create another service/api/route which sends the user a welcome email.
Keep it simple, the mail just needs to have a simple text like:
Hello {{name}},
We weclome you to our website...
Generic welcome message

Thank you


## Some pointers

- Remember a microservice serves a single purpose as explained in the presentation(https://docs.google.com/presentation/d/1xpuD9J9AwqtksiFE0VA17Ojdgyn_EwZZpddWp0HHw-M/edit?usp=sharing) but it should be usable in multiple scenarios.So design the service in such a way that later it can be used by other services ,like
 a succesful purchase of an item.
 
## Useful resources

- You could use external npm modules for sending emails like and you may need to create and email account, dont shy away.
Use this article (https://codeburst.io/sending-an-email-using-nodemailer-gmail-7cfa0712a799) as reference.
-You can reach out to me @rohitj299@gmail.com for any queries. 
