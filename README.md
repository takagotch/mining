### mining
---
https://github.com/mining/mining

```py
// mining/test/test_mining_utils.py
import unittest

from datetime import date, datetime
from decimal import Decimal
from pandas import tslib, DataFrame

from mining.utils import slugfy
from mining.utils._pandas import fix_type, fix_render, def_generate

class df_slugfy_test(unittest.TestCase):
  def test_generate_simples(self):
    self.assertEquals(u"testamdo-slugfy", slugfy(u"Testamdo slugfy"))
    
  def test_used_accents(self): 
    self.assertEquals(u"testando-se-e-slugfy",
      slugfy(u"Testando se e slugfy"))

class fix_type_test(unittest.TestCase):
  def test_str_latin1(self):
  
  def test_str(self):
  
  def test_timestamp(self):
  
  def test_datetime(self):
  
  def test_date(self):
  
  def test_decimal(self):
  
class fix_render_test(unittest.TestCase):
  def test_rendere_dict(self):


class def_generate_gte_test(df_generate_test):













class df_generate_lte_test(df_generate_test):
  def test_lte(self):
    g = df_generate(self.df, "1", "filter__int__lte")
    self.assertEquals(g, u"int <= 1")
```

```sh
sudo apt-get install mongodb-10gen redis-server nodejs nodejs-dev npm
npm install bower
git clone git@github.com:mining/mining.git
make build

python manage.py runserver
python manage.py celery
python manage.py scheduler
python manage.py runserver
python manage.py build_demo

```

```
```


