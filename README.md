# teste-fcamara
###Teste FCamara

START
### 1. Se você tivesse 5 diferentes arquivos de folhas de estilo, qual seria a melhor forma de integrá-los no site?
   Eu usaria no caso o elemento <link rel="stylesheet" href="nome_do_arquivo.css"> 5 vezes no código. Não me aprofundei
   muito no assunto, mas acho que com o pré-processador SASS pode ajudar isso também.
   
### 2. Fale 3 formas de diminuir o page load (tempo de carregamento real e percebido).
    *Usando um Minify (Biblioteca que pode deixar seu código JavaScript e CSS minificado ou seja diminuir o tamanho dele em kbytes.)
    *Otimizar imagens
    *Usar o HTML Tidy para removar os espaços em brancos.
    
### 3. Quais ferramentas você usa para testar a performance do seu código?
   Tenho pouco conhecimento sobre, pois não usei nada disso por enquanto, o que sei que uma vez quando trabalhei em uma agência,
   o rapaz me mostrou o PageSpeed do Google
  
### 4. Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
   *Header
   *Nav
   *Aside
   *Section
   *Article
   *Footer
   
### 5. Você pode explicar a diferença entre GET e POST?
   Metódo GET serve para realizar pesquisar no Servidor e o Método POST serve para enviar informações de forma segura para
   o servidor como por exemplo um formulário de pesquisa ou algo do tipo.
   
### 6. Liste quantas propriedades display você puder lembrar.
    *flex
    *grid
    *block
    *inline
    *inline-block
    *none
    
### 7. Qual a diferença entre inline e inline-block?
       Para posicionar os elementos um do lado do outro, precisamos utilizar a propriedade inline, porém ao escolher essa opção
       ele acaba não aparecendo o a altura e largura. Tem a outra propriedade que é o display block, nessa é possível posicionar os            elementos e escolher o a altura e largura, porém eles não ficam alinhados um do lado do outro, por isso é utilizado o display            inline-block, ao inserir isso no seu código, é possivel alinhar os elementos e ao mesmo tempo escolher a largura e altura do seu        elemento.
       
### 8. Qual a diferença entre elementos posicionados de forma relativa, fixa, absoluta e estática?
       Relative posiciona o elemento de forma relativa ao local onde foi criafo, mas para posicionar de forma correta
       é necessário usar junto ao position relative, as propriedades top, right, bottom e left.
       Fixed posiciona o elemento de forma fixa na tela, como por exemplo fixar um header com menu de navegação no
       tipo da tela.
       Absolute posiciona o elemento onde a gente quer, ou seja, esquerda, direita, em cima ou abaixo
       de acordo com a nossa tela.
       Static nada mais é que um elemento estático, ou seja, não se move, não acontece nada.
       
### 9. Qual a diferença entre .call e .apply?
    Não tenho conhecimento sobre.
    
### 10. Qual a diferença entre == e ===?
    == testa se um valor é igual ao outro trazendo a resposta "true" ou "false", 
    por exemplo 1 == 1 (No caso 1 é igual a 1, então "true"), se fosse 1 == 2 a resposta seria "false" porque 1 não é igual a 2.
    === testa se o valor é igual ao outro mas através do tipo de dados (Por exemplo : String, Boolean, Number, Array e etc.)
    Ex: 1 == '1'? Sim, é 'true' pois o número 1 é igual ao número 1, no outro caso 1 === '1'? Não, é 'false' pois 1 (Number) e 
    '1' é String, então eles não são iguais por conta dos tipos de dados.


