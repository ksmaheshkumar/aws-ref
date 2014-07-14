# aws-ref

A simple AWS reference of stuff to be used in IAM.

## S3

### S3 Object Operations

- `s3:GetObject`
- `s3:GetObjectVersion`
- `s3:PutObject`
- `s3:GetObjectAcl`
- `s3:GetObjectVersionAcl`
- `s3:PutObjectAcl`
- `s3:PutObjectVersionAcl`
- `s3:DeleteObject`
- `s3:DeleteObjectVersion`
- `s3:ListMultipartUploadParts`
- `s3:AbortMultipartUpload`
- `s3:GetObjectTorrent`
- `s3:GetObjectVersionTorrent`
- `s3:RestoreObject`

### S3 Bucket Operations

- `s3:CreateBucket`
- `s3:DeleteBucket`
- `s3:ListBucket`
- `s3:ListBucketVersions`
- `s3:ListAllMyBuckets`
- `s3:ListBucketMultipartUploads`

### S3 Bucket Subresource Operations

- `s3:GetBucketAcl`
- `s3:PutBucketAcl`
- `s3:GetBucketCORS`
- `s3:PutBucketCORS`
- `s3:GetBucketVersioning`
- `s3:PutBucketVersioning`
- `s3:GetBucketRequestPayment`
- `s3:PutBucketRequestPayment`
- `s3:GetBucketLocation`
- `s3:GetBucketPolicy`
- `s3:DeleteBucketPolicy`
- `s3:PutBucketPolicy`
- `s3:GetBucketNotification`
- `s3:PutBucketNotification`
- `s3:GetBucketLogging`
- `s3:PutBucketLogging`
- `s3:GetBucketWebsite`
- `s3:PutBucketWebsite`
- `s3:DeleteBucketWebsite`
- `s3:GetLifecycleConfiguration`
- `s3:PutLifecycleConfiguration`

## RDS

### RDS Operations

- `rds:CreateDBInstance`
- `rds:ModifyDBInstance`
- `rds:DeleteDBInstance`
- `rds:DescribeDBLogFiles`
- `rds:AddTagsToResource`
- `rds:RemoveTagsFromResource`
- `rds:RestoreDBInstanceToPointInTime`
- `rds:RestoreDBInstanceFromDBSnapshot`
- `rds:DownloadDBLogFilePortion`
- `rds:DescribeDBInstances`

### RDS Resources

- `rds:DatabaseClass` (String) The DB instance class of a DB instance
- `rds:DatabaseEngine` (String) The DB engine of the DB instance
- `rds:DatabaseName` (String) The name of the database on the DB instance
- `rds:MultiAz` (Integer) Indicates if the DB instance is running in multiple availability zones. 1 indicates that the DB instance is using multi-AZ.
- `rds:Piops` (Integer) This key will be present when a request is made for a DB instance with PIOPs enabled. The value will contain the number of provisioned IOs that an instance supports. 0 indicates does not have PIOPs enabled.
- `rds:StorageSize` (Integer) The storage volume size (in GB)
- `rds:Vpc` (Integer) Indicates if the database instance is running in a virtual private cloud
