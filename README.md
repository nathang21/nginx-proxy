# nginx-proxy
A nginx revrese proxy on Docker to easily host services behind in isolated containers. 
- Included seperate docker-gen for security
- docker-compose version 2
- My production WIP setup
- Lets Encrypt autmation for containers behind nginx-proxy  

Run:  
1. $ git clone  
2. $ docker-compose up  
3. Connect other containers that expose ports 80/443 (or customize config) to "nginx-proxy" docker network  to server virtual hosts.
