# proyecto2
/*
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
*/
/* 
    Created on : Jul 21, 2017, 6:56:49 PM
    Author     : 00140051
*/
#cabecera {font-family: Arial;
           font-size: 30px;
           text-align: center;
}
#menu ul li{
    list-style-type: none;
    display: inline;
    font-size: 20px;
    background: crimson;
    padding: 5px;
    border-radius: 5px;
}
#cabecera span{
    color: #000;
}
#cuerpo img{
    width: 1000px;
    height: 500px;
    display: block;
    margin: auto;
}
#cuerpo p{
    font-family: ariel;
    font-size: 18px;
   
}
#pie {
    background: red;
    text-align: center;
}
#pie img{
    width: 30px;
}
/*Aqui estamos definiendo el mismo color y tamaño de letra para los enlaces */
a:link, a:visited{
 font-size: 20px;
 background: crimson;   
 text-decoration: none;
}
a:hover{
    background: black;
    color: red;
    font-size: 30px;
}

#menu ul li:hover{
    background: black;
    color: red;
    font-size: 30px;
}
/*Parte del formulario*/
form{
    /*Para centrar formulario y color de fondo*/
    margin:0 auto;
    width: 800px;
    background: gray;
    /*Ponemos border*/
    boder: 2px solid #CCC;
    border-radius: 20px;
}
form div{/*Poner espacio entre elementos*/
    margin-top: 1em;
     
    
}
label{/*Poner los labels del mismo ancho*/
    display: inline-block;
    width: 100px;
    text-align: right;
    font-size: 20px;
}
input textarea{
    width: 200px;
    font: 1em sans-serif;
}

input:focus, textarea:focus{
    border: 2px solid #000;
    background: #f3f3f3;
}
textarea{
    vertical-align: middle;
}
button{
    margin-left: 5em;
    font-size: 20px;
    
}
h1{
    text-align: center;
}
#select {
   margin-left: 2em;
   font-size: 20px;  
    
}
