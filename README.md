# 🚀 AWS S3 + CloudFront Static Website Hosting Project

## 📌 Overview

This project demonstrates hosting a static website using Amazon S3 and delivering it securely using CloudFront CDN with logging enabled.

---

## 🧠 Architecture

User → CloudFront → S3 Bucket (Static Website)
Logs → Stored in S3 Logs Bucket

---

## ⚙️ Services Used

* Amazon S3 (Static Hosting & Logs)
* CloudFront (CDN)

---

## 🔧 Steps Performed

1. Created S3 bucket and enabled static website hosting
2. Added bucket policy for public access
3. Uploaded website files (HTML, CSS)
4. Created CloudFront distribution
5. Connected CloudFront to S3 bucket
6. Enabled logging in CloudFront
7. Created separate S3 bucket for logs
8. Verified logs and website performance

---

## 📸 Screenshots

### S3 Static Website Hosting

![S3 Hosting](screenshots/s3-static-hosting.png)

### CloudFront Distribution

![CloudFront](screenshots/cloudfront-distribution.png)

### Logging Enabled

![Logging](screenshots/cloudfront-logging.png)

### Logs in S3

![Logs](screenshots/s3-logs.png)

### Final Website Output

![Website](screenshots/final-output.png)

---

## ✅ Outcome

* Successfully hosted static website
* Implemented CDN for faster delivery
* Enabled logging and monitored requests

---

## 💡 Key Learnings

* S3 static hosting configuration
* CloudFront distribution setup
* Logging and monitoring using S3
* Understanding HTTP status codes and caching

---