# Dehydrated, Route53 and S3
This is a docker image that uses hydrated to issue Let's Encrypt certificates.
It automatically tries to pass the dns-01 challenge using an hydrated hook that calls `cli53`.

When the process is finished, it uploads the certificates to the desired s3 bucket.
