# Gestor de Senhas

## Descrição
O **Gestor de Senhas** é uma aplicação simples e eficiente para gerenciar logins e senhas. Ele permite:
- Armazenar credenciais de login.
- Automatizar o preenchimento de campos de login e senha.
- Gerenciar (adicionar, editar e excluir) suas credenciais de forma fácil.

## Funcionalidades Principais
- **Gerenciamento de Contas**: Adicione, edite e exclua informações de login.
- **Automatização de Login**: Preencha automaticamente campos de login e senha com apenas um clique.
- **Interface Intuitiva**: Interface limpa e amigável para facilitar a navegação.
- **Personalização de Tema**: Alterne entre temas claro e escuro.

## Requisitos
- Python 3.8 ou superior
- Pacotes listados no arquivo `requirements.txt`

## Instalação

### 1. **Instalar o Python**
Certifique-se de ter o Python 3.8 ou superior instalado:
- **Windows**: Baixe o instalador em [python.org/downloads](https://www.python.org/downloads) e marque a opção **"Add Python to PATH"**.
- **Linux**: Use o gerenciador de pacotes (exemplo para Ubuntu: `sudo apt install python3 python3-pip`).
- **macOS**: Use o `brew` (`brew install python`) ou baixe no site oficial.

### 2. **Instalar as Dependências do Projeto**
No diretório do projeto:
```bash
pip install -r requirements.txt
```

### 3. **Criar o Executável (Opcional)**
Para criar o executável:
```bash
pyinstaller --onefile -w app.py
```
O executável será gerado na pasta `dist/`.

## Como Usar
1. Configure as coordenadas de preenchimento automático na aba "Configurações".
2. Adicione suas contas e senhas na aba "Configurações" clicando em "Adicionar".
3. Use a aba "Contas" para realizar logins automáticos.

## Contribuição
Contribuições são bem-vindas! Siga os passos abaixo para contribuir:
1. Faça um fork do projeto.
2. Crie uma nova branch para suas modificações.
3. Envie um Pull Request com as alterações.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
