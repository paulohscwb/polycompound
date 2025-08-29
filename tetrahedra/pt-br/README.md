<link rel="stylesheet" href="../../scripts/style.css">
<meta charset="utf-8">
<script type="text/x-mathjax-config">
	  MathJax.Hub.Config({
		showProcessingMessages: false,
		tex2jax: { inlineMath: [['$','$'],['\\(','\\)']] }
	  });
</script>
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_HTMLorMML"></script>
<link rel="icon" type="image/png" href="../vr/salas/imagens/icone.png">
<h2>Visualização de Poliedros com Realidade Virtual (RV) em A-frame</h2>
<b>autor:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
<br><b>contato:</b> <a href="#"> paulohscwb@gmail.com </a>
<br><a href="https://paulohscwb.github.io/polycompound/tetrahedra/">english version</a>
<form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected>Mais sólidos:</option>
		<option value="../../compounds1/pt-br/">Família dos tetraedros</option>
		<option value="../../compounds2/pt-br/">Família dos cubos</option>
		<option disabled value="../../tetrahedra/pt-br/">Embalagens tetraédricas</option>
		<!--<option value="../../compounds3/pt-br/">Família dos octaedros</option>
		<option value="../../compounds4/pt-br/">Família dos dodecaedros e icosaedros 1</option>
		<option value="../../compounds5/pt-br/">Família dos dodecaedros e icosaedros 2</option>
		<option value="../../compounds6/pt-br/">Compostos de poliedros duais</option>
		<option value="../../compounds7/pt-br/">Compostos de dois poliedros</option>-->
	</select>
</form>
<script>
function urlHandler(value) {                               
    window.location.assign(`${value}`);
}
</script>

<p id="p1"></p>
  <h2 align="center"><img src="../vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Embalagens tetraédricas</h2>
  A embalagem tetraédrica é um problema de organizar tetraedros idênticos no espaço tridimensional, com o objetivo de preencher a maior parte possível do espaço. Os arranjos destas embalagens incluem os formatos esférico, plano, prismático, antiprismático e cúbico.
<br>A estrutura de embalagem mais densa conhecida de tetraedros regulares é formada por um conjunto de bipirâmides triangulares, que preenche 85,63% do espaço em um formato esférico.
<br>Este trabalho mostra os compostos de tetraedros, modelados para visualização em Realidade Virtual.
 <p align="center"><a href="#m3d">Modelos 3D</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../../pt-br/">Página Inicial</a></p>
<hr>
  <p align="center"><img src="../vr/salas/videos/compound1.gif" style="max-width: 45%; border-radius:5px; margin-right:15px" loading="lazy" alt="VR immersive compound"/><img src="../vr/salas/videos/compound2.gif" style="max-width: 45%; border-radius:5px;" loading="lazy" alt="VR immersive compound"/></p> 
<hr>
<h3 id="m3d" align="center">Modelos 3D</h3>
<iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxUBFOD4zwVl2mMkGU-phDxF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<h4>1. Tetraedro de Baumgartner</h4>
<a href="../vr/Baumgartner.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/0A.png" class="foto" alt="tetraedro de Baumgartner"></a>
 <br>O tetraedro de Baumgartner (descoberto em 1968) pode ser usado para composição de embalagem em formato prismático.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{11} \over{2} }$, $\mathsf{ \sqrt{3} }$, $\mathsf{ \sqrt{3} \over{2} }$, $\mathsf{ 2 }$.
 <br><b>ângulos diédricos</b>: 106.74°, 30°, 60°, 73.26°, 90°.
 <br>
<hr>
<h4>2. Tetraedro alto irlandês</h4>
<a href="../vr/IrishHigh.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/1A.png" class="foto" alt="Tetraedro alto irlandês"></a>
 <br>O tetraedro alto irlandês (descoberto em 1994 por Denis Weaire e Robert Phelan) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ {1} \over{2} }$, $\mathsf{ \sqrt{6} \over{4} }$.
 <br><b>ângulos diédricos</b>: 53.13°, 78.46°.
 <br>
