# falha_winget

Descrição:

a) Ocorreu uma falha ao tentar fazer o upgrade dos programas do Windows 10 utilizando o WinGet.

> Sintaxe: winget upgrade --all

b) A falha é a seguinte (tela01):

> C:\Windows\system32>winget upgrade --all
> Falha na pesquisa da origem: msstore
> Ocorreu um erro inesperado ao executar o comando:
> 0x8a150044 : O ponto de extremidade da origem REST não foi encontrado.

c) #SOLUÇÃO# Na verdade é uma alternativa, eu completei a linha com "--include-unknown --source winget" (tela02).

> Sintaxe: winget upgrade --all --include-unknown --source winget
>
> Obs.: Você deve "executar como administrador" o prompt de comando.
