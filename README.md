## Kittygram backend ##

Backend server for Kittugram service. 

### Deployment notes: ### 
Add relevant URL to ALLOWED_HOSTS in /kittygram_backend/.env instead of kittygrampracticum.ddns.net  

Create virtual envinronment: 
`python3 -m venv venv`

Activate virtual envinronment:
`source venv/bin/activate`

Create superuser with activated vitrual envinronment: 
`python manage.py createsuperuser`
