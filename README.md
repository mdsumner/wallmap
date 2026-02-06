# wallmap



938 depth of jcupboard 

2390 width of wall outside of cupboard depth

2730 height skirting to skirting
hybrid, from list?

https://www.arcgis.com/apps/mapviewer/index.html?layers=d42f45dc18ce41199a48bfd73a20212a

## Monthly reminder email

The workflow in `.github/workflows/monthly-reminder-email.yml` sends a reminder email on the first day of each month at 09:00 UTC. Configure the following GitHub Actions secrets to enable it:

- `MAIL_SERVER`: SMTP server hostname
- `MAIL_SERVER_PORT`: SMTP server port (for example, `465`)
- `MAIL_USERNAME`: SMTP username
- `MAIL_PASSWORD`: SMTP password
- `MAIL_FROM`: sender email address
- `MAIL_TO`: recipient email address

Use the workflow dispatch action to send a test email after the secrets are set.
