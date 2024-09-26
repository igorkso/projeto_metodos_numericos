# Projeto Métodos Numéricos <h3>

Este projeto trata-se da entrega para conclusão da disciplina de Métodos Numéricos do IFPB, ministrada pelo professor Paulo Ribeiro

O projeto consiste na utilização de métodos de filtragem colaborativa, similaridade de cossenos e fatoração de matriz (SVD) para geração de recomendações personalizadas de filmes. 

Para executar o projeto, faça download do `csv` disponível neste [link](https://drive.google.com/drive/folders/1bwOqbQljd90--HQ621JlKrMpBe1Hu_4l?usp=sharing) siga as instruções:

# Pré-requisitos:

- Python 3 (ou versões posteriores);
- Virtual Envrionment para instalação das bibliotecas.

1. Clone o repositório localmente:

```bash
git clone git@github.com:igorkso/projeto_metodos_numericos.git
```

2. Crie um ambiente virtual e instale as dependências:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r req.txt
```

3. Execute o jupyter notebook:

```
$ (venv) jupyter-notebook
```

4. Clique no arquivo `Projeto_recomendação.ipynb` e execute todas as células.

Dica: Você pode selecionar outros filmes alterando o conteúdo da variável `chosen_movie`
