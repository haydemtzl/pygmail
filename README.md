# Send emails from Gmail account with or without attachments

If you locate this library on your Python directory under lib/site-packages you will be able to import it directly.

It contains two functions, send email with attachments and with no attachments

## Usage

```
import pygmail
sender = pygmail.gmailsendemail.SendEmailUtility()

sender.send_mail_with_attachment(from_user,from_password,to,subject,text,attach)
sender.send_mail_no_attachment(from_user,from_password,to,subject,text)

```

## Requirements

1. smptlib
