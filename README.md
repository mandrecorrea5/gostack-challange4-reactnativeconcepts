# GoStack - Challange 4 - React Native Concepts

> Quarto e último desafio do primeiro módulo (Conceitos) do Go Stack. Nesse desafio, a ideia é implementar a função de like dos repositórios

O projeto mobile tem por finalidade implementar o like nos repositórios

## Screenshot

![Captura de Tela 2020-06-22 às 10 42 19](https://user-images.githubusercontent.com/40653742/85295459-55645200-b476-11ea-9b27-bcf0aeb0d149.png)

## Project struture

    android           diretório com arquivos gerados para a compilação Android
    ios               diretório com arquivos gerados para a compilação iOS
    src
    src/__tests__     diretório com arquivos de testes
    src/services      diretório contendo o arquivo com a configuração da api
    src/App.js        arquivo como código principal da aplicação
    index.js
    package.json
    
## Development Setup

Para rodar o projeto, os seguintes softwares precisam estar instalados

- __[npm](https://docs.brew.sh/Installation)__
- __[Homebrew](https://docs.brew.sh/Installation)__
- __[XCode - se for iOS](https://developer.apple.com/xcode/)__
- __[Android Studio - se for Android](https://developer.android.com/studio)__
- __[watchman](https://facebook.github.io/watchman/)__
- __[node](https://nodejs.org/en/)__
- __[react-native-cli](https://reactnative.dev)__

### Libs Used

#### Production use
    @testing-library/jest-native
    @types/jest
    axios
    axios-mock-adapter
    
#### Development use
    @babel/core
    @testing-library/react-native
    jest
    react-test-renderer
    
### Instalation

```yarn install``` para instalar as dependências
```pod update``` dentro do diretório ios
    
### Run project

```react-native run-android``` (Para Android)
```react-native run-ios``` (Para iOS)
    
### Run Tests

    yarn test
    
    
