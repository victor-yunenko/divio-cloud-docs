:sequential_nav: next

..  _tutorial-django-set-up:

Create a new Django project
===============================================

In this tutorial you will create and deploy a new project using `Django <https://www.djangoproject.com/>`_, the most
popular Python web application framework. The project will be set up in Docker and integrated with various cloud
services such as database and media storage.

The principles covered by the tutorial will apply to any other development stack.

..  note::

    This tutorial is intended for newcomers to the Divio platform. If you're already familiar with the basics of Divio,
    see our guide :ref:`How to create and deploy a Django project <django-create-deploy>`, which shows step-by-step how
    to create and deploy a Twelve-factor Django project including Postgres or MySQL, and cloud media storage using S3.


..  include:: includes/02-create-1-set-up.rst


* *Platform*: ``No platform``
* *Project type*: ``Empty``


..  include:: includes/02-create-2-git-environments.rst


This project is empty, so though you can try deploying it, that will fail (it will fail because the deployment process
checks for a successful start up, and so far, there isn't anything to start).


..  include:: includes/02-create-4-deployment-dashboard.rst
