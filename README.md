# cloud-formation-template

# AWS CloudFormation Deployment with GitHub Actions

This repository provides an automated CI/CD pipeline using GitHub Actions to validate and deploy AWS CloudFormation stacks using passwordless OpenID Connect (OIDC) authentication.

---

## Repository Structure

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment workflow
├── templates/
│   └── s3-bucket.yaml          # Sample AWS CloudFormation template
└── README.md
