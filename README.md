# my-first-blog

git https://github.com/scouduresmpf/my-first-blog
SITIO LOCAL => http://10.4.15.161:8000/
ADMIN LOCAL => http://10.4.15.161:8000/admin
SITIO EN LA NUBE => http://scouduresmpf.pythonanywhere.com/
ADMIN EN LA NUBE => http://scouduresmpf.pythonanywhere.com/admin

INICIAR EL SITIO
PS C:\Users\scoudures.MPF> cd C:\Users\scoudures\djangogirls
PS C:\Users\scoudures\djangogirls> myvenv\Scripts\activate
(myvenv) PS C:\Users\scoudures\djangogirls> C:\Users\scoudures.MPF\AppData\Local\Programs\Python\Python37\python.exe manage.py runserver 0.0.0.0:8000

o bien desde la página pythonanywhere => consolas => bash
cd /home/scouduresmpf
pip3.6 install --user pythonanywhere
pa_autoconfigure_django.py https://github.com/scouduresmpf/my-first-blog.git
python manage.py createsuperuser
 workon scouduresmpf.pythonanywhere.com
(scouduresmpf.pythonanywhere.com)$ python manage.py collectstatic

APLICAR CAMBIOS
https://www.pythonanywhere.com/user/scouduresmpf/
$ cd $USER.pythonanywhere.com
$ git pull

Lo hice siguiendo https://tutorial.djangogirls.org/es/deploy/