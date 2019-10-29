### Superformula Backend Plan
- Use DynamoDB as storage for user data.
- Build a library for core data access & business logic code.
- Create Node.JS lambdas for each endpoint which utilize the data access library.
- Use API Gateway or possibly an Application Load Balancer as a reverse proxy/frontend to the lambda functions.
- Use Terraform to orchestrate cloud resources and deploy lambdas to AWS.

### Strech Goals
- Implment a logging & monitoring solution with Cloudwatch
- Implement a filtering compontent for the query/GET endpoints

### Estimated Time
- Estimated time required 6-12hrs of dev time.