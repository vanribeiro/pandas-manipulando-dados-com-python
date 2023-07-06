# Notas

## Configurando o Ambiente

Via terminal (PowerShell):

1. Via Admin, instalar o Poetry:

    ```bash
    pip install poetry
    ```

2. Criar um projeto:

    ```bash
    poetry new <nome-do-projeto>
    ```

3. Abrir a pasta do projeto:

    ```bash
    cd <nome-do-projeto>
    ```

4. Dentro da pasta, no terminal:

    ```bash
    poetry shell
    ```

5. Instalando as dependências:

    ```bash
    poetry add pandas
    ```

No VSCode, para uso da extensão Jupyter, talvez seja preciso [uma configuração extra](https://stackoverflow.com/questions/71229335/vscode-doesnt-show-poetry-virtualenvs), adicionando o caminho onde ficam os ambientes virtuais para serem exibidos no Kernel, se esse não for exibido de forma automática:

```json
{
    "python.venvPath": "C:\\Users\\nome-do-usuario\\AppData\\Local\\pypoetry\\Cache\\virtualenvs\\"
}
```

Para sair do ambiente virtual

    ```bash
    exit
    ```


# Outras Informações
URI API
```python
url = "https://dadosabertos.camara.leg.br/api/v2/deputados"
```