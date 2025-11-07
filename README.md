# Host a Static Website on Amazon S3

## Project Overview
This project demonstrates how to host a static website using Amazon S3. The goal was to learn about AWS services, specifically S3, and understand how to configure a bucket to serve a website publicly.

## Author
**Lilly Adjei**  


## Tools & Concepts Used
- **Service**: Amazon S3
- **Key Concepts**:
  - S3 Bucket Creation
  - Bucket Policies & ACLs (Access Control Lists)
  - Uploading HTML and Image Files
  - Enabling Static Website Hosting
  - Troubleshooting 403 Forbidden Errors

## Steps Taken

### 1. Create an S3 Bucket
- Created a general-purpose S3 bucket in the **N. Virginia (us-east-1)** region.
- Bucket names are globally unique.

### 2. Upload Website Files
- Uploaded `index.html` and image assets to the S3 bucket.
- These files are necessary to build a functional static website.

### 3. Enable Static Website Hosting
- Navigated to the **Properties** tab of the bucket.
- Enabled **Static Website Hosting**.
- Set `index.html` as the index document.

### 4. Resolve Access Issues
- Initially encountered a **403 Forbidden** error when accessing the bucket endpoint.
- Resolved by modifying the **S3 Block Public Access** settings and granting public read access to the objects.

### 5. Access the Website
- After configuration, the S3 bucket endpoint URL successfully displayed the website.

## Project Reflection
- **Time Spent**: Approximately 1 hour (including troubleshooting and quiz)
- **Most Challenging Part**: Troubleshooting the 403 error and configuring public access correctly.
- **Most Rewarding Part**: Seeing the website live and accessible via the S3 endpoint.

## Useful Links
- [NextWork](https://nextwork.org) – Explore more projects and learning resources.

---

> This project was completed as part of the NextWork learning platform to build practical AWS skills.
