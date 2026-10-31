# Secure Static Website Hosting on AWS

This project demonstrates hosting a secure static website on AWS using Amazon S3, CloudFront, and Origin Access Control (OAC).

## 🚀 Live Demo
[Click here to view the Live Site](https://d1omwcgiwj2oq7.cloudfront.net)

## 🛠️ Cloud Architecture
- **Amazon S3**: Stores website static assets (`index.html`) privately with public access blocked.
- **Amazon CloudFront**: Global Content Delivery Network (CDN) serving content via fast edge locations.
- **Origin Access Control (OAC)**: Restricts S3 bucket access so traffic only flows through CloudFront.

## 🔒 Security & Best Practices
- **Blocked Public Access**: Direct public access to the S3 bucket is strictly disabled.
- **OAC Bucket Policy**: S3 Bucket Policy grants read access exclusively to CloudFront distribution.
- **HTTPS Security**: Secured end-to-end using CloudFront default SSL certificate.
