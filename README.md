FOEDI
=====

API
---
Ejecutar‌ ‌aplicación‌ ‌FOEDIAPI‌ ‌en‌ ‌la‌ ‌maquina‌ ‌mirtual‌ ‌

1. ‌Entrar‌ ‌a‌ ‌la‌ ‌carpeta‌ ‌en‌ ‌la‌ ‌ruta‌ ```/home/srosales/foediapi``` 
    ```
    cd /home/srosales/foediapi‌ ‌
    ```

2. Teclear‌ ‌el‌ ‌comando:
    ```
    ‌java‌ ‌org.springframework.boot.loader.JarLauncher‌ ‌
    ```

WEB
---
 ‌Como‌ ‌ejecutar‌ ‌aplicación‌ ‌FOEDI‌ ‌en‌ ‌la‌ ‌maquina‌ ‌mirtual‌ ‌

1. Entrar‌ ‌a‌ ‌la‌ ‌carpeta‌ ‌en‌ ‌la‌ ‌ruta‌ ‌:‌ ‌```/home/srosales/foediweb```
        ```
    cd /home/srosales/foediweb ‌
    ```

2. ‌teclear‌ ‌el‌ ‌comando:‌ ‌java‌ ‌org.springframework.boot.loader.JarLauncher‌ ‌
 ‌
 ‌
Aplicativo‌ ‌
----------
‌ ‌
1. ‌usa‌ ‌la‌ ‌teclas‌ ‌Ctrl-Z‌ ‌para‌ ‌detener‌ ‌el‌ ‌servicio‌ ‌
 ‌
 ‌
Link‌ ‌de‌ ‌Foedi:‌ 
###  ###
    
http://ipmaquinavritual:8086/foedi/login‌   
    
 ‌
Linkde‌ ‌Foedi‌ ‌Api:‌ ‌
 ‌
### Solicitar‌ ‌token‌ ‌POST‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/oauth/token‌  
     ‌
### Consultar‌ ‌permisos‌ ‌pendienetes‌ ‌GET‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/pendientes‌  
```
    {
        "idPermiso": 13,
        "solicitante": "Blanca Estela Valencia Casillas",
        "puesto": "Enlace en Telecomunicaciones",
        "area": "35.05.05 - Enlace en Telecomunicaciones",
        "tipoPermiso": "Día económico",
        "tituloPermiso": "Permiso por día económico",
        "tipoPermisoNombreCorto": "pde",
        "diasSolicitados": 1,
        "fechaInicio": "2020-02-28",
        "fechaFin": "2020-02-28",
        "deOtraPersona": false
    },
```
### Consultar‌ ‌un‌ ‌permiso‌ ‌pendienete‌ ‌GET‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/{idPermiso}‌  
     ‌
### Autoriza‌ ‌un‌ ‌permiso‌ ‌PUT‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/{idPermiso}/autorizaciones‌  
     ‌
### Rechazar‌ ‌un‌ ‌permizo‌ ‌PUT‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/{idPermiso}/negaciones‌  
     ‌
### Autoriza‌ ‌varios‌ ‌permisos‌ ‌PUT‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/autorizaciones/varios‌  
     ‌
### Rechazar‌ ‌varios‌ ‌permisos‌ ‌PUT‌ ‌ ###
    
http://ipmaquinavritual:8085/foediapi/api/permisos/negaciones/varios‌  
     ‌
