<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Carmen</title>
</head>

<body style="font-family: Arial; padding:40px">

<h2>Carmen</h2>
<pre id="alma">Cargando...</pre>

<script>
fetch("carmen-system.txt")
.then(r => r.text())
.then(t => document.getElementById("alma").textContent = t);
</script>

</body>
</html>
