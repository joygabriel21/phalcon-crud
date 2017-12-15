# crud_phalcon
CRUD using Phalcon with Search and Login Intergrated with Database. In this source we learn to how to make simple CRUD Phalcon on the study case how to sign up / register user and management user with login user and searching data. 

If you want try this script? You can clone/download this source and import the SQL (in folder sql) to your PhpMyAdmin.

# Edit Your Config.php
Edit your <b>config</b> phalcon on your directory phalcon in <b>/crud_phalcon/app/config/config.php</b> <br>
Setup your config with your host, username or password phpmyadmin/

<pre>
return new \Phalcon\Config([
    'database' => [
        'adapter'     => 'Mysql',
        'host'        => 'localhost',
        'username'    => 'root',
        'password'    => '',
        'dbname'      => 'crud',
        'charset'     => 'utf8',
    ],
</pre>
