Use this to generate secret key in django on linux


```shell

cd /home/../project_dir/

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

python manage.py shell
from django.core.management.utils import get_random_secret_key

get_random_secret_key()

```
