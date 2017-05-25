# Teste-1
Contém uma<!DOCTYPE html>
<html>
<body>
<script>
var b;
var i;
document.write("<h1>CALCULAR TABUADA</h1>");

document.write("<button type='button'onclick='calcular()'>Calcular</button>");

document.write("<br><h6><i>por Harry Moura Freitas</i></h6>");

function calcular(){
 b = prompt("Base da tabuada: ");
 document.write("<h1>TABUADA DE "+b+"</h1>");
 for(i=0;i<10;i++)
document.write("<br>"+i+" * "+b+" = "+(i*b));
}
</script>
</body>
</html>
