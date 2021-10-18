<h1>OBJETIVO DA AULA</h1>

<p>Nesta segunda aula da Imersão Dev, o objetivo é criar um programa que peça para o usuário fornecer um valor em real, e a partir desse valor o programa vai exibir na tela o equivalente em dolar. Neste programa, vamos aprender como o Javascript pode interagir com o HTML através de botões, valores decimais e conversão de tipo.</p>

<h3>PASSO A PASSO</h3>
<p>Antes de começarmos a escrever qualquer linha de código, temos que pensar no caminho que o programa deve percorrer e quais informações ele precisa para ser executado corretamente.<br>
1. O que o programa deve fazer? Converter real para dolar Ok, mas como isso é feito? Se fôssemos converter 1 real para dolar “na mão”, faríamos a seguinte conta: 1 * 5 = 5.0 (supondo que a conversão seja 5 para 1)<br>
Onde 1 é o valor em reais que queremos converter e 5 é a taxa média do dólar no momento em que escrevemos este texto. Multiplicando um valor pelo outro, temos o resultado em reais:<br>
5.0 .<br>
1. Como o programa vai receber essas informações? Podemos concluir, a partir do que vimos no ponto 1, que os dados que o programa precisa para funcionar são:<br>
2. o valor em dólar que queremos converter (será fornecido pelo usuário);<br>
3. a taxa do dólar que será utilizada na conversão (que nós vamos fornecer ao programa no momento em que escrevemos o código);<br>
4. exibir “resultado” da conversão. Após executar todo o código, o programa deve exibir ao usuário um número que representa o resultado da operação valor em dólar * taxa de câmbio.