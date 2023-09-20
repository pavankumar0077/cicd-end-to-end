# django-todo
A simple todo app built with django

# ===================================================================================================
ARGO CD
--
1) GIT OPS Based Tool, Specially designed for deployment on KUBERNETES, We can also use FLUX as an alternative
2) JENKINS FOR CI,  ARGO for Continous Delivery 
3) ONE ADVANTAGE WITH ARGO CD is we don't need to write single line of CODE.
4) WE CAN CONFIGURE EVERYTHING WITH UI
5) Here we are storing KUBERNTES MANIFESTS in a different REPO
6) It is always recommended to keep Manifests files in different repo so that we are following GITOPS Princpals 








# ===================================================================================================

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
