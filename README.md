“First, I created an S3 bucket to store my backup files.
Next, I launched an EC2 instance and attached an IAM role so the EC2 instance can access S3 securely without using access keys.
Then, I connected to the EC2 instance from my command prompt using SSH with a key pair.
After that, I transferred my files from my local laptop to the EC2 instance using the SCP command.
To back up the files from EC2 to S3, I created a shell script called backup.sh using nano, which contains the command to copy files from EC2 to the S3 bucket.
Finally, I ran the script manually whenever I wanted to back up the files to S3.”
