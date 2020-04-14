# Introduction to css


![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQt_1HgkAy6BTXQmJfrS81Mema1KeBrIARmYw_vIs04z1eyuM350w&s)

 **CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface**

 ## On the next page, you will see how CSS rules can also be placed in your HTML pages and we will discuss when you might want to do this
 
 **<!DOCTYPE**
  **html>** 
  **<html>**
   **<head>** 
    **<title>Introducing CSS</title>** 
     **<link href="css example.css" type="text/css"rel="stylesheet"/>**
     **head>**
      **<body>**  
       **<h1>example to css </h1>**
        **<p>A <i>potager</i> is a French term for an  ornamental vegetable or kitchen garden ... </p>**
          **<h2>What to Plant</h2>**
            **<p>Plants are chosen as much for their functionality as for their color and form ... </p>**
             **</body>**
             **</html>**
             
             ## and in css file do 

             **body{ font-family: Arial, Verdana, sans-serif;}**             **h1, h2 { color: #ee3e80;} p { color: #665544;}**

# also there is Three way to do  a css design :

 >External 
 >Enternal 
 >Inline



![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNxNT59r_zFJMBxqIKKufZKFvrR4dOw4kdyBo1oJ5hc57RiB9B&s)
# Color

## Color can really bring your pages to life

 ### The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways

  > ***rgb values*** 
  > ***hex Codes***
  > ***Color names***

  # Example 

  **/* color name */**
   **h1 {** 
       ***color: DarkCyan;}**
        **/*  hex code */** 
        **h2 { color: #ee3e80;} /** 
        **rgb value */** 
        **p {** 
        **color: rgb(100,100,90);}**