# prediccion-de-bus
algoritmo hill climbing  (Mejia-Merchan-Perero)

<html>
<head>
 <title>Hill climbing</title>
</head>

<body>
 <script>
  
     var vecino=new Array(6,12,10,14,16,14,20); //vector con los datos heuristicos



    var actual=vecino[0];    //la variable actual es igual al la cabezera
   
    document.write("Inicio=>");
                                       //se recorre cada nodo
    for(var i=0;i<vecino.length;i++){
      if(vecino[i]<=actual){            
       document.write(vecino[i]);document.write("=>");
      }
       actual=vecino[i];
    }
     document.write("Meta");
 </script>
</body>
</html>
