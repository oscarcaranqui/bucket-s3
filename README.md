# bucket-s3
create bucket s3

## Crear access keys
1. Ingresamos al usuario oscaranqui
![image](https://github.com/oscarcaranqui/bucket-s3/assets/122688473/70e45261-3c0f-4c38-a931-30338c185c28)
2. Agregamos permisos S3 y creamos el access key
![image](https://github.com/oscarcaranqui/bucket-s3/assets/122688473/8e95aa0b-3b98-4b7f-9820-e7ae9f11a7bb)
Nota en nuestro caso el grupo developer tiene asignado los permisos
![image](https://github.com/oscarcaranqui/bucket-s3/assets/122688473/dfa9d34d-2c8c-451a-9e84-41990e6c6730)



## S3FS FUSE
https://github.com/s3fs-fuse/s3fs-fuse

1. sudo apt install s3fs
2. 
echo AKIA4DKFL42QF6PUSZLY:0/GMW6sSLG6saX1DQR0XplcaO9Wowprq7PvCla7a > ${HOME}/.passwd-s3fs
chmod 600 ${HOME}/.passwd-s3fs


