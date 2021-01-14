# sonar-report

1. Instala NodeJS 10 en Ubuntu 20.04 LTS  
```sh
$ sudo curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -  
$ sudo apt install nodejs
```
2. Instala Sonar-report  
```sh
$ sudo npm install -g sonar-report  
```
3. Edita el fichero principal de sonar-report con el contenido de index.js  
```sh
$ sudo nano /usr/local/lib/node_modules/sonar-report/index.js  
```
o reemplazalo directamente.  

4. Ejecuta sonar-report. Ejemplo:
```sh
sonar-report   --sonarurl="http://192.168.0.29" \
--sonarusername=admin \
--sonarpassword=PIqsjzZVznF3 \
--sonarcomponent=foro_inseguro \
--project "Foro Inseguro" > sonar-report_sonar-report.html
```
