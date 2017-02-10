# Azure SIEMonster Deployment

Rancher Server
This template deploys an Ubuntu system with Docker installed. In addition, the Rancher server will be deployed. The public url for your host will be : http://[hostname].[region].cloudapp.azure.com:8080/

[Server Deployment](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsiemonster%2Fazure%2Fmaster%2Fazuremonster-serverdeploy.json)

Rancher Nodes
This template deploys an Ubuntu system with Docker installed. In addition, the Rancher agent will be deployed with the callback url as provided by you. So here you need to already have a server running!

[Nodes Deployment]

