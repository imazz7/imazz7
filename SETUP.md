# Como colocar no perfil do GitHub

O README de perfil precisa estar em um repositório público com o mesmo nome
do seu usuário:

```text
https://github.com/imazz7/imazz7
```

## Opção pelo GitHub

1. Crie um repositório público chamado `imazz7`.
2. Marque a opção para adicionar um README, ou deixe-o vazio.
3. Copie o conteúdo de `README.md` para o README desse repositório.
4. Copie a pasta `.github` para a raiz do repositório.
5. Faça o commit e aguarde a workflow gerar a cobrinha.

## Opção pelo Git

Dentro desta pasta:

```powershell
git init
git branch -M main
git add README.md .github SETUP.md
git commit -m "docs: add GitHub profile README"
git remote add origin https://github.com/imazz7/imazz7.git
git push -u origin main
```

Troque a URL do remoto se o repositório tiver outro endereço.

## Observações

- A workflow gera os arquivos da animação na branch `output`.
- O README usa cartões hospedados por serviços externos.
- Ajuste os links dos projetos se os repositórios tiverem outros nomes.
