# poc_azure_loadbalancer

`
az deployment group create \
--name $DeploymentName \
--template-file $templateFile \
--parameters storageAccountType=Standard_LRS storageName={your-name}         
`