# romarioprojetobus345687
romario
<html>
<head>
  <title>Código CSS - Entendendo a folha de estilos</title>
</head>
<body>
<h1>Sou a tag h1</h1>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ultrices feugiat ullamcorper.
 Cras ut tristique velit. Fusce euismod turpis at lorem vestibulum malesuada. Mauris porttitor sem
 vitae leo tincidunt varius. Nunc vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante
 metus. Fusce leo ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi
 dignissim auctor quis eget augue.</p>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ultrices feugiat ullamcorper.
Cras ut tristique velit. Fusce euismod turpis at lorem vestibulum malesuada. Mauris porttitor sem
vitae leo tincidunt varius. Nunc vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante
metus. Fusce leo ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi
dignissim auctor quis eget augue.</p>

</body>
</html>

Como ele é aplicado diretamente naquela tag específica, é impossível reutilizar ele em outra tag, tendo que sempre copiar e colar ou criar um novo para cada tag que você queira estilizar.

<html>
<head>
  <title>Código CSS - Entendendo a folha de estilos</title>
</head>
<body>
<h1 style="font-style: italic;">Sou a tag h1</h1>

<p style="color:red;">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at lorem
vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius. Nunc vulputate
interdum sem, eu semper metus suscipit ut. Sed eget ante metus. Fusce leo ante, aliquam
in sagittis id, auctor quis turpis. Donec vitae magna quis mi dignissim auctor quis eget
augue.</p>

<p style="color:red;">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at
lorem vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius. Nunc
vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante metus. Fusce leo
ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi dignissim
auctor quis eget augue.</p>

</body>
</html>
<html>
<head>
  <title>Código CSS - Entendendo a folha de estilos</title>
<style type="text/css">
h1{
  font-style: italic;
}
p{
  color: red;
}
</style>
</head>
<body>
<h1>Sou a tag h1</h1>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ultrices feugiat
ullamcorper. Cras ut tristique velit. Fusce euismod turpis at lorem vestibulum malesuada.
Mauris porttitor sem vitae leo tincidunt varius. Nunc vulputate interdum sem, eu semper
metus suscipit ut. Sed eget ante metus. Fusce leo ante, aliquam in sagittis id, auctor
quis turpis. Donec vitae magna quis mi dignissim auctor quis eget augue.</p>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ultrices feugiat
ullamcorper. Cras ut tristique velit. Fusce euismod turpis at lorem vestibulum malesuada.
Mauris porttitor sem vitae leo tincidunt varius. Nunc vulputate interdum sem, eu semper
metus suscipit ut. Sed eget ante metus. Fusce leo ante, aliquam in sagittis id, auctor
quis turpis. Donec vitae magna quis mi dignissim auctor quis eget augue.</p>

</body>
</html>
<html>
<head>
  <title>Código CSS - Entendendo a folha de estilos</title>
<style type="text/css">
h1{
  font-style: italic;
}
#fundo{
  background-color: #a3a9fa;
}
.paragrafo{
  color: red;
}
.paragrafo2{
  color: #0018ff;
}
</style>
</head>
<body>
<div id="fundo">
  <h1>Sou a tag h1</h1>

  <p class="paragrafo">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at
  lorem vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius.
  unc vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante metus.
  Fusce leo ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis
  mi dignissim auctor quis eget augue.</p>

  <p class="paragrafo2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at
  lorem vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius. Nunc
  vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante metus. Fusce leo
  ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi dignissim
  auctor quis eget augue.</p>
</div>

</body>
</html>
<link rel="stylesheet" type="text/css" href="aqui entra o
link do seu arquivo externo">
h1{
  font-style: italic;
}
#fundo{
  background-color: #a3a9fa;
}
.paragrafo{
  color: red;
}
.paragrafo2{
  color: #0018ff;
}
<html>
<head>
  <title>Código CSS - Entendendo a folha de estilos</title>
<link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
<div id="fundo">
  <h1>Sou a tag h1</h1>

  <p class="paragrafo">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at
  lorem vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius. Nunc
  vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante metus. Fusce leo
  ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi dignissim
  auctor quis eget augue.</p>

  <p class="paragrafo2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  Duis ultrices feugiat ullamcorper. Cras ut tristique velit. Fusce euismod turpis at
  lorem vestibulum malesuada. Mauris porttitor sem vitae leo tincidunt varius. Nunc
  vulputate interdum sem, eu semper metus suscipit ut. Sed eget ante metus. Fusce leo
  ante, aliquam in sagittis id, auctor quis turpis. Donec vitae magna quis mi dignissim
  auctor quis eget augue.</p>
</div>

</body>
</html>
