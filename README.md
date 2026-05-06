# Ciência de Dados

Repositório base do projeto da disciplina de Ciência de Dados da FACAPE.

Este projeto está no formato de esqueleto inicial e será usado para organizar a coleta, análise e visualização dos dados ao longo da disciplina.

O dataset utilizado neste projeto foi:

- https://www.kaggle.com/datasets/wajahat1064/healthcare-appointment-dataset

## Requisitos

- Python 3.14 ou superior
- `uv`

Se você ainda não tiver o `uv` instalado, consulte o site oficial:

- https://docs.astral.sh/uv/

## Instalação

1. Clone este repositório.
2. Entre na pasta do projeto.
3. Instale as dependências com `uv`:

```bash
uv sync
```

Aviso: depois do `uv sync`, certifique-se de usar o interpretador Python do ambiente virtual gerado por esse comando, e não o Python global do sistema.

Se ocorrer algum erro ao executar os notebooks, execute os comandos abaixo:

```bash
uv venv --seed
uv pip install pydantic
uv pip install jupyterlab
```

Depois, reinicie o VS Code e tente executar as células novamente.

Depois, execute o projeto ou os notebooks conforme a etapa da disciplina.

## Estrutura do projeto

- `data/`: base de dados utilizada nas análises
- `notebooks/`: notebooks de exploração e resultados
- `src/`: código-fonte do pipeline e das rotinas do projeto

## Observações

Este README será atualizado conforme o projeto evoluir ao longo da disciplina.
