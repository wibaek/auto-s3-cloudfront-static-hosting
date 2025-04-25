# Automatic s3/cloudfront static hosting with Github Actions

해당 workflow는 Github Actions를 사용하여 AWS S3와 CloudFront를 통해 정적 웹사이트를 자동으로 배포하는 것을 도와줍니다.

Vite와 node 18, npm을 사용하는것을 가정하고 설정되었습니다.

## 해야할 것

### AWS IAM 사용자 생성

필요 정책

- AmazonS3FullAccess
- CloudFrontFullAccess

### Github Secrets 설정

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_REGION=ap-northeast-2
- AWS_S3_BUCKET=
- AWS_CLOUDFRONT_ID
