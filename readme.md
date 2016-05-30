# Deploy a web app linked to a GitHub repository

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmaneta%2Fweb-app-github-deploy%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmaneta%2Fweb-app-github-deploy%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Commands to deploy:

```
azure login

azure account list

azure account set <YourSubscriptionNameOrId>

azure config mode arm

azure group create -n WebAppTestCapside -l "West Europe"

azure group deployment create -f azuredeploy.json -g  WebAppTestCapside 
```

