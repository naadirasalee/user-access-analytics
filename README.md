# Automated User Access Analytics

This project analyzes user access logs to identify potentially high risk accounts using
rule based risk indicators and anomaly detection.

It simulates a real IT audit / IAM review process used in regulated environments in businesses.

## What the project does
- Flags dormant user accounts
- Identifies privileged users
- Detects unusual login hours
- Highlights users with high failed login attempts
- Applies Isolation Forest for anomaly detection
- Produces an audit-ready Excel report

## Tools used
- Python
- Pandas, NumPy
- sklearn
- Excel reporting

## Files in this repository
- `Automated_User_Access_Analytics.ipynb` – main analysis notebook
- `user_access_log.csv` – sample input data
- `High_Risk_User_Access_Report.xlsx` – example output report

## Use case
This project demonstrates how data analytics can be applied to:
- IT audit
- Identity and Access Management (IAM)
- Continuous controls monitoring
