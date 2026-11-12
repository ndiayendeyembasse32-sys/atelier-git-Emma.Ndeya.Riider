# Emmanuelle Max

- Pseudo GitHub : emmanuellemax67-spec
- Ce que je connais déjà de Git : ...
- Ce que j'attends de cet atelier : ...

## Quiz

1. Juste après `git commit`, où se trouve mon commit ?
=Juste après `git commit`, mon commit se trouve dans mon dépôt Git local, c'est-à-dire dans mon Codespace. Il n'est pas encore envoyé sur GitHub.
2. Juste après `git push`, où se trouve-t-il ?
=Juste après `git push`, mon commit est envoyé sur GitHub, dans le dépôt distant. Les autres collaborateurs peuvent alors le récupérer avec `git pull`.
3. Que se passe-t-il si je supprime mon Codespace après un commit mais sans push ?
=Si je supprime mon Codespace après un commit mais sans avoir fait `git push`, je risque de perdre mon travail, car mon commit était uniquement enregistré localement et n'avait pas été envoyé sur GitHub.

## Stash

`git stash` met de côté les modifications en cours sans les commiter, ce qui laisse un dossier de travail propre.
On l'utilise quand une urgence arrive et qu'on doit changer de branche sans perdre son travail.
`git stash pop` ramène ensuite les modifications rangées.