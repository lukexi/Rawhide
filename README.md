```
=~=~=~=~=~=~=~=~=~=~=~=~=~
Stack-IDE for Sublime Text
=~=~=~=~=~=~=~=~=~=~=~=~=~
```


![SublimeStackIDE Errors](http://lukexi.github.io/RawhideErrors.png)
![SublimeStackIDE Autocomplete](http://lukexi.github.io/RawhideAutocomplete.png)
![SublimeStackIDE Type-at-cursor](http://lukexi.github.io/RawhideTypeAtCursor.png)




An Sublime Text IDE for Haskell based on

https://github.com/fpco/ide-backend

via

https://github.com/chrisdone/ide-backend-client

Clone to
`~/Library/Application Support/Sublime Text 3/Packages/SublimeStackIDE`

Bleeding edge notes:
Currently depends on some patches in https://github.com/lukexi/ide-backend-client,
which in turn depends on the newest https://github.com/fpco/ide-backend.
Clone them both, and then run (assuming you're in directory you cloned them both into):
```
stack install ../../Code/ide-backend/ide-backend-rts
stack install ../../Code/ide-backend/ide-backend-common
stack install ../../Code/ide-backend/ide-backend-server
stack install ../../Code/ide-backend/ide-backend
stack install ../../Code/stack-ide/stack-ide-api
stack install ../../Code/stack-ide/stack-ide
```
SublimeStackIDE currently expects you to open a folder in sublime with a .cabal file in it.
Stack support is underway.
