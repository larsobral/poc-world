# Substituição Automatizada de Nomes de Universidade em Documentos

Este projeto é uma prova de conceito (POC) que demonstra como automatizar a substituição de nomes de universidade em documentos do Microsoft Word (.docx) utilizando a biblioteca `python-docx` em Python.

## Funcionalidade

A POC lê um documento do Microsoft Word (.docx) que contém marcadores de posição (`XXXXXXXXXXXXX`) e substitui esses marcadores pelo nome de uma universidade fornecida. O resultado é um novo documento em que todos os marcadores de posição foram substituídos pelo nome da universidade escolhida.

## Como Usar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-projeto.git
cd nome-do-projeto
```
Instale as dependências:
```bash
pip install -r requirements.txt
```
Coloque seus documentos .docx na pasta doc/.

Edite o arquivo main.py para adicionar os nomes das universidades que você deseja substituir.

Execute o código:
```bash
python src/main.py
```
Os documentos gerados serão salvos na pasta output/.