## Official UCSD IEEE Org Quarterly Projects Website

Home for IEEE Quarterly Projects Competitions, where 2k+ students apply quarterly and compete to make the best hardware and software projects! Winners get internship opportunities at sponsor companies. Hosted quarterly in September, January, and March!

https://github.com/user-attachments/assets/c91cbd9d-9b64-4cff-b145-cde06b0dde81

## Get Started

### Dependencies 
```bash
brew install python postgres
```
After installing postgres, start the service and set your DB username and password

### Run Application
```bash
cd ieeeqp.com
python -m venv .
source bin/activate
pip install requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
