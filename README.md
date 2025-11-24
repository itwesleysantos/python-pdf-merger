# 🐍 Python: Mesclador de PDFs

## 💡 Descrição do Projeto

Este projeto em **Python** oferece uma solução simples e eficiente para **mesclar múltiplos arquivos PDF** em um único documento, sem depender de ferramentas online que podem ter limites de página ou exibir anúncios.

O script foi desenvolvido para ler todos os arquivos PDF em uma pasta específica e combiná-los sequencialmente, utilizando a biblioteca **PyPDF2**, gerando um único arquivo de saída chamado **"PDF Final.pdf"**.

## 💻 Tecnologias Utilizadas

* **Python 3**
* **PyPDF2**: Biblioteca para manipulação e leitura eficiente de arquivos PDF.
* **os**: Módulo para interagir com o sistema operacional (leitura de arquivos em pastas).

## ⚙️ Como Executar o Projeto

Para rodar este projeto na sua máquina, siga os passos abaixo:

### Pré-requisitos

1.  **Python 3** instalado.
2.  Ter instalado a biblioteca **PyPDF2**.

### 1. Estrutura de Arquivos

Certifique-se de que o arquivo Python (`main.py`) e a pasta que contém seus PDFs (`arquivos`) estejam na mesma raiz do projeto.

* Crie uma pasta chamada **`arquivos`**.
* Coloque **todos os arquivos PDF** que você deseja mesclar dentro desta pasta `arquivos`.

### 2. Instalação de Dependências

Abra o terminal na pasta raiz do projeto e instale a biblioteca **PyPDF2**:

```bash
pip install PyPDF2
```

### 3. Execução

Execute o script principal a partir do terminal:

```bash
python main.py
```

O programa irá ler os arquivos, mesclá-los na ordem em que são listados e gerar o arquivo `PDF Final.pdf` na pasta raiz do projeto.

## 🤝 Contato

Desenvolvido por: **Wesley Santos**

| Plataforma | Link |
| :--- | :--- |
| **LinkedIn** | https://www.linkedin.com/in/itwesleysantos/ |
| **GitHub** | https://github.com/itwesleysantos |
