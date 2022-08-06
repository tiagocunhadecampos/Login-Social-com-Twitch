<div align="center">
  <h1>Stream Data - Login social com a Twitch</h1>
  
  ![image](https://user-images.githubusercontent.com/71537090/180063261-1eeb09cd-c744-4396-be14-f0f83a71db6d.png)

</div>

## ⚙️ Como executar

Antes de começar a executar o projeto no seu computador é necessário preparar o ambiente para que possamos usar a implementação de login social.
Abaixo estou disponibilizando um link de um material feito pela Rocketseat para preparação desse ambiente.

-> [🗺️ Preparando o ambiente](https://efficient-sloth-d85.notion.site/Preparando-ambiente-3ca815f6798f45b1a92f76a41d59c7bb)

Com o ambiente preparado é necessário abrir o Console da Twitch Developers e copiar o seu *ID do cliente* para adicionar nas variáveis de ambiente.
Logo abra o projeto usando o VSCode e siga os passos:
- Duplique o arquivo *.env.example*;
- Renomeie o arquivo duplicado para *.env*;
- No arquivo *.env* cole o ID do Cliente no valor da chave *CLIENT_ID*.

Feito isso já finalizamos o passo de adicionar nosso CLIENT ID nas variáveis de ambiente.

Agora podemos prosseguir para execução do projeto:

```sh
# Instale as dependências
$ npm install

# Execute a aplicação
$ expo start
```

Se você estiver usando um emulador basta clicar na letra `a` que o expo irá executar em seu emulador, mas se tiver utilizando o próprio smartphone utilze o aplicativo
do Expo, o Expo Go, para escanear o QRCode gerado no seu terminal.

## 🔨 Aprendizado

- [x] Expo Bare Workflow
- [x] Styled components
- [x] Typescript
- [x] React Navigation
- [x] OAuth -> Usado para login social com a Twitch
- [x] ContextAPI -> Construção dos nossos próprios hooks para dispor de estados globais para nossa aplicação

## 📖 Prototipo

Você pode encontrar o Design dessa aplicação no link abaixo:

- [Figma](https://www.figma.com/file/tzsZqOOwLj0hfcDreiiuaS/stream.data?node-id=1%3A206)


## ☕ Contatos

Você vai me encontrar em qualquer uma das redes sociais abaixo:

<a href = "mailto: tiagocdev@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23EA4335?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" margin-right="10px"></a>
<a href="https://www.linkedin.com/in/tiagocunhadecampos/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
