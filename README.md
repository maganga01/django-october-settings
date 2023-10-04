# posts
<!-- venv/bin/rav run installs -->
<!-- rav run freeze -->
django-october-settings
Learn how to build a Micro eCommerce Web App with Python and Serverless Postgres

Prerequisites
Python experience with 30 Days of Python or similiar
Django experience with Try Django or similiar
Basic understanding of HTML and CSS
Required Software
Python 3.10 or newer
Node.js 18.17 LTS or newer (For Tailwind.CSS)
Git
Getting Started
mkdir -p ~/dev
cd ~/dev
git clone https://github.com/maganga01/django-october-settings
cd django-october-settings
git checkout start
To install packages and run various command shortcuts, we use rav. Open rav.yaml to see the various commands available if you prefer to not use rav.

macOS/Linux Users

python3 -m venv venv
source venv/bin/activate
venv/bin/python -m pip install pip pip-tools rav --upgrade
venv/bin/rav run installs
rav run freeze
Windows Users

c:\Python310\python.exe -m venv venv
.\venv\Scripts\activate
python -m pip install pip pip-tools rav --upgrade
rav run win_installs
rav run win_freeze
With all the configuration done, here are the main commands you'll run:

rav run server
rav run watch
rav run vendor_pull
rav run server maps to python manage.py runserver in the src folder
rav run watch triggers tailwind to watch the tailwind-input.css to output the output.css styles file.
rav run vendor_pull