# System Environment Variables Setting For Aliyun Secrets Manager Client 
Use Aliyun Secrets Manager client by system environment variables with the below ways:

* Use access key to access aliyun kms, you must set the following system environment variables (for linux):
	- export credentials\_type=ak
	- export credentials\_access\_key\_id=\<your access key id>
	- export credentials\_access\_secret=\<your access key secret>

* Use STS to access aliyun kms, you must set the following system environment variables (for linux):
	- export credentials\_type=sts
	- export credentials\_role\_session_name=\<your role name>
	- export credentials\_role\_arn=\<your role arn>
	- export credentials\_access\_key\_id=\<your access key id>
	- export credentials\_access\_secret=\<your access key secret>
* Use RAM role to access aliyun kms, you must set the following system environment variables (for linux):
	- export credentials_type=ram\_role
	- export credentials\_role\_session\_name=\<your role name>
	- export credentials\_role\_arn=\<your role arn>
	- export credentials\_access\_key\_id=\<your access key id>
	- export credentials\_access\_secret=\<your access key secret>
* Use ECS RAM role to access aliyun kms, you must set the following system environment variables (for linux):
	- export credentials\_type=ecs\_ram\_role
	- export credentials\_role\_session\_name=\<your role name>

	