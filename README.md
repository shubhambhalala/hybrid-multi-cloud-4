# hybrid-multi-cloud-4
Hello World😃



In my previous article we have seen that how we can make our cloud architecture secure just by configuring it in right way. Still we left out with some interesting this like, we didn't give connectivity to the database subnet, in this case if we need to do security patch or download software we cannot do in the database subnet. Hence we have created a NAT Gateway to have a Bastion System.

Amazon Amazon Web Services (AWS)

✔Creating VPC

✔Creating two subnet one public and other private

✔Creating Internet Gateway and Routing table for gateway and associate it

✔Creating NAT Gateway and routing table for bastion system and associate it

✔Creating Security group for database and webserver

✔Launching instance of Wordpress server and MySql database



🎫Writeup: https://tinyurl.com/y7hsgebj
