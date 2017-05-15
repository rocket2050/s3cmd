Role Name
=========
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
This role manage backups to aws s3 bucket and creates versions of backup using s3cmd utility.
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
Role Variables
--------------

Here are the variables used in role which are very much required to configure s3cmd and managing backup in s3 bucket.

aws_key: "AWS_KEY"

aws_secret: "AWS_SECRET_KEY"

s3bucketPath: "bucketName/foldername"

folderNameInS3: "Name Of Folder To Set In S3"

localFilePath: "Path Of File To Be Put In S3"


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: backuptoS3host
      roles:
         - { role: opstree.s3cmd }

License
-------

BSD

Author Information
------------------

opstree.com

blog.opstree.com

