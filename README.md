# px-ad-image-uploader
新広告画像アップローダー



## Development Enviroment

| Category             | Skill Stack          |
| -------------------- | -------------------- |
| Framework            | React.js             |
| Static typing        | TypeScript           |
| Linter               | ESLint               |
| Formatter            | Prettier             |
| Serverless Framework | Serverless Framework |



## System Configuration

### PlanA: Serverless

| Category                | Skill Stack     |
| ----------------------- | --------------- |
| Database                | AWS  DynamoDB   |
| Storage                 | AWS S3          |
| Hosting                 | AWS S3          |
|                         | AWS CloudFront  |
| Serverless architecture | AWS API Gateway |
|                         | AWS Lamdba      |

![serverless](https://prime-x-co-ltd.github.io/px-overview/serverless-uploader.png)

### PlanB: Client-Server

| Category   | Skill Stack       |
| ---------- | ----------------- |
| Database   | AWS  Aurora/MySQL |
| Storage    | AWS S3            |
| Hosting    | AWS S3            |
|            | AWS CloudFront    |
| API Server | AWS EC2           |

![onserver](https://prime-x-co-ltd.github.io/px-overview/onserver-uploader.png)