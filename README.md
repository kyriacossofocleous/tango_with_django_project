# tango_with_django_project
RANGO PROJECT

For chapter4 
Error of not showing a picture of a cat in about page in about.html
Please change 
```html
# <img src="{{ MEDIA_URL }}cat.jpg" alt="Picture of a Cat."/>
```
to
```html
# <img src="{{ MEDIA_URL }}cat.jpg" alt="Picture of a Cat." />
```
before running the test
