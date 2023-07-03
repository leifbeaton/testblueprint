# Blueprint for deploying an NGINX Plus server using the NGINX Deployment Manager

![NGINX Plus]([https://example.com/nginx-plus-image.jpg](https://www.nginx.com/wp-content/uploads/2020/08/NGINX-Plus-logo-2020_featured.png))

This blueprint will deploy an NGINX Plus server in a standalone environment. It exposes the server with an external IP address and sets up the users with the relevant SSH keys.

![Server Diagram](https://example.com/server-diagram.png)

## Firstboot and Eachboot Scripts

Any `firstboot` and/or `eachboot` scripts will be copied to the instance and executed as appropriate.

## License Files

Any required license files will be asked for in the NGINX Deployment Manager interface.

![Deployment Manager Interface](https://example.com/deployment-manager-interface.png)
