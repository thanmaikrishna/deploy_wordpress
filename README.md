create a highly available (HA), scalable and fault-tolerant deployment of 
the WordPress application. You will deploy the WordPress application in such a way that the application 
server, load balancer and database will scale independently of one another. You will also deploy the 
application's components like the webserver and database into two availability zones to distribute it and 
guard against failure of the anyone availability zone. The WordPress application will be deployed in a 
stateless fashion so that we can add or remove web application servers in response to the requests 
flowing into the system. Finally, we create a CloudFront distribution as CDN and change the 
configuration of WordPress.
