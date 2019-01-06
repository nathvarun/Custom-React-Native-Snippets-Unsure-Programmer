# Custom React Native Snippets

This repository contains few of the snippets that i use in my react native videos on my youtube channel.

## Setup Instructions (VSCODE)

- Open Visual Studio Code

- CODE > PREFERENCES > USER SNIPPETS > **javascriptreact.json/jsx-attr.json/jsx.json**

- Copy the code from this repository into that file.

## Issues :

- In case your javascriptreact.json snippets don't work, try and copy it into :

- CODE > PREFERENCES > USER SNIPPETS > **javascript.json**

## javascript.json/javascriptreact.json Snippets

```sh
imrnc  - Import React Native Component
imrnfc - Import React Native Functional Component
imrnp -  Create Panresponder.create
imrnss - Create React Native Style Sheet
clog   - console.log("$1")
rnmap  - React Native Map Method
rndime - const {width,height} = Dimensions.get('window')
rncomp - Create a React Native Component
rnfcomp  - Create a Functional React Native Component
```

## jsx-attr.json -> JSX Attribute Snippets

```sh
rnajc - alignItems:'center',justifyContent:'center'
```

## jsx.json -> JSX Snippets

```sh
<but - <Button title='${1:title}' onPress={()=>${2:alert('button pressed')}}/>
```
