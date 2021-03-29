<!DOCTYPE html><!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Peru delivery</title>
  
  <link rel="shortcut icon" type="image/x-icon" href="2imagen.ico">
  <link rel="stylesheet" href="styles.css">
  <meta name="viewport" content="width=divice-width,user-scalable=no, initial-scale=1.0, maximun-scale=1.0,minimun-scale=1.0">
	<script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
</head>
<body>
<style >
@import url("https://fonts.googleapis.com/css?family=Montserrat:400,500,700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  font-family: "Montserrat", sans-serif;
}
#contenedor{
  width:80%;
  max-width: 1000px;
  margin: 0 auto;
  overflow: hidden;
}

body {
  width: 100%;
  
  background: #8f8c8c;
  font-size: 14px;
  line-height: 22px;
  color: #000000;
}

.bold {
  font-weight: 700;
  font-size: 20px;
  text-transform: uppercase;
}

.semi-bold {
  font-weight: 500;
  font-size: 16px;
}

.resumen {
  width: 80%;
  height: auto;
  display: flex;
  margin: 50px auto;
}

.resumen .resumen_izquierda {
  width: 37%;
  background: #0bb5f4;
}

.resumen .resumen_izquierda .resumen_perfil {
  width: 100%;
  height: 280px;
}

.resumen .resumen_izquierda .resumen_perfil img {
  width: 100%;
  height: 100%;
}

.resumen .resumen_izquierda .resumen_content {
  padding: 0 25px;
}

.resumen .titulo {
  margin-bottom: 20px;
}

.resumen .resumen_izquierda .bold {
  color: rgb(252, 243, 243);
}

.resumen .resumen_izquierda .regular {
  color: #b1eaff;
}

.resumen .resumen_item {
  padding: 25px 0;
  border-bottom: 2px solid #b1eaff;
}

.resumen .resumen_izquierda .resumen_item:last-child,
.resumen .resumen_derecha .resumen_item:last-child {
  border-bottom: 0px;
}

.resumen .resumen_izquierda ul li {
  display: flex;
  margin-bottom: 10px;
  align-items: center;
}

.resumen .resumen_izquierda ul li:last-child {
  margin-bottom: 0;
}

.resumen .resumen_izquierda ul li .icon {
  width: 35px;
  height: 35px;
  background: #fff;
  color: #0bb5f4;
  border-radius: 50%;
  margin-right: 15px;
  font-size: 12px;
  position: relative;
}

