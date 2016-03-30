## Description

Enhance the reddit clone system to incorporate streamlined views and login authentication.

## Normal Mode

Use the ongoing code from [Reddit Remake 2](https://github.com/tiy-lv-python-2016-02/reddit-remake-part-2) as a base to accomplish the assignment.

Convert all views over to use the built in generic views provided by django.

Using login required mixins ensure that login is required for all data modification views.

## Hard Mode

Convert the Post and Comment modification views to the generic views

Convert the application to use Postgres.  No need to import data.

## Nightmare Mode

Using the `UserPassesTestMixin` ensure that the user is the owner of the object before allowing access.

Convert the entire voting system to generic views and add check to ensure they can only vote once.

## External Links
* [Auth System Documentation](https://docs.djangoproject.com/en/1.9/topics/auth/default/)
* [Full Auth Views Docs](https://docs.djangoproject.com/en/1.9/topics/auth/default/#all-authentication-views)
* [Generic Views](https://docs.djangoproject.com/en/1.9/topics/auth/default/#all-authentication-views)
