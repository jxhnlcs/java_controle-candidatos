# Processo Seletivo - Gerenciador de Candidaturas
Este é um projeto simples em Java chamado "Processo Seletivo" que simula um processo de seleção de candidatos para uma vaga de emprego. O projeto inclui funções para entrar em contato com os candidatos, imprimir a lista de candidatos, selecionar candidatos com base em critérios de salário e analisar as pretensões salariais dos candidatos.

## Funcionalidades
Entrando em Contato com Candidatos
A função entrandoEmContato tenta entrar em contato com os candidatos da lista e registra o número de tentativas realizadas. O objetivo é alcançar o candidato em até 3 tentativas. Se o contato for bem-sucedido, uma mensagem informando o sucesso é exibida.

### Imprimindo Lista de Candidatos
A função imprimirSelecionados imprime a lista de candidatos e seus índices usando dois tipos diferentes de loops (for e for-each).

### Seleção de Candidatos
A função selecaoCandidatos simula a seleção de candidatos com base em suas pretensões salariais. Ela verifica se o salário pretendido pelos candidatos é compatível com um salário base e seleciona até 5 candidatos que atendem aos critérios.

### Análise de Candidato
A função analisarCandidato compara o salário base com o salário pretendido de um candidato e decide se deve ligar para o candidato, fazer uma contra proposta ou aguardar outros resultados.

### Como Utilizar
Para utilizar este projeto simples, siga os seguintes passos:

1. Abra o código-fonte em um ambiente de desenvolvimento Java.

2. Execute o método main na classe ProcessoSeletivo para iniciar a simulação.

3. O programa irá interagir com os candidatos, imprimir a lista de candidatos, selecionar candidatos e analisar suas pretensões salariais.