<hr>
<h4>3. Tetraedro medial irlandês</h4>
<a href="../vr/IrishMedial.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/3A.png" class="foto" alt="Tetraedro medial irlandês"></a>
 <br>O tetraedro medial irlandês (descoberto em 1994 por Denis Weaire e Robert Phelan) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{5} \over{4} }$, $\mathsf{ \sqrt{6} \over{4} }$.
 <br><b>ângulos diédricos</b>: 73.4°, 67.79°.
 <br>
<hr>
<h4>4. Tetraedro baixo irlandês</h4>
<a href="../vr/IrishLow.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/2A.png" class="foto" alt="Tetraedro baixo irlandês"></a>
 <br>O tetraedro baixo irlandês (descoberto em 1994 por Denis Weaire e Robert Phelan) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{5} \over{4} }$, $\mathsf{ {1} \over{2} }$, $\mathsf{ \sqrt{6} \over{4} }$.
 <br><b>ângulos diédricos</b>: 77.4°, 58.41°, 63.43°, 73°.
 <br>
<hr>
<h4>5. Tetraedro escocês</h4>
<a href="../vr/Scottish.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/4A.png" class="foto" alt="Tetraedro escocês"></a>
 <br>O tetraedro escocês (descoberto em 1887 por Lord Kelvin) pode ser usado para composição de embalagem em formato antiprismático.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{3} \over{2} }$, $\mathsf{ {1} }$.
 <br><b>ângulos diédricos</b>: 60°, 90°.
 <br>
<hr>
<h4>6. Tetraedro escocês v2</h4>
<a href="../vr/Scottish1.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/5A.png" class="foto" alt="Tetraedro escocês"></a>
 <br>O tetraedro escocês (descoberto em 1887 por Lord Kelvin) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{3} \over{2} }$, $\mathsf{ {1} }$.
 <br><b>ângulos diédricos</b>: 60°, 90°.
 <br>
<hr>
<h4>7. Tetraedro de Sommerville 1</h4>
<a href="../vr/Sommerville.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/6A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato prismático.
 <br><b>medidas das arestas</b>: $\mathsf{ {2} }$, $\mathsf{ \sqrt{3} }$.
 <br><b>ângulos diédricos</b>: 90°, 60°.
 <br>
<hr>
<h4>8. Tetraedro de Sommerville 1 v2</h4>
<a href="../vr/Sommerville_a.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/7A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ {2} }$, $\mathsf{ \sqrt{3} }$.
 <br><b>ângulos diédricos</b>: 90°, 60°.
 <br>
<hr>
<h4>9. Tetraedro de Sommerville 1 v3</h4>
<a href="../vr/Sommerville_b.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/8A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato prismático.
 <br><b>medidas das arestas</b>: $\mathsf{ {2} }$, $\mathsf{ \sqrt{3} }$.
 <br><b>ângulos diédricos</b>: 90°, 60°.
 <br>
<hr>
<h4>10. Tetraedro de Sommerville 2</h4>
<a href="../vr/Sommerville2.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/9A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato prismático.
 <br><b>medidas das arestas</b>: $\mathsf{ {2} }$, $\mathsf{ \sqrt{2} }$, $\mathsf{ \sqrt{3} }$, $\mathsf{ 1 }$.
 <br><b>ângulos diédricos</b>: 45°, 90°, 60°.
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>
<h4>11. Tetraedro de Sommerville 3</h4>
<a href="../vr/Sommerville3.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/10A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato cúbico.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{3} }$, $\mathsf{ {2} }$, $\mathsf{ 2 \sqrt{2} }$.
 <br><b>ângulos diédricos</b>: 120°, 60°, 45°, 90°.
 <br>
<hr>
<h4>12. Tetraedro de Sommerville 3 v2</h4>
<a href="../vr/Sommerville3_a.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/11A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{3} }$, $\mathsf{ {2} }$, $\mathsf{ 2 \sqrt{2} }$.
 <br><b>ângulos diédricos</b>: 120°, 60°, 45°, 90°.
 <br>
