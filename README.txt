Instrucciones para subir el sitio a alwaysdata:
1) Crear una cuenta en alwaysdata.com y entrar al panel.
2) En Web > Sites > Add a site, crear un sitio nuevo o usar el subdominio <tu-cuenta>.alwaysdata.net. (ver docs)
3) Subir los archivos al directorio público del sitio (normalmente 'www' o 'htdocs') usando:
   - FTP/SFTP: Host ftp-<tu-cuenta>.alwaysdata.net, puerto 990 (SSL) o 21 (STARTTLS). Usa tu usuario FTP y contraseña.
   - O usar Git deploy: agregar como remoto 'deploy' y hacer 'git push deploy production'.
4) Si usas FTP con FileZilla, configura sitio nuevo y conecta con las credenciales.
5) Reemplaza las imágenes en la carpeta 'images' si lo deseas.
Referencias: alwaysdata docs (Sites, FTP/SFTP, Git deploy).
