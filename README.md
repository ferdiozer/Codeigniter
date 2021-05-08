# PHP Codeigniter Quick Starter
You can start developing immediately by cloning it locally or to your server.
## For what
Speeding up and streamlining the development process
<br/>
If you have an SSL certificate, update the htaccess file as follows
```
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*) index.php?/$1 [L]
RewriteRule .* http://%{HTTP_HOST}%{REQUEST_URI} [L,R=301]
RewriteCond %{HTTP_HOST} !^www\. [NC]
RewriteRule .* http://www.%{HTTP_HOST}%{REQUEST_URI} [L,R=301]
```


### Support
[Documentation](https://codeigniter.com/userguide3)
[For your questions](https://github.com/ferdiozer/Codeigniter/issues)


<br/>
For your questions
https://github.com/ferdiozer/Codeigniter/issues

E-mail
[info@ferdiozer.com](https://github.com/ferdiozer/Codeigniter/issues)
