AWS-CLI

Example:

docker run --rm  \
    -e AWS_ACCESS_KEY_ID=0000000000000000000 \
    -e AWS_SECRET_ACCESS_KEY=00000000000000000000000000000000000 \
    zensoftdevops/aws-cli \
    s3 mb s3://mybucket
