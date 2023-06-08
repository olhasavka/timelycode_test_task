# timelycode_test_task for DevOps role

Lambda Function for Retrieving Pre-signed URL for Latest File in S3 Bucket

1. Create Cloudformation stack from template file (timelycode_task.yaml)
2. During creation enter parameters: S3 bucket name and lambda function name. Bucket name should not contain uppercase characters and must be unique
3. After successful stack creation appropriate S3 bucket and lambda function will appear.
4. Upload some files to the new S3 bucket.
5. Open the Functions page of the Lambda console.
6. Choose the name of the function that was created by our cloudformation stack
7. Choose the Test tab.
8. Under Test event, choose Saved event, and then choose the saved event that you want to use.
9. Click Test.
10. To review the test results, under Execution result, expand Details.

