<VirtualHost *>
  DocumentRoot "C:/xampp/htdocs/dullahan.local"
  ServerName dullahan.local
  DirectoryIndex index.php
  <Directory "C:/xampp/htdocs/dullahan.local">
    AllowOverride All
    Allow from All
  </Directory>
</VirtualHost>