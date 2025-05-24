Fokus - Aplicativo de Timer Pomodoro

Fokus é um aplicativo elegante de timer Pomodoro desenvolvido com React Native. Ele ajuda você a gerenciar seu tempo de forma eficaz usando a técnica Pomodoro, alternando entre sessões de foco e pausas.

Funcionalidades

Três modos de timer:
Foco (25 minutos)
Pausa curta (5 minutos)
Pausa longa (15 minutos)
Controle de reprodução/pausa
Reinício automático ao trocar de modo
Design limpo e escuro com controles intuitivos
Interface responsiva para dispositivos móveis

Instalação

Clone este repositório:
bash
git clone https://github.com/seu-usuario/fokus.git  
Acesse a pasta do projeto:
bash
cd fokus  
Instale as dependências:
bash
npm install  
Inicie o servidor de desenvolvimento:
bash
expo start  
Como Usar

Selecione o modo desejado (Foco, Pausa Curta ou Pausa Longa).
Pressione "Começar" para iniciar o timer.
Pressione "Pausar" para pausar o timer.
Troque entre os modos quando quiser — o timer será reiniciado automaticamente.

Estrutura do Projeto

fokus/  
├── app/                      # Pasta principal do app  
│   ├── components/           # Componentes reutilizáveis  
│   │   ├── ActionButton/     # Botões de seleção de modo  
│   │   ├── FokusButton/      # Botão principal de ação  
│   │   ├── Timer/            # Componente do timer  
│   │   └── Icons/            # Ícones de play/pause  
│   ├── assets/               # Arquivos estáticos (imagens, etc.)  
│   └── index.jsx             # Tela principal do app  
├── ios/                      # Código nativo para iOS  
└── android/                  # Código nativo para Android  

Tecnologias Utilizadas

React Native
Expo
JavaScript/JSX
React Native SVG

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias ou correções.

Licença

Criado por Ialmo — Um projeto para fins de estudo em React Native. 


![image](https://github.com/user-attachments/assets/0b247b3f-6807-46e5-a56f-9f28c920956f)
![image](https://github.com/user-attachments/assets/c6b47956-894e-4831-aa9b-9860dbfe9aa8)
<img width="1416" alt="image" src="https://github.com/user-attachments/assets/7c48195e-545a-46aa-bc3b-ca7da37904ee" />




# Welcome to your Expo app 

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
