# Task Kubernetes Bucket Controller
 - Implement a custom Kubernetes controller to create an S3 bucket out of a custom resource called "Bucket"
 - The controller should create a new S3 storage bucket for each such resource
 - Bonus: optionally force-delete the bucket when the "Bucket" resource is deleted (you may have to empty the bucket first)
 - Bonus 2: create a Google Cloud Storage bucket depending on the cloud provider used by the cluster (pass as flag to the controller)
Input
 - AWS credentials should be provided to the controller via environment
 - Kubernetes manifest as shown below (extend the spec as needed)
# Solution - (in-progress)
