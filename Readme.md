# congstar-api

The German mobile phone provider Congstar doesn't allow you to have your 
invoice sent to you via email. You always have to log into the very slow
website to get it.

This script automates this process:

- it downloads the PDF invoice
- and sends it to you via email

## Usage

Clone the repo and run

```
CONGSTAR_USERNAME=$username CONGSTAR_PASSWORD=$pw SMTP_USERNAME=$username SMTP_PASSWORD=$pw ./congstar
```

