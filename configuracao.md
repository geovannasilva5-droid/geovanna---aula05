         CRIAR PASTA PARA PROJETO
evitar arquivos espalhados  manter tudo tudo organizado 
separa projetos, para não misturar este projeto com outros futuros
facilitar manutenção, pois sabemos exatamente onde está


CRIAR TERMINAL: Microsoft Windows [versão 10.0.26200.8037]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\202410210032>mkdir django_aulas
C:\Users\202410210032>cd django_aulas

FIZEMOS A INSTALAÇÃO DO DJANGO
(venv) C:\Users\202410210032\django_aulas>pip install django
Collecting django
  Downloading django-5.2.12-py3-none-any.whl (8.3 MB)
     |████████████████████████████████| 8.3 MB 1.1 MB/s
Collecting asgiref>=3.8.1
  Downloading asgiref-3.11.1-py3-none-any.whl (24 kB)
Collecting tzdata
  Downloading tzdata-2025.3-py2.py3-none-any.whl (348 kB)
     |████████████████████████████████| 348 kB ...
Collecting sqlparse>=0.3.1
  Downloading sqlparse-0.5.5-py3-none-any.whl (46 kB)
     |████████████████████████████████| 46 kB ...
Collecting typing_extensions>=4
  Downloading typing_extensions-4.15.0-py3-none-any.whl (44 kB)
     |████████████████████████████████| 44 kB ...
Installing collected packages: typing-extensions, tzdata, sqlparse, asgiref, django
Successfully installed asgiref-3.11.1 django-5.2.12 sqlparse-0.5.5 typing-extensions-4.15.0 tzdata-2025.3
WARNING: You are using pip version 21.2.4; however, version 26.0.1 is available.
You should consider upgrading via the 'C:\Users\202410210032\django_aulas\venv\Scripts\python.exe -m pip install --upgrade pip' command.

APÓS VIMOS A VERSÃO QUE ESTAVA 
(venv) C:\Users\202410210032\django_aulas>django-admin --version
5.2.12

APÓS CRIAMOS OUTRO CODE COM O NOME MEU PROJETO
(venv) C:\Users\202410210032\django_aulas>django-admin startproject meu_projeto

(venv) C:\Users\202410210032\django_aulas>cd meu_projeto

(venv) C:\Users\202410210032\django_aulas\meu_projeto>code .


PASSAMOS TUDO QUE CRIAMOS PARA O VSCODE
(venv) C:\Users\202410210032\django_aulas\meu_projeto>code .

COM AS ABAS TODAS CRIADAS COLOCAMOS OS SEGUINTES COMANDOS NO VSCODE:
PS C:\Users\20241021python manage.py runservereto>

ASSIM DESCOBRIMOS A VERSÃO QUE ESTAVA INSTALADO NO PC:
 Django version 5.2.12

E ABRIMOS O LINK PARA IR PARA A PÁGINA DO DJANGO 
http://127.0.0.1:8000/



