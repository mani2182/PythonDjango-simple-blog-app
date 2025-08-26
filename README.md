# PythonDjango-simple-blog-app
PythonDjango-simple-blog-app

1. Download and extract: django_simple_blog_app_complete 2.zip

2. Navigate to Project Folder
   Open terminal and go into the extracted folder:
   cd django_simple_blog_app_complete 2

3. Set Up Virtual Environment
   Create a virtual environment:
   > python -m venv venv

Activate it:
On Windows:
> venv\Scripts\activate
On Mac: 
> source venv/bin/activate

4. Install Django
  Install Django using pip:
  > pip install django

5. Run Migrations
   Initialize the database:
   > python manage.py makemigrations
   > python manage.py migrate

6. Create Superuser (Admin Login)
To access the admin panel:
> python manage.py createsuperuser
(Enter username, email, password when prompted.)

7. Run the Server
Start the local development server:
> python manage.py runserver

8. Visit in your browser:
   http://127.0.0.1:8000

9. Use the App
    | Page             | URL                  |
| ---------------- | -------------------- |
| Blog List (Home) | `/`                  |
| Blog Detail      | `/blog/<id>/`        |
| Create Blog      | `/blog/create/`      |
| Edit Blog        | `/blog/edit/<id>/`   |
| Delete Blog      | `/blog/delete/<id>/` |
| Register         | `/register/`         |
| Login            | `/login/`            |
| Admin Panel      | `/admin/`            |

**Please run this one command to create the missing migration for your blog models:**
> python manage.py makemigrations blog
> python manage.py migrate
> python manage.py runserver
http://127.0.0.1:8000

--------------------------- Thank you -------------------------


