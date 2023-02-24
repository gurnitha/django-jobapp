# BUILDING JOB APPLICATION USING DJANGO V 4.1
Building Job Application based on my course on Udemy.com by Faisal Memon

Github: https://github.com/gurnitha/django-jobapp


## 01. SETUP


#### 01.1 Create django project 'config'

		Acitivities:

        (venv3841) λ django-admin startproject config .
        
        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py


#### 01.2 Create django app 'apps/job

		Acitivities:

        1. (venv3841) λ mkdir apps\job                                
        2. (venv3841) λ django-admin startapp job apps\job            
                                                           
        modified:   README.md                              
        new file:   apps/job/__init__.py                   
        new file:   apps/job/admin.py                      
        new file:   apps/job/apps.py                       
        new file:   apps/job/migrations/__init__.py        
        new file:   apps/job/models.py                     
        new file:   apps/job/tests.py                      
        new file:   apps/job/views.py                      