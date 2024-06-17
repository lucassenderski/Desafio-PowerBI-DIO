# processando_e_transformado_dados_com_powerBI
2º Projeto de desafio do Módulo de Power BI do Bootcamp em Ciência de Dados com Python - Jun - 2004 

Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI


1. Criação de uma instância na Azure para MySQL: No portal da Azure, crie uma instância do MySQL seguindo as instruções.
2. Criar o Banco de dados: Utilize os scripts do GitHub para criar seu banco de dados na instância do MySQL.
3. Integração do Power BI com MySQL no Azure: No Power BI, use a opção “Obter Dados” e selecione “MySQL database” para conectar-se à sua instância.
4. Verificar problemas na base: Analise a base de dados para identificar inconsistências ou erros que precisam ser corrigidos antes da transformação dos dados.

Para as diretrizes de transformação dos dados:

1. Verifique os cabeçalhos e tipos de dados: Assegure-se de que os cabeçalhos estão corretos e que os tipos de dados correspondem ao conteúdo das colunas.
2. Modifique os valores monetários para o tipo double preciso: Altere o tipo de dados das colunas monetárias para ‘double’ para garantir precisão nos cálculos.
3. Verifique a existência dos nulos e analise a remoção: Identifique campos nulos e decida se devem ser removidos ou tratados de outra forma.
4. Employees com nulos em Super_ssn: Verifique se esses employees são gerentes e se há algum colaborador sem gerente atribuído.
5. Departamento sem gerente: Identifique departamentos sem gerente e preencha as lacunas conforme necessário.
6. Número de horas dos projetos: Confira se as horas registradas nos projetos estão corretas e completas.
7. Separar colunas complexas: Divida colunas que contêm múltiplas informações em colunas mais simples para facilitar a análise.
8. Mesclar consultas employee e departament: Crie uma tabela combinada no Power BI ou via SQL, mantendo atenção ao tipo de junção para não perder dados importantes.
9. Eliminar colunas desnecessárias: Remova informações que não são relevantes para a análise para simplificar o conjunto de dados.
10. Junção dos colaboradores e nomes dos gerentes: Faça isso utilizando consultas SQL ou mesclando tabelas no Power BI, documentando o processo no README se usar SQL.
11. Mescle Nome e Sobrenome: Crie uma coluna única com o nome completo dos colaboradores.
12. Mescle nomes de departamentos e localização: Isso cria uma chave única por combinação, útil para modelagem futura como o modelo estrela.
13. Utilizar ‘mesclar’ em vez de ‘atribuir’: No contexto do Power BI, ‘mesclar’ é usado para combinar tabelas com base em colunas relacionadas, enquanto ‘atribuir’ não é um termo padrão neste contexto. ‘Mesclar’ permite criar relações entre tabelas, o que é essencial para análises mais complexas e criação de modelos como o modelo estrela mencionado no passo 13.