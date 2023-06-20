# [Atlantis Dark Django](https://appseed.us/product/atlantis-dark/django/)

Open-source **[Django Dashboard](https://appseed.us/admin-dashboards/django)** generated by AppSeed op top of [Atlantis BS4 Design](https://appseed.us/product/atlantis-dark/django/), 
an open-source admin template crafted by ThemeKita agency. It comes with the basic components and set of pre-built pages required to lay the foundation for any application.

- 👉 [Atlantis Dark Django](https://appseed.us/product/atlantis-dark/django/) - `Product page`
- 👉 [Atlantis Dark Django](https://django-atlantis-dark.appseed-srv1.com/) - `LIVE Demo`
- 🛒 **[Volt Django PRO](https://appseed.us/product/volt-dashboard-pro/django/)** - `Premium Version`

<br />

> Features

- ✅ `Up-to-date Dependencies`
- ✅ `Design`: [Django Theme Atlantis](https://github.com/app-generator/django-admin-atlantis)
- ✅ `Sections` covered by the design:
  - ✅ **Admin section** (reserved for superusers)
  - ✅ **Authentication**: `Django.contrib.AUTH`, Registration
  - ✅ **All Pages** available in for ordinary users 
- ✅ `Docker`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

![Atlantis Dark - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172799909-4cbc8eed-fdde-4408-ab61-123f235212d0.png)

<br />

## Start with `Docker`

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/django-atlantis-dark.git
$ cd django-atlantis-dark
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## Environment

Create a new `.env` file using sample `env.sample`. The meaning of each variable can be found below: 

- `DEBUG`: if `True` the app runs in develoment mode
  - For production value `False` should be used
- For `MySql` persistence
  - Install the DB Driver: `pip install mysqlclient` 
  - Create DB and assign a new user (full rights) 
  - Edit `.env` to match the DB, user, password ..  

<br />

## Manual Build

> Download the code 

```bash
$ git clone https://github.com/app-generator/django-atlantis-dark.git
$ cd django-atlantis-dark
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the APP

```bash
$ python manage.py createsuperuser # create the admin
$ python manage.py runserver       # start the project
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the APP

```bash
$ python manage.py createsuperuser # create the admin
$ python manage.py runserver       # start the project
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Codebase Structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                            
   |    |-- settings.py                   # Project Configuration  
   |    |-- urls.py                       # Project Routing
   |
   |-- home/
   |    |-- views.py                      # APP Views 
   |    |-- urls.py                       # APP Routing
   |    |-- models.py                     # APP Models 
   |    |-- tests.py                      # Tests  
   |
   |-- requirements.txt                   # Project Dependencies
   |
   |-- env.sample                         # ENV Configuration (default values)
   |-- manage.py                          # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Deploy on [Render](https://render.com/)

- Create a Blueprint instance
  - Go to https://dashboard.render.com/blueprints this link.
- Click `New Blueprint Instance` button.
- Connect your `repo` which you want to deploy.
- Fill the `Service Group Name` and click on `Update Existing Resources` button.
- After that your deployment will start automatically.

At this point, the product should be LIVE.

<br />

## [PRO Version](https://appseed.us/product/volt-dashboard-pro/django/)   

This design is a pixel-perfect [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Dashboard with a fresh, new design. `Volt Dashboard PRO` is built with over 300 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

> Features: 

- `Up-to-date Dependencies`
- `Design`: [Django Theme Volt](https://github.com/app-generator/django-volt-dashboard-pro) - `PRO Version`
- `Sections` covered by the design:
  - **Admin section** (reserved for superusers)
  - **Authentication**: `Django.contrib.AUTH`, Registration
  - **All Pages** available in for ordinary users 
- `Docker`, `Deployment`:
  - `CI/CD` flow via `Render`

![Volt Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172672843-8c40a801-3438-4e9c-86db-38a34191fbdf.png)

<br />

---
[Atlantis Dark Django](https://appseed.us/product/atlantis-dark/django/) - Open-source starter generated by **[AppSeed](https://appseed.us/)**.
