# Django

## **Links Úteis:**

**Estrutura de Arquivos:**

https://gist.github.com/RochaGabriell/be715c3d2e0e084ec9ef3f0e75d97897

**Notion do Projeto:**

https://elfin-effect-c09.notion.site/Django-125190147c16801d92bee84339e21057

**Principais Arquivos e Diretórios:**

manage-py - arquivo de gerenciamento do django

[settings.py](http://settings.py) - arquivo de configurações

requirements.txt - arquivo de dependências do projeto

## Atalhos

### **VSCode**

CTRL+b - Mostra oculta pastas

CTRL+j - Mostra oculta terminal

CTRL+l - Limpa o Terminal

CTRL+Shft+p > Python Select Interpreter - Importante verificar se o Python setado é o da venv

### **Django**

django-admin help

## Comandos Úteis

Python —version

virtualenv —version

## Instalando o Python, PIP e VirtualEnv

1. Instalar o Python: https://www.python.org/downloads/
2. Configurar variavel de ambiente do Python: C:\Users\tiago\AppData\Local\Programs\Python\Python313
3. Baixar o PIP: curl https://bootstrap.pypa.io/get-pip.py -o [get-pip.py](http://get-pip.py/)
4. Instalar o PIP: python [get-pip.py](http://get-pip.py/)
5. Configurar variavel de ambiente do PIP: C:\Users\tiago\AppData\Local\Programs\Python\Python313\Scripts
6. Instalar a Virtualenv: pip install virtualenv

## Criando um ambiente virtual e iniciando

1. virtualenv venv
2. venv/Scripts/activate
3. deactivate

## Instalando o Django, criando requirements e criando projeto

1. pip install django
2. pip freeze > requirements.txt
3. django-admin startproject setup .

## Iniciando o servidor

1. python [manage.py](http://manage.py) runserver

## Alterando Time-Zone e Linguagem

1. Editar o arquivo settings.py
2. alterar a variável language_code para pt-br
3. alterar a variável time_zone para America/Sao_Paulo

## Criar arquivo .env Preparando a Secret-key para versionamento

1. pip install python-dotenv
2. pip freeze > requirements.txt
3. criar arquivo .env
4. copiar a secret_key para este arquivo sem as aspas

## Criar arquivo .gitignore

1. criar arquivo .gitignore
2. Acessar https://www.toptal.com/developers/gitignore/ e digitar django
3. copiar e colar conteúdo no arquivo

## Criar App

python [manage.py](http://manage.py/) startapp *nome_do_app*

## Criando Statics

python [manage.py](http://manage.py/) collectstatic

## Instalando dependências a partir do requirements.txt

pip install -r requirements.txt
