# Azure-Template-AD-Joined-VMs
Deployement of 7 VMs inside a VNet and 3 Different Subnet

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/subodhcloud/Azure-Template-AD-Joined-VMs/blob/master/AzureAD-Template-AD%20Joined%20VMs.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://github.com/subodhcloud/Azure-Template-AD-Joined-VMs/blob/master/AzureAD-Template-AD%20Joined%20VMs.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to deploy 7 VMs inside a VNet and 3 Different Subnets. 
Also in those 7 VMs there will ve 1 AD server in subnet1, 2 Windows VMs in 2nd 
subnet and 4 Windows Servers in 3rd Subnet. In last subnet there will be 2 VMs 
IIS auto installed and rest of the 2 VMs will be SQL 2012 Enterprise Servers. 
All these VMs will also be added to the Domain simultaneously.
