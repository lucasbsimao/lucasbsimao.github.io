---
layout: page
name: index
title: Personal Website
description: >
  Site pessoal - Lucas Borsatto - Back-end developer
hide_description: true
---
<!-- <script type="text/javascript">
	document.getElementsByClassName("page-title")[0].classList.add("sr-only");
</script> -->

<style type="text/css">
	.page-title {
		position: absolute;
		width: 1px;
  		height: 1px;
  		margin: -1px;
  		border: 0;
  		padding: 0;
  		clip: rect(0 0 0 0);
  		overflow: hidden;
	}
</style>

<h2 class="h1" style="color: rgb(1,92,171)" id="about">Sobre</h2>

Olá, sou Lucas Borsatto, desenvolvedor back-end há mais de 8 anos.

Tenho conhecimentos sólidos em Java, Node e AWS. Além disso, tenho experiência prática na aplicação de DDD, TDD e Microsserviços síncronos e assíncronos. Normalmente, tenho um papel de mentor de novos membros da equipe, tendo projetado o primeiro processo de onboarding da equipe na Ame. Também tenho a prática de ensinar pessoas com menos experiência, tendo em meu currículo diversas palestras que muitas vezes resultam em POCs que contribuem muito para o crescimento do negócio e dos projetos que atuo. Mantenho um blog no Medium sobre desenvolvimento de software e também atuei como coordenador do GDG Petrópolis por muitos anos.

Gosto muito de tecnologia, astronomia, futebol e xadrez (aceito desafios no [chess.com](https://www.chess.com/member/lucasb001)).


<div class="body-social sidebar-social">
  <ul>
    <li> <a href="https://www.linkedin.com/in/lucas-borsatto-8b9a405a/" title="LinkedIn" class="no-mark-external" target="_blank"> <span class="icon-linkedin2"></span> <span aria-hidden="true">LinkedIn </span><span class="sr-only">LinkedIn</span></a></li>
    <li> <a href="https://github.com/lucasbsimao" title="GitHub" class="no-mark-external" target="_blank"> <span class="icon-github"></span> <span aria-hidden="true">Github </span><span class="sr-only">GitHub</span></a></li>
    <li> <a href="https://stackoverflow.com/users/2581736/lucas-borsatto" title="Stack Overflow" class="no-mark-external" target="_blank"> <span class="icon-stackoverflow"></span> <span aria-hidden="true">Stack Overflow</span><span class="sr-only">Stack Overflow</span></a></li>
  </ul>
</div>

---
<h2 class="h1" style="color: rgb(1,92,171)" id="lectures">Palestras </h2>

<h3 class="h2">DDD e SOLID aplicado para API Design</h3>

<h3 class="h2">Data: 07/12/2023</h3>

Apresentação para orientação interna da equipe de desenvolvimento da Porto Seguro. Foram levantados pontos de melhoria no desenvolvimento das APIs, como melhor aplicação de SOLID e conceitos de DDD e REST.

[PDF da palestra](https://lucasbsimao.github.io/lectures/ApiDesign.pdf)
<br/>

<h3 class="h2">Containers Python na AWS</h3>

<h3 class="h2">Data: 12/05/2020</h3>

Tutorial feito em evento do GDG Petrópolis, no qual apresentei um passo a passo de como containers funcionam e como realizar um deploy básico na AWS. Foram apresentadas vantagens que a utilização de Docker pode oferecer ao desenvolvimento de projetos.

[PDF da palestra](https://lucasbsimao.github.io/lectures/Containers.pdf)

<br/>

<h3 class="h2">Programação Assíncrona com Kotlin Coroutines</h3>

<h3 class="h2">Data: 23/11/2019</h3>

Apresentação feita no Dev Fest de 2019 no Rio de Janeiro com o objetivo de mostrar a utilização de Kotlin Coroutines e como funcionam, diferenciando-as das threads e os principais pontos de cada abordagem.

[PDF da palestra](https://lucasbsimao.github.io/lectures/kotlincoroutines-200207132933.pdf)

<br/>

<h3 class="h2">Kotlin Backend</h3>

<h3 class="h2">Data: 22/08/2019</h3>

Apresentação interna para a equipe de desenolvedores da Americanas S/A, demonstrando o desenvolvimento de uma POC transformando um dos micro serviços que a equipe gerenciava de Java para Kotlin. Foram apresentadas diferenças de performance e de código, e quais vantagens Kotlin apresenta no desenvolvimento de micro serviços.

[PDF da palestra](https://lucasbsimao.github.io/lectures/kotlinbackendpresentation-190823024648.pdf)

<br/>

<h3 class="h2">Generative Adversarial Networks</h3>

<h3 class="h2">Data: 26/04/2017</h3>

Introdução feita sobre GANs (Generative Adversarial Networks) no Meetup de Data Science do Rio de Janeiro, sendo este o tópico foco da minha Iniciação Científica da época. Foi feito um aprofundamento teórico estatístico e das bases do funcionamento das GANs, que foram primordiais para algoritmos de IA geradores de imagens. 

[PDF da palestra](https://lucasbsimao.github.io/lectures/generativeadversarialnets-170426154023.pdf)

<br/>

---
<h2 class="h1" style="color: rgb(1,92,171)" id="articles">Artigos </h2>

<h3 class="h2">Insights and Optimizations from Benchmarking frameworks</h3>

Neste artigo realizei a medição de algumas métricas de saturação e latência com alguns frameworks em Java, Kotlin, Go e Nodejs. Além disso, são mostradas algumas abordagens para melhora de performance de cada framework e linguagem.

[Link do artigo](https://medium.com/@lucas01/insights-and-optimizations-from-benchmarking-frameworks-a089bf44320)

<style type="text/css">
  .body-social > ul {
    display: inline-block;
    list-style-type: none;
    margin-bottom: 0;
    overflow: hidden;
    padding: 0;
  }

  .body-social > ul > li {
    float: left;
    
    /* padding-left: 5px; */
    padding-right: 10px;
    
    /* display: inline-block; */
  }


  .body-social > ul > li > a {
    display: inline;
    text-align: center;
    font-size: 0.95rem;
    font-weight: 600;
    /*width: 3rem;*/
    /*height: 4rem;*/
    padding: 4px;
    
    /* line-height: 3rem; */
    
    text-decoration: none;
    border-width: 1px;
    border-style: solid;
    border-radius: 5px;
    transition: background-color 250ms, color 250ms, text-decoration-color 250ms, border-color 250ms;
    
    /* border-bottom: none; */
  }

  .body-social > ul > li > a:not(.btn):not(.no-hover) {
    border-color: var(--accent-color);
  }

  .body-social > ul > li > a:hover {
    color: white;
    background-color: var(--accent-color);
    border-radius: 5px;
    padding: 4px;
    transition: background-color 250ms, color 250ms, text-decoration-color 250ms, border-color 250ms;
  }

  .note-sm:before, .note:before {
    font-size: 1rem;
    color: rgb(1,92,171);
</style>
