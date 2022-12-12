# Estudo sobre Git Flow
---
## 1. Lista de comando para usar o Git flow
- git flow init ou git flow init -f

1. Podemos codificar na develop e podeis criar a release para mescrar com a master, mas o melhor é criar feature e depois criar as releases.

## 2. Criar uma feature
- git flow feature start _nome_da_feature

## 3. Finalizar feature
- git flow feature finish _nome_da_feature

## 4. Criar release
- git flow release start _1.0.0 : a versão da release

## 5. Finalizar a release
- git flow release finish _versão_da_release

## Modificar url do projeto
- git remote set-url origin url_do_git
## Verificar url do projeto
- git remote -v

## Enviar unica tag
- git push origin <tag_name>

### configurar vscode global
- https://uw-madison-aci.github.io/git-novice/02-setup/

### link sobre Git flow
- https://www.youtube.com/watch?v=394mc6PV8t8

#### Correções de erro.
- https://salferrarello.com/git-warning-pulling-without-specifying-how-to-reconcile-divergent-branches-is-discouraged/
