# Sites estáticos com MkDocs

Você já criou sites? Caso ainda não tenha feito isso, saiba que você pode fazer isso de maneira prática e rápida, 
sem ter o mínimo de conhecimento de linguagem de marcação de hipertextos (HTML), folha de estilos (CSS) 
ou uma linguagem de programação voltada para Web (Javascript, Typescript).
Vamos demonstrar como fazer isso usando a ferramenta MkDocs.

Neste tutorial, vamos criar e publicar sites estáticos.

## Material necessário

- Sistema operacional Windows com usuário autenticado na loja da Microsoft (Microsoft Store)
- Sistema de controle de versão distribuído Git, disponível em: <https://git-scm.com/download/win>
- Editor de código VS Code, disponível em: <https://code.visualstudio.com/download>
- Linguagem de programação Python no PATH, disponível na loja da Microsoft ou no site: <https://www.python.org/>
- Uma conta no GitHub: <https://github.com/>
- Interpretador de comandos PowerShell habilitado com política de segurança irrestrita

## Roteiro

1. Instale:
   - Git
   - VS Code
   - Python
2. Execute o PowerShell como administrador e configure para irrestrita a política de execução dele. Execute:
   - `Set-ExecutionPolicy Unrestricted`
4. Abra o Explorador de Arquivos (Windows Explorer) e crie a pasta `meus-sites` no local de sua preferência
5. Abra a pasta `meus-sites` no VS Code
6. No VS Code, instale as extensões:
   - Python (da Microsoft)
   - vscode icons
   - Markdown Preview Enhanced
7. Abra um terminal e configure um ambiente virtual do Python para instalação futura do MkDocs e de seus temas, plugins e extensões
8. Encerre o terminal aberto (Execute: `exit`) 
9. Abra a paleta de comandos do VS Code e selecione o interpretador do Python instalado no ambiente virtual
10. Abra um novo terminal do VS Code e observe se ele carregou o ambiente virtual criado no passo 7.
11. Instale o MkDocs (Execute: `pip3 install mkdocs`)
12. Instale o tema `mkdocs-material` (Execute: `pip3 install mkdocs-material`)
13. Instale as extensões pymdown para Python (Execute: `pymdown-extensions`)
14. Vá ao site do GitHub e crie um repositório público para guardar uma cópia de segurança (*backup*) de seu site
15. Retorne ao terminal do VS Code e clone o repositório do GitHub (Execute: `git clone {{URL}}`)
16. Entre na pasta do repositório recém-clonado (Execute: `cd {{nome-da-pasta}}`
17. Crie um site MkDocs dentro da pasta (Execute: `mkdocs new .`)
18. Edite o arquivo `mkdocs.yml` para personalizar o site em questão
19. Crie arquivos Markdown no diretório `docs` (Arquivos com extensão `.md`)



