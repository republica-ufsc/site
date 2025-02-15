<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css"/>
  <meta name="autor" content="Rafael Schüler de Carvalho 2023"
  <title>República de estudantes da UFSC</title>
  
  <style>
  
  
  
  select {
   -webkit-appearance:none;
   -moz-appearance:none;
   -ms-appearance:none;
   appearance:none;
   outline:0;
   box-shadow:none;
   border:0!important;
   background: #5c6664;
   background-image: none;
   flex: 1;
   padding: 0 .5em;
   color:#fff;
   cursor:pointer;
   font-size: 1em;
   font-family: 'Open Sans', sans-serif;
}
select::-ms-expand {
   display: none;
}
.select {
   position: relative;
   display: flex;
   width: 20em;
   height: 3em;
   line-height: 3;
   background: #5c6664;
   overflow: hidden;
   border-radius: .25em;
}
.select::after {
   content: '\25BC';
   position: absolute;
   top: 0;
   right: 0;
   padding: 0 1em;
   background: #2b2e2e;
   cursor:pointer;
   pointer-events:none;
   transition:.25s all ease;
}
.select:hover::after {
   color: #23b499;
}
  </style>
  
  
</head>
<body>
  
  <div class="wrapper">
    <main>
      <section class="module parallax parallax-1">
        <h1>Alojamento estudantil - República de estudantes da UFSC</h1><br>
		<h1>100% Amazonia</h1>
      </section>

      <section class="module content">
        <div class="container">
          <h2>Açaí Palm</h2>
          <p>
            O açaizeiro (Euterpe oleracea) cresce ao longo dos afluentes da Amazônia. A planta e o seu fruto foram descobertos pelos indígenas da floresta e até hoje funcionam como base alimentar para a população local. É nativo do Pará, que detém 90% da produção de açaí do país, presente em grande parte no estuário do rio Amazonas. Também está nos Estados do Amapá, Amazonas e Maranhão.s!          </p>
        </div>
      </section>
      
	  <p>
	  

	  </p>
	  
      <p>Utilize o formulário abaixo para o auto atendimento:</p>
	  
      <form name="comprar" method="post" action="formmail.html">
	  
        <label>Nome
          <input name="Nome ou Razão Social:Nome ou Razão Social:" type="text" id="Nome">
        </label>
      
	  
	  
	  
      <p>CPF/CNPJ:
        <input name="Nome ou Razão Social:Nome ou Razão Social:2" type="text" id="Nome ou Razão Social:Nome ou Razão Social:">
      </p>
      <p>Rua/número/apto:
        <input name="Nome ou Razão Social:Nome ou Razão Social:22" type="text" id="Nome ou Razão Social:Nome ou Razão Social:2">
      </p>
      <p>Cidade:
        <input name="Nome ou Razão Social:Nome ou Razão Social:23" type="text" id="Nome ou Razão Social:Nome ou Razão Social:22">
      </p>
      <p>CEP:
        <input name="Nome ou Razão Social:Nome ou Razão Social:24" type="text" id="Nome ou Razão Social:Nome ou Razão Social:23">
      </p>
      <p>Telefone:
        <input name="Nome ou Razão Social:Nome ou Razão Social:25" type="text" id="Nome ou Razão Social:Nome ou Razão Social:24">
      </p>
      <p>Whatsapp:
        <input name="Nome ou Razão Social:Nome ou Razão Social:26" type="text" id="Nome ou Razão Social:Nome ou Razão Social:25">
      </p>
      <p>email:
        <input name="Nome ou Razão Social:Nome ou Razão Social:27" type="text" id="Nome ou Razão Social:Nome ou Razão Social:26">
      </p>
      <p>instagram:
        <input name="Nome ou Razão Social:Nome ou Razão Social:28" type="text" id="Nome ou Razão Social:Nome ou Razão Social:27">
      </p>
      <p>facebook:
        <input name="Nome ou Razão Social:Nome ou Razão Social:29" type="text" id="Nome ou Razão Social:Nome ou Razão Social:28">
      </p>
      <p>site:
        <input name="Nome ou Razão Social:Nome ou Razão Social:210" type="text" id="Nome ou Razão Social:Nome ou Razão Social:29">
      </p>
      <p>Produto:      
        <label>produto
        <select name="select">
		<
		
        </select>
        </label>
      </p>
      <p>Quantidade:      
        <select name="select2">
        </select>
      </p>
      <p>Forma de Pagamento:
        <select name="select3">
        </select>
      </p>
	  </form>
	  
	  
      <p>&nbsp; </p>
      <p>&nbsp;</p>
	  
	  <h1>Choose a book format</h1>
<div class="select">
   <select name="format" id="format">
      <option selected disabled>Choose a book format</option>
      <option value="pdf">PDF</option>
      <option value="txt">txt</option>
      <option value="epub">ePub</option>
      <option value="fb2">fb2</option>
      <option value="mobi">mobi</option>
   </select>
</div>
	  
	  
	  
      <p>&nbsp;</p>
      <section class="module parallax parallax-2">
        <h1>O Rep. de estudantes da UFSC</h1>
      </section>

      <section class="module content">
        <div class="container">
          <h2></h2>
          <p>
            
Lugar funcional, para quem está focado nos estudos, perfeito para tomar banho, descansar, estudar e se organizar para as aulas diárias na universidade. </p>          
        </div>
      </section>

      <section class="module parallax parallax-3">
        <h1>Produto Natural</h1>
      </section>

      <section class="module content">
        <div class="container">
          <h2>Original</h2>
          <p>
          
Obrigatória a apresentação do comprovante de matrícula, semestralmente.</p>          
        </div>
      </section>
    </main>
  </div>

</body>
</html>
