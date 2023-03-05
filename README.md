# Kanban-Backend

<b>W przypadku błędu:</b>
<p><i>django.db.migrations.exceptions.MigrationSchemaMissing: 
Unable to create the django_migrations table ((1064, "You have an error in your SQL syntax;
check the manual that corresponds to your MySQL server version for the right syntax to use near '(6) NOT NULL)' at line 1"))</i></p>
<hr>
---<b>Wykonaj downgrade Django do wersji 2.0</b>:
<p><i>pip install Django==2.0.0 -i https://pypi.douban.com/simple</i></p> 

---<b>W pliku</b> <i>billenium_project/&lowbar;&lowbar;init&lowbar;&lowbar;.py</i> <b>zaimportuj pakiet pymysql: </b>
<p><i>import pymysql
  <br>pymysql.install_as_MySQLdb()</i></p>
  
---<b>Zainstaluj pakiet pymysql: </b>  
<p><i>pip install pymysql</i></p>

<hr>
<b>Aby były zachowane standardy pep8 wpisz:</b>
<p><i>python -m autopep8 --in-place --recursive  --aggressive --aggressive ./kanban/</i><p>
  