.resumen .icon i,
.resumen .resumen_derecha .resumen_hobby ul li i {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.resumen .resumen_izquierda ul li .data {
  color: #000000;
}

.resumen .resumen_izquierda .resumen_habil2 ul li {
  display: flex;
  margin-bottom: 10px;
  color: #b1eaff;
  justify-content: space-between;
  align-items: center;
}

.resumen .resumen_izquierda .resumen_habil2 ul li .habil_name {
  width: 20%;
}

.resumen .resumen_izquierda .resumen_habil2 ul li .habil_progreso {
  width: 60%;
  margin: 0 5px;
  height: 5px;
  background: #009fd9;
  position: relative;
}

.resumen .resumen_izquierda .resumen_habil2 ul li .habil_per {
  width: 15%;
}

.resumen .resumen_izquierda .resumen_habil2 ul li .habil_progreso span {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background: #fff;
}

.resumen .resumen_izquierda .resumen_social .semi-bold {
  color: rgb(0, 0, 0);
  margin-bottom: 3px;
}

.resumen .resumen_derecha{
  width: 520px;
  background: rgb(255, 255, 255);
  padding: 25px;
}

.resumen .resumen_derecha .bold {
  color: #0b83f4;
}

.resumen .resumen_derecha .resumen_todo ul,
.resumen .resumen_derecha .resumen_educacion ul {
  padding-left: 40px;
  overflow: hidden;
}

.resumen .resumen_derecha ul li {
  position: relative;
}

.resumen .resumen_derecha ul li .date {
  font-size: 16px;
  font-weight: 500;
  margin-bottom: 15px;
}

.resumen .resumen_derecha ul li .informacion {
  margin-bottom: 20px;
}

.resumen .resumen_derecha ul li:last-child .informacion {
  margin-bottom: 0;
}

.resumen .resumen_derecha .resumen_todo ul li:before,
.resumen .resumen_derecha .resumen_educacion ul li:before {
  content: "";
  position: absolute;
  top: 5px;
  left: -25px;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  border: 2px solid #0bb5f4;
}

.resumen .resumen_derecha .resumen_todo ul li:after,
.resumen .resumen_derecha .resumen_educacion ul li:after {
  content: "";
  position: absolute;
  top: 14px;
  left: -21px;
  width: 2px;
  height: 115px;
  background: #0bb5f4;
}

.resumen .resumen_derecha .resumen_hobby ul {
  display: flex;
  justify-content: space-between;
}

.resumen .resumen_derecha .resumen_hobby ul li {
  width: 80px;
  height: 80px;
  border: 2px solid #0b9ff4;
  border-radius: 50%;
  position: relative;
  color: #0bb5f4;
}

.resumen .resumen_derecha .resumen_hobby ul li i {
  font-size: 30px;
}

.resumen .resumen_derecha .resumen_hobby ul li:before {
  content: "";
  position: absolute;
  top: 40px;
  right: -52px;
  width: 50px;
  height: 2px;
  background: #0bb5f4;
}

.resumen .resumen_derecha .resumen_hobby ul li:last-child:before {
  display: none;
}


</style>
<div id ="contenedor">
    <div class="resumen">
      <div class="resumen_izquierda">
        <div class="resumen_perfil">
          <img src="tr 2.jpg" alt="profile_pic">
        </div>
        <div class="resumen_content">
          <div class="resumen_item resumen_informacion">
            <div class="titulo">
              <p class="bold">Perudelivery</p>
              <p class="regular">de seguridad</p>
            </div>
            <ul>
              <li>
                <div class="icon">
                  <i class="fas fa-map-signs"></i>
                </div>
                <div class="data">
                  18 , Arequipa <br /> Peru
                </div>
              </li>
              <li>
                <div class="icon">
                  <i class="fas fa-mobile-alt"></i>
                </div>
                <div class="data">
                  +51 944187579
                </div>
              </li>
              <li>
                <div class="icon">
                  <i class="fas fa-envelope"></i>
                </div>
                <div class="data">
                  Perudelivery124@gmail.com
                </div>
              </li>
            </ul>
          </div>
          <div class="resumen_item resumen_habil2">
            <div class="titulo">
              <p class="bold">Habilidades</p>
            </div>
            <ul>
              <li>
                <div class="habil_name">
                  HTML
                </div>
                <div class="habil_progreso">
                  <span style="width: 80%;"></span>
                </div>
                <div class="habil_per">80%</div>
              </li>
              <li>
                <div class="habil_name">
                  CSS
                </div>
                <div class="habil_progreso">
                  <span style="width: 70%;"></span>
                </div>
                <div class="habil_per">70%</div>
              </li>
            </ul>
          </div>
          <div class="resumen_item resumen_social">
            <div class="titulo">
              <p class="bold">Social</p>
            </div>
            <ul>
              <li>
                <div class="icon">
                  <i class="fab fa-facebook-square"></i>
                </div>
                <div class="data">
                  <p class="semi-bold"><b>Facebook</b></p>
                  <p> <a href ="Perudelivery124@gmail.com" target="_blank" style="text-decoration:none">Perudelivery124@gmail.com</a></p>
                </div>
              </li>
              <li>
                <div class="icon">
                  <i class="fab fa-twitter-square"></i>
                </div>
                <div class="data">
                  <p class="semi-bold"><b>Twitter</b></p>
                  <p><a href ="Perudelivery124@gmail.com" target="_blank" style="text-decoration:none">Perudelivery124@gmail.com</a></p>
                </div>
              </li>
              <li>
                <div class="icon">
                  <i class="fab fa-youtube"></i>
                </div>
                <div class="data">
                  <p class="semi-bold"><b>instagram</b></p>
                  <p><a href="Perudelivery124@gmail.com" target="_blank" style="text-decoration:none">Perudelivery124@gmail.com</a></p>
                </div>
              </li>
              
            </ul>
          </div>
        </div>
      </div>
      <div class="resumen_derecha">
        <div class="resumen_item resumen_sobre">
            <div class="titulo">
              <p class="bold">Sobre mi persona</p>
            </div>
            <p>somos la empresa Perudelivery124 y proporcionamos porductos de seguridad en todo el pais

        <div class="resumen_item resumen_todo">
            <div class="titulo">
              <p class="bold">Experiencia laboral</p>
            </div>
            <ul>
                <li>
                    <div class="date">2012 - 2014</div> 
                    <div class="informacion">
                        <p class="semi-bold">camaras</p> 
                      <p>de seguridad
                      </p>
                    </div>
                </li>
                <li>
                  <div class="date">2015 - 2017</div>
                  <div class="informacion">
                        <p class="semi-bold">webscams</p> 
                      <p>para todos los deportes</p>
                    </div>
                </li>
                <li>
                  <div class="date">2017 - 2019</div>
                  <div class="informacion">
                        <p class="semi-bold">agrandamos nuestro mercado</p> 
                      <p>en plx y aliexpress</p>
                    </div>
                </li>
            </ul>
        </div>
        <div class="resumen_item resumen_educacion">
          <div class="titulo">
              <p class="bold">carrera de la empresa</p>
            </div>
          <ul>
                <li>
                    <div class="date">2008 - 2019</div> 
                    <div class="informacion">
                        <p class="semi-bold">vendimos la primero la primera camara</p> 
                      <p>Primero: tenemos el sitio web</p>
                      <p>whatapp: <a href="+51 944187579" target="_blank" style="text-decoration:none">Perudelivery124@gmail.com</a></p>
                    </div>
                </li>
                <li>
                  <div class="date">2020 - ...</div>
                  <div class="informacion">
                        <p class="semi-bold">telegram <a href="+51 944187579" target="_blank" style="text-decoration:none">(SENATI)</a></p> 
                      <p>Carrera: Ingenieria de Software con Inteligencia Artificial</p>
                    </div>
                </li>
            </ul>
        </div>
        <div class="resumen_item resumen_hobby">
          <div class="titulo">
              <p class="bold">Pasatiempos</p>
            </div>
          <ul>
            <li><i class="fas fa-book"></i></li>
            <li><i class="fas fa-gamepad"></i></li>
            <li><i class="fas fa-music"></i></li>
            <li><i class="fab fa-pagelines"></i></li>
          </ul>
  

<div class="footer">
  <table>
    <tr>
      <td>|||Contactos: </td>
      <td></td>
      <td>|||Dirección:  Av cuestadelangel202</td>
     
      
    </tr>
    <tr>
      <td></td>
      <td>|||Localidad: Arequipa</td>
      <td></td>
    </tr>
    <tr>
      <td>|||Correo: perudelivery124@gmail.com</td>
    </tr>
  </table>
</div>
<style>
  .footer{
    background-color: #474242;
    width: 100%;
    
    
  }
  td{
        color: aliceblue;
        text-align: left;
      
      
  }
  .next{
    text-align: center;
    text-emphasis-color: black;
    background-color: rgb(44, 169, 241) ;
    
    text-decoration: none;
  }
  
  </style>
  <div class="next">
    <p><a href="pagina2.html" style="text-decoration: none;"><h2>--------------------Siguiente pagina--------------------</h2></a></p>

  </div>
</body>

</body>
</html>
