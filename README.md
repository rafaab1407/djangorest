# djangorest

Fazer os seguintes comandos de instalação 

pip install django==2.2.9
pip install djangorestframework markdown django-filter

rodar depois esses dois comandos 

python manage.py makemigrations
python manage.py migrate

criar um usuario para acessar o admin 
python manage.py createsuperuser

Comando para iniciar o servidor 
python manage.py runserver

link do admin http://localhost:8000/admin/

link dos end points 

http://localhost:8000/api/v1/cursos/
http://localhost:8000/api/v1/avaliacoes/
