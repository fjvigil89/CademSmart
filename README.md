# SmartWeb Back

Back del Proyecto SmartWeb (WebApp)

## Installación


```bash
git clone git@gitlab.com:devsCadem/B2BApps/smartweb/smartweb-back.git 
```

## paquetes.

```npm
cd smartweb-back
npm install

npm start
```

## Complementos
- AWS
- mongoDB
- mariaDB
- npm
- nodejs
- typeScript


## Bases de Datos 
#### AWS
- [DB_SERVER](master-00.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [CADEMPRINCIPAL_SERVER](master-00.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BPERNOD_SERVER](b2b-pernod-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BICB_SERVER](b2b-icb-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BANDINA_SERVER](b2b-data-01.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BABI_SERVER](b2b-abi-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BCIAL_SERVER](b2b-cial-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BEMBONOR_SERVER](b2b-embonor-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [B2BCAPEL_SERVER](b2b-capel-app.c6tid4wxmmxn.us-east-1.rds.amazonaws.com)
- [REDIS_PORTAL_DESCARGAS](portal-descargas-redis-cache.ajeafu.ng.0001.usw2.cache.amazonaws.com)

#### Mongo
- [MONGO_URL](mongodb+srv://sistemas:8Vz4XNXUBDgw4xR@smartweb-sl4dh.mongodb.net/test?retryWrites=true&w=majority)

## Encrypt
AES Encrypt

## UML
![diagrama de clases](./img/uml.png)

## Flujo por Controlador
#### User
![user_login](./img/user_login.png)
![user_create](./img/user_create.png)
![user_ForgotPassword](./img/user_ForgotPassword.png)
![user_changePassword](./img/user_changePassword.png)
![user_status](./img/user_status.png)

#### Scheduler
![scheduler_update](./img/scheduler_update.png)

#### Report
![report_get](./img/report_get.png)

#### News
![news_visible](./img/news_visible.png)

#### Favoritos
![favoritos_delete](./img/favoritos_delete.png)
![favoritos_list](./img/favoritos_list.png)
![favoritos_save](./img/favoritos_save.png)

#### Download
![download_detalle](./img/download_detalle.png)
![download_detalle_cola](./img/download_detalle_cola.png)
![download_semanal](./img/download_semanal.png)
![download_ultimas_descargas](./img/download_ultimas_descargas.png)

#### B2b
![b2b_status](./img/b2b_status.png)

#### Apertura
![apertura](./img/apertura.png)
![apertura_periodo](./img/apertura_periodo.png)


