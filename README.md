# Microservices-Docker-K8
Express based Microservices + Docker + Kubernetes(K8) with React front end.

PreReqs:
---------------

npm

Docker and Kubernetes.

Scaffold (https://skaffold.dev/docs/install/).



In hosts file the following entry need to be made to map the posts domain to localhost  ( for mac) in /etc/hosts
127.0.0.1 posts.com


Running the application:
------------------------


Launch terminal and run 

$ skaffold dev

Sample success output will list the following pods running in K8 cluster

[event-bus] Listening on 4005
[moderation] Listening on 4003
[comments] Listening on 4001
[posts] Listening on 4000
[query] Listening on 4002
[client] ℹ ｢wds｣: Project is running at http://10.1.0.38/
[client] ℹ ｢wds｣: webpack output is served from 
[client] ℹ ｢wds｣: Content not from webpack is served from /app/public
[client] ℹ ｢wds｣: 404s will fallback to /
[client] Starting the development server...
[client] 
[client] Compiled successfully!
[client] 
[client] You can now view client in the browser.
[client] 
[client]   Local:            http://localhost:3000
[client]   On Your Network:  http://10.1.0.38:3000


App url: http://posts.com/






