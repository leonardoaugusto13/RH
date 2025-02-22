# RH

# Dashboard de RH - Gerenciamento de Funcionários

Este repositório contém um script Python que gera uma base de dados fictícia de funcionários e um dashboard de RH que visualiza essas informações. O dashboard fornece insights sobre os colaboradores, como salários, tempo de casa, setores de atuação, e muito mais.

## Estrutura do Repositório

- **faker_funcionarios.ipynb**: Um notebook Jupyter que gera uma base de dados fictícia de funcionários utilizando a biblioteca `Faker`.
- **arquivos_csv/base_fake_dados.csv**: O arquivo CSV gerado pelo script, contendo os dados dos funcionários.

## Script de Geração de Dados

O script `faker_funcionarios.ipynb` utiliza a biblioteca `Faker` para gerar dados fictícios de funcionários, incluindo:

- **ID**: Identificador único para cada funcionário.
- **Nome**: Nome completo do funcionário.
- **Data de Nascimento**: Data de nascimento do funcionário.
- **Cargo**: Cargo ocupado pelo funcionário.
- **Salário**: Salário do funcionário, gerado dentro de uma faixa salarial específica para cada cargo.
- **Sexo**: Gênero do funcionário (Masculino ou Feminino).
- **Setor de Atuação**: Setor em que o funcionário trabalha.
- **Data de Admissão**: Data em que o funcionário foi admitido.
- **Data de Demissão**: Data de demissão, se aplicável (30% dos funcionários têm uma data de demissão gerada aleatoriamente).

### Como Executar o Script

1. Instale as dependências necessárias:
   ```bash
   pip install faker pandas
   ```

2. Execute o notebook `faker_funcionarios.ipynb` para gerar a base de dados. O arquivo CSV será salvo em `arquivos_csv/base_fake_dados.csv`.

## Dashboard de RH

O dashboard de RH visualiza os dados gerados pelo script, fornecendo uma visão geral dos colaboradores da empresa. As principais funcionalidades do dashboard incluem:

### Visão Geral
- **Cargos e Salários**: Distribuição dos salários por cargo.
- **Contratados vs. Desligados**: Proporção de funcionários ativos e desligados.
- **Colaboradores**: Número total de colaboradores.

### Métricas Principais
- **Tempo Médio de Casa (TMC)**: Tempo médio que os funcionários permanecem na empresa.
- **Média Salarial**: Salário médio dos funcionários.
- **Média de Idade**: Idade média dos funcionários.

### Distribuição de Colaboradores
- **Por Sexo**: Proporção de funcionários por gênero.
- **Por Cargo**: Número de funcionários em cada cargo.
- **Por Setor**: Número de funcionários em cada setor da empresa.

### Análise de Salários
- **Salário Médio por Setor**: Salário médio em cada setor de atuação.
- **Despesa Salarial Total**: Custo total com salários por setor.

### Detalhes dos Funcionários
- **Listagem de Funcionários**: Tabela com detalhes de cada funcionário, incluindo matrícula, cargo, nome, sexo, idade, data de nascimento, setor de atuação e tempo de casa.

## Como Utilizar o Dashboard

O dashboard pode ser implementado utilizando ferramentas de visualização de dados como Power BI, Tableau, ou mesmo uma aplicação web desenvolvida com bibliotecas como Dash ou Streamlit em Python. 

## Contribuições

Contribuições são bem-vindas! Se você deseja melhorar o script ou o dashboard, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Nota**: Este projeto foi criado para fins educacionais e de demonstração. Os dados gerados são fictícios e não representam nenhuma empresa ou indivíduo real.
