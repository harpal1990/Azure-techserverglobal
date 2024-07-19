Create Resource Group using AZ Cli 
az group create --name WebRG --location 'Central India


Create Virtual machine using ARM template 
az deployment group create --resource-group WebRG --template-file ARM_template/Virtual_machine/virtual_machine.json
