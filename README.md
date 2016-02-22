# Postcode API
AppService API App ARM Demo

This API app uses AppService APIApp for service tier and can be deployed to any Azure subscripton.
Data store used is a highly performant and relatively less expensive Azure Table Storage, are you still using SQL Server for PAF service in your oraganisation?

Data used is from a RoyalMail sample file consisting 500K records mainly from York and Plymouth e.g. PL1 1DH, YO90 1UT.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsuneetnangia%2Fpostcodeapi%2Fmaster%2FMicrosoft.Demo.Postcode.API.Template%2FTemplates%2FAPIApp.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsuneetnangia%2Fpostcodeapi%2Fmaster%2FMicrosoft.Demo.Postcode.API.Template%2FTemplates%2FAPIApp.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Once deployed use this url to test the API http://&lt;YourApiAppName&gt;.azurewebsites.net/swagger
