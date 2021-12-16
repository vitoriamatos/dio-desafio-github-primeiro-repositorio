# TREINAMENTO DE GIT


## ⚙️ Sobre o git
 - Ferramenta de versionamento de código distribuido
 - Criado com o intuito de ajudar o desenvolvimento entre equipes
 - Possui sistema de hashing para detectar quais arquivos foram alterados, gerando chaves únicas a cada nova alteração
 

## Como usar 
- Utilizar o comando git init para inicializa um repositório
- Existem dois tipos de arquivos:
  - Untracked: Arquivos ainda desconhecidos pelo git
  - Tracked: Arquivos rastreados pelo git e  se subdividem em 3 estágios:
          <br>
          1. Unmodified
           <br>
          2. Modified 
           <br>
          3. Staged: conceito chave: arquivos que estão 
          se preparando para fazerem parte de outro
          tipo de agrupamento, ou seja, foram commitados. 
   - Arquivos transitam entre esses estados, conforme vão sendo executados os comandos de "add", "commit -m", "push" e "pull"
   
   ## Conflitos 
     - São problemas comuns em sistemas de versionamentos de codigo
     - Acontecem quando o arquivo possui edições diferentes na mesma linha
     - Conflitos de Merge: 
        - Tentar juntar as duas alterações na mesma linha
        - O git não decide  qual a certa, ele deixa pra que o programador decida qual mudança deve permanecer
          
