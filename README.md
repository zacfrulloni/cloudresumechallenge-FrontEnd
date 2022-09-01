# cloudresumechallenge-FrontEnd
•	Deployed CV online hosted on Amazon s3 as a static website. Used AWS services to display a visitor counter on the webpage that increments by 1 every time someone visits. The count is also stored and updated in a DynamoDB table.
•	Frontend: CV written with HTML, CSS and JavaScript to display number of visits on webpage
•	Backend: REST API integrated with a lambda function that uses python to update the visitor count in a DynamoDB table 
•	Deployed Frontend and Backend with SAM and CloudFormation templates
•	Used GitHub Actions to test new code with pytest and deploy SAM application to AWS
