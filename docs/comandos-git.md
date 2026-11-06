# Comandos GitHub
git remote add origin https://github.com/pdmguzman-web/back_nest_angular_DGM.git


# Inicializar el repositorio local
```
git init
```
- Referencia del repositorio local con el repositorio remoto
(GITHUB)
````
git remote add origin https://github.com/pdmguzman-web/back_nest_angular_DGM.git
````


# Validar referencia 
````
git remote -v 
````
--------------------
```
git add .
git command -m "proyecto base"
git put origin master 
```
```
- Para forzar

git push -f origin master
```

# Arrancamos proyecto 
```
npm run start:dev
```
# Modules & Resource 
```
nest g mo modules/auth 
nest g res modules/auth
```
# Controllers & Services 
```
nest g co modules/auth 
nest g s modules/auth 
```