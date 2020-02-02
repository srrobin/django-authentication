# django-authentication

for email :::::::

https://myaccount.google.com/lesssecureapps(email)
 
settings > Forwarding and POP/IMAP > Status: IMAP is disabled > enable(email setting)
 
 
#Email server
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend' 

EMAIL_HOST = 'smtp.gmail.com'

EMAIL_HOST_USER = 'your email'

EMAIL_HOST_PASSWORD = 'your email password ' 

EMAIL_PORT = 587


EMAIL_USE_TLS = True

DEFAULT_FROM_EMAIL = 'OTF Team <your email>'
