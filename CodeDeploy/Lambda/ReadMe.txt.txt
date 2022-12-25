https://www.youtube.com/watch?v=UlX38mVvMy8

Steps:
1. Create Lambda Function "CDLambda"
2. Create Version 1
3. Create Alias "CDVersion" pointing to Version1
4. Modify Lambda Function and Create Version 2

5. Create Service Role For CodeDeploy with Lambda
6. Create Deployment Application 
7. Create Deployment group
8. Trigger Deployment and verify that Alias has pointer moved to Version 2
