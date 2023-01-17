# PROYECTO FINAL DE ARGENTINA PROGRAMA 
# EDICIÓN 2022 
# POR NORBERTO GATTI

# **********   DOCUMENTACIÓN DE LA API    ***********
 
 Backend en Spring Boot : Rest API with MySQL and JWT
 
 # USUARIO : nombreUsuario: "norberto.o.gatti@gmail.com" , password: "12345678"
 
 # ENDPOINTS

 LINK DEL SERVIDOR EN VIVO: https://argentina-programa-portafolio.kpyeb.com/
 
 ENTIDADES: AcercaDe, Educacion, Experiencias, Skills, Proyectos.
 
  
 #  *** OPEN ***

    REGISTRO: 
    {
     "nombre": "usuario1", 
     "nombreUsuario": "usuario1", 
     "email": "usuario1@usuario1.com",
     "password": "usuario1"
    }
    
    LOGIN:
    https://argentina-programa-portafolio.koyeb.com/auth/login
    
    { 
       "nombreUsuario": "norberto.o.gatti@gmail.com",
       "password": "12345678"
    }
 
 # *** LOCK ***
 
   # METHOD GET 

     All
         https://argentina-programa-portafolio.koyeb.com/api/v1/acerca_de
         https://argentina-programa-portafolio.koyeb.com/api/v1/educacion
         https://argentina-programa-portafolio.koyeb.com/api/v1/experiencias
         https://argentina-programa-portafolio.koyeb.com/api/v1/skills
         https://argentina-programa-portafolio.koyeb.com/api/v1/proyectos

     One
         https://argentina-programa-portafolio.koyeb.com/api/v1/acerca_de/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/educacion/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/experiencias/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/skills/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/proyectos/id
         
   # METHOD POST
     
         https://argentina-programa-portafolio.koyeb.com/api/v1/acerca_de
         
         {
           "fullname": "...",
           "posicion": "...",
           "descripcion" : "..."
         }
     
         
         https://argentina-programa-portafolio.koyeb.com/api/v1/educacion
         
         {
          "institucion": "...",
          "titulo": "...",
          "periodo": "...", 
          "estado" : "...",
          "detalles": "..."
         }
         
         
         https://argentina-programa-portafolio.koyeb.com/api/v1/experiencias
         
         {
          "empresa": "...",
          "ubicacion": "...",
          "puesto": "...",
          "periodo": "...",
          "actividades": "..."
         }
         
         
         https://argentina-programa-portafolio.koyeb.com/api/v1/skills
         
        {
         "tecnologia": "...",
         "imagen": "link_de_una_imagen"
        }
         
         
         https://argentina-programa-portafolio.koyeb.com/api/v1/proyectos
         
         {
          "titulo": "...",
          "imagen": "link_de_una_imagen",
          "descripcion" : ""
         }
         
         

   
   # METHOD PUT & DELETE
     One
         https://argentina-programa-portafolio.koyeb.com/api/v1/acerca_de/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/educacion/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/experiencias/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/skills/id
         https://argentina-programa-portafolio.koyeb.com/api/v1/proyectos/id
   
 
 
    
  PARA EJECUTAR LAS PETICIONES EL USUARIO DEBE ESTAR LOGUEADO, 
  DE LO CONTRARIO RECIBIRÁ UN ERROR 401: NO AUTORIZADO.
  
  ESTE PROYECTO SE ENCUENTRA EN ETAPA DE DESARROLLO.

  
  
 
 