<hr>
<h4>13. Tetraedro de Sommerville 4</h4>
<a href="../vr/Sommerville4.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/12A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato prismático.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{5} \over{2} }$, $\mathsf{ \sqrt{3} }$, $\mathsf{ {2} }$.
 <br><b>ângulos diédricos</b>: 131.8°, 114.1°, 30°, 45°.
 <br>
<hr>
<h4>14. Tetraedro de Sommerville 4 v2</h4>
<a href="../vr/Sommerville4_a.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/13A.png" class="foto" alt="Tetraedro de Sommerville"></a>
 <br>O tetraedro de Sommerville (descoberto em 1923 por Duncan Sommerville) pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{5} \over{2} }$, $\mathsf{ \sqrt{3} }$, $\mathsf{ {2} }$.
 <br><b>ângulos diédricos</b>: 131.8°, 114.1°, 30°, 45°.
 <br>
<hr>
<h4>15. Tetraedro alto galês</h4>
<a href="../vr/WelshHigh.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/14A.png" class="foto" alt="tetraedro alto galês"></a>
 <br>O tetraedro alto galês tem uma combinação de propriedades dos tetraedros irlandês e escocês e pode ser usado para composição de embalagem em formato plano. Este é o tetraedro regular de Platão.
 <br>medida das arestas: $\mathsf{ \sqrt{2} \over{2} }$.
 <br><b>ângulo diédrico</b>: 70.53°.
 <br>
 <hr>
<h4>16. Tetraedro medial galês</h4>
<a href="../vr/WelshMedial.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/16A.png" class="foto" alt="tetraedro medial galês"></a>
 <br>O tetraedro medial galês tem uma combinação de propriedades dos tetraedros irlandês e escocês e pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{11} \over{4} }$, $\mathsf{ \sqrt{2} \over{2} }$.
 <br><b>ângulos diédricos</b>: 67.12°, 74.2°.
 <br>
<hr>
<h4>17. Tetraedro baixo galês</h4>
<a href="../vr/WelshLow.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/15A.png" class="foto" alt="Tetraedro baixo galês"></a>
 <br>O tetraedro baixo galês tem uma combinação de propriedades dos tetraedros irlandês e escocês e pode ser usado para composição de embalagem em formato plano.
 <br><b>medidas das arestas</b>: $\mathsf{ \sqrt{3} \over{2} }$, $\mathsf{ \sqrt{11} \over{4} }$, $\mathsf{ \sqrt{3} \over{4} }$.
 <br><b>ângulos diédricos</b>: 90°, 73.22°, 33.57°, 60°.
 <br>
 <hr>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Polyhedral Compound - Tetrahedra packings: visualization with Virtual Reality</span> de <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polycompound/tetrahedra/pt-br/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> está licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Atribuição-NãoComercial-SemDerivações 4.0 Internacional</a>.

<h4>Como citar este trabalho:</h4> 
<p>Siqueira, P.H., "Polyhedral Compound - Tetrahedra packings: visualization with Virtual Reality". Disponível em: <https://paulohscwb.github.io/polycompound/tetrahedra/pt-br/>, Agosto de 2025.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.14502405"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.14502405.svg" alt="DOI"></a>-->
<br><br><b>Referências:</b>
<br>Weisstein, Eric W. "Polyhedron Compound" From MathWorld-A Wolfram Web Resource. <a href="https://mathworld.wolfram.com/ArchimedeanDual.html" target="_blank">https://mathworld.wolfram.com/PolyhedronCompound.html</a>
<br>Conway, J. H., Torquato, S. "Packing, tiling, and covering with tetrahedra" <a href="https://www.pnas.org/doi/10.1073/pnas.0601389103" target="_blank">https://www.pnas.org/doi/10.1073/pnas.0601389103</a>
<br>McCooey, David I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>
