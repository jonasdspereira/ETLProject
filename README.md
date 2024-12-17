# ETL com Requests em Python

Este projeto é um exemplo de um pipeline ETL (Extract, Transform, Load) usando a biblioteca `requests` em Python. O objetivo é extrair dados de uma API, transformá-los e carregá-los em um banco de dados.

## Requisitos

- Python 3.6+
- Bibliotecas Python:
  - `requests`
  - `pandas`
  - `sqlalchemy`

## Instalação

1. Clone este repositório:
    ```sh
    git clone https://github.com/seu-usuario/etl-requests-python.git
    cd etl-requests-python
    ```

2. Crie um ambiente virtual e ative-o:
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Configure as variáveis de ambiente no arquivo `.env`:
    ```env
    API_URL=https://api.exemplo.com/dados
    DATABASE_URL=sqlite:///dados.db
    ```

2. Execute o script ETL:
    ```sh
    python etl.py
    ```

## Estrutura do Projeto

- `etl.py`: Script principal que executa o pipeline ETL.
- `requirements.txt`: Arquivo com as dependências do projeto.
- : Este arquivo.

## Funcionalidades

- **Extração**: Usa a biblioteca `requests` para obter dados de uma API.
- **Transformação**: Usa a biblioteca `pandas` para transformar os dados.
- **Carga**: Usa a biblioteca `sqlalchemy` para carregar os dados em um banco de dados.

## Contribuição

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.