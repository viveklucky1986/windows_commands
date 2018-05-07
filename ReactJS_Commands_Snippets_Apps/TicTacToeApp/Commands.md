### Goto App directory and Start Npm Server ###
```cmd
cd tic-tac-tow-game && npm start
```

### Delete "src" folder contents and Create blank CSS and JS files
```cmd
del /s /q src && md src && cd src && echo. 2> index.css && echo. 2> index.js
del /s /q src && echo. 2> src/index.css && echo. 2> src/index.js
```
#### Create the "index.js" by executing below script(MakeReactIndexjs.cmd) inside "src" folder ####
```cmd
@echo off
set NLM=^


set NL=^^^%NLM%%NLM%^%NLM%%NLM%
(
    echo import React from 'react';%NL%import ReactDOM from 'react-dom';%NL%import './index.css';
) > index.js
pause
```