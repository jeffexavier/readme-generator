# Gerador de README.md

### Descrição

O gerador de README.md é uma ferramenta criada para ajudar a comunidade a construir seus arquivos README de forma rápida e organizada. Ele oferece um processo passo a passo para gerar READMEs personalizados que fornecem informações essenciais sobre seus projetos.

### Requisitos

- Python (versão 3.8 ou superior)
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/jeffexavier/readme-generator.git
   ```

2. Acesse o diretório do projeto:

   ```bash
   cd readme-generator
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

### Configuração

#### Arquivo `.env`

Crie um arquivo `.env` na raiz do projeto e configure a seguinte variável de ambiente:

```
GEMINI_API_KEY="sua_chave_api_do_google"
```

Você pode obter sua chave API do Google seguindo a [documentação oficial](https://developers.google.com/search).

### Execução

Para gerar seu README.md, execute o seguinte comando:

```bash
python generate_readme.py
```

Você será solicitado a fornecer informações sobre seu projeto, como título, descrição, licença e muito mais. Após inserir todas as informações, o script gerará um arquivo README.md personalizado no diretório atual.

### Licença

Este projeto está licenciado sob os termos da [Licença MIT](https://opensource.org/licenses/MIT).