# tcp-routing-pcf-aws
With the TCP Routing feature now available in Pivotal Cloud Foundry [1](https://docs.pivotal.io/pivotalcf/1-8/adminguide/enabling-tcp-routing.html), support for IoT, blockchain as well as legacy applications has become stronger on Pivotal Cloud Foundry. 

PCF Docs (docs.pivotal.io) does a great job in providing information as to how to enable TCP Routing on PCF for AWS. This document is to provide additional caveats with AWS and how to workaround them. 

Primarily, I will cover the below points
- Cloud Formation Template to update your ports for your ELB as well as TCP Security Groups. 
- Sample EchoServer application to show the capabilities of TCP Routing. 

