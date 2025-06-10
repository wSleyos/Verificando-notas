<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>textox</title>
</head>
<body>
<script>

function verificarSituacao(nota) {
  if (nota === 10) {
    return "Parabéns! Você tirou nota máxima!";
  } else if (nota >= 7) {
    return "Você está aprovado!";
  } else if (nota >= 4 && nota <= 6) {
    return "Você está de recuperação.";
  } else if (nota < 4) {
    return "Você está reprovado.";
  } else {
    return "Nota inválida.";
  }
}


console.log(verificarSituacao(10));
console.log(verificarSituacao(8));  
console.log(verificarSituacao(3)); 
</script>
</body>
</html>
