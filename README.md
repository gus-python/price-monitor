Monitor de Preços com Python
Projeto de automação com foco em coleta e análise de dados para tomada de decisão
Desenvolvido em Python para monitoramento de preços em e-commerces, com coleta de dados via Selenium e armazenamento de histórico em Excel.
O projeto simula um cenário real de análise e acompanhamento de preços, aplicando lógica de negócio, tratamento de dados e automação de processos.
Principais funcionalidades
* Coleta automatizada de preços em páginas web dinâmicas
* Verificação de disponibilidade do produto
* Comparação com preço alvo definido
* Comparação com último preço registrado (histórico)
* Armazenamento dos dados em planilha Excel
* Tratamento de exceções para evitar falhas no processo
- Tecnologias utilizadas
* Python
* Selenium (automação de navegador)
* OpenPyXL (manipulação de Excel)
- Lógica do projeto
O script percorre uma lista de URLs e, para cada produto:
1. Acessa a página com Selenium
2. Extrai o preço do produto
3. Verifica se o item está disponível
4. Compara o valor atual com:
   * um preço alvo (ex: R$ 900)
   * o último preço registrado
5. Armazena o novo valor em uma planilha `.xlsx`

Autor: Gustavo Souza
