# Introdução 
Seja bem vindo ao desenvolvimento do ProjetaDev!! É muito importante que estabeleçamos
algumas boas práticas e organização dentro do repositório, então por favor se atentem ao 
resto deste arquivo como um guia de conduta.

# Boas práticas

Existem algumas convenções e acordo a serem seguidos quando estamos trabalhando em equipe
no meio de programação que são chamadas de boas práticas, podemos ver mais detalhadamente sobre 
isso por este [artigo](https://www.devmedia.com.br/boas-praticas-de-programacao/21137).

## Fluxo de desenvolvimento

1. Crie um novo branch no seu repositório local.
2. Implemente suas mudanças
3. Faça um push do seu branch para o repositório remoto
4. Submeta um Pull Request na branch develop
5. Aguarde a revisão do mesmo por outros desenvolvedores da equipe.
6. Caso alguma mudança seja solicitada, implemente-a.
7. Seus colegas de equipe integrarão seu código quando ele estiver ok.

## Controle de versão

Faça commits no modelo semântico da [conventional commit](https://blog.geekhunter.com.br/o-que-e-commit-e-como-usar-commits-semanticos/#O_que_sao_Commits_Semanticos)

1. Mensagens de commit devem ser curtas e objetivas. Exemplos:
  "Fix bug at user controller"
  "Add sign in feature"
2. Commits devem possuir poucas mudanças, em geral. Ou seja: commite constantamente.

### Considerações sobre PR

Quando formos fazer um Pull Request, ou PR, aparecerá uma mensagem de tamplate para
orientar o que precisa estar certo na sua branch para que ela seja corretamente mergeada, vá "Ticando" os checkboxes concluídos. Exemplo:
- [ ] Verificar se a sua branch esta atualizada com a develop
- [x] Verificar se esta loggado no GitHub
