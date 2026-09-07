# Gap Analysis — vs Stéphane Maarek "AWS Certified Solutions Architect Slides v48"

Порівняння поточних 20 деків з офіційним змістом курсу (Table of Contents витягнутий з оригінального PDF, 876 сторінок, 30 розділів).

## Повна таблиця відповідності

| # | Розділ курсу | Статус |
|---|---|---|
| 1 | Getting Started with AWS | ❌ немає |
| 2 | AWS IAM | ✅ IAM |
| 3 | EC2 – Basics | ✅ EC2 |
| 4 | EC2 – Associate | 🟡 можливо в EC2_Advanced |
| 5 | EC2 – Instance Storage | 🟡 можливо в EC2_Advanced/Storage_Extras |
| 6 | High Availability & Scalability | ✅ ELB_ASG |
| 7 | RDS, Aurora & ElastiCache | ✅ RDS_Aurora_ElastiCache |
| 8 | Amazon Route 53 | ✅ Route53 |
| 9 | Classic Solutions Architecture | ❌ немає |
| 10 | Amazon S3 | ✅ S3 |
| 11 | S3 – Advanced | 🟡 можливо в Storage_Extras |
| 12 | S3 – Security | ❌ немає окремо |
| 13 | CloudFront & Global Accelerator | 🟡 CloudFront_GA |
| 14 | AWS Storage Extras | ✅ Storage_Extras |
| 15 | AWS Integration & Messaging | ✅ Messaging |
| 16 | Containers on AWS | ✅ Containers |
| 17 | Serverless Overview | ✅ Serverless |
| 18 | Serverless Architectures | 🟡 можливо разом із Serverless |
| 19 | **Databases in AWS** (DynamoDB!) | ❌ **немає — критична прогалина** |
| 20 | Data & Analytics | ✅ Analytics |
| 21 | Machine Learning | ✅ ML_Overview |
| 22 | AWS Monitoring, Audit & Performance | ✅ Monitoring |
| 23 | **Advanced Identity in AWS** | ❌ **немає — критична прогалина** |
| 24 | AWS Security & Encryption | ✅ Security_Encryption |
| 25 | Amazon VPC | ✅ VPC |
| 26 | Disaster Recovery & Migrations | ✅ DR_Migration |
| 27 | More Solutions Architecture | ❌ немає |
| 28 | Other Services | ✅ Other_Services |
| 29 | White Papers & Architectures | ❌ немає |
| 30 | Exam Preparation | ❌ немає |

## Пріоритетні прогалини для нових деків

1. **DynamoDB / Databases in AWS** — NoSQL, partition/sort keys, capacity modes, DAX, Global Tables. Один з найчастіше тестованих сервісів на іспиті — найвищий пріоритет.
2. **Advanced Identity in AWS** — AWS Organizations, IAM Identity Center (SSO), Control Tower, Service Control Policies (SCP).
3. **Classic / More Solutions Architecture** — сценарні приклади архітектур ("дано constraint X — обери сервіс Y"). Формат самих інших деків (концептуальний Feynman-стиль) не тренує це сценарне мислення, яке власне і тестує іспит.
4. **Cost Optimization** — окремого розділу немає навіть в оригінальному курсі (розкидано по темах), але для іспиту SAA-C03 це окремий домен (20% ваги) — варто зібрати в окремий дек.
5. **S3 Security** — якщо не покрито достатньо глибоко в Security_Encryption.
6. **White Papers & AWS Well-Architected Framework** — 6 стовпів (Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability).
7. **Exam Preparation** — тактика складання (типи питань, time management, process of elimination).

## Джерело
Офіційний Table of Contents витягнутий з "AWS Certified Solutions Architect Slides v48.pdf" (Stéphane Maarek, datacumulus.com) — 876 сторінок, останні сторінки містять індекс усіх 30 розділів курсу.
