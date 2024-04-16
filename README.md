# Custom GPT
This project aims to guide developers through the process of creating a custom GPT (Generative Pre-trained Transformer) model using Google AI API. By leveraging the power of Google's AI infrastructure, developers can build and deploy highly performant and scalable custom language models for various applications.


## Features
* Conversational Interface: Users can interact with ChatGPT through a text-based interface, engaging in conversations or asking questions.
* Real-time Responses: ChatGPT provides responses in real-time, creating a seamless conversational experience.
* Google AI Integration: Utilizes various Google AI APIs for tasks such as natural language processing, translation, sentiment analysis, etc.
* Customizable Experience: The application is highly customizable and can be extended to incorporate additional features or APIs.

## Installation
* __Step 1 -__ 
```bash 
npm i
```

* __Step 2 -__ add your api key to .env.local file ( create a new file if it doen't exists)   

* __Step 3 -__ 
```bash 
npm run dev
``` 

Obtain API credentials for the desired [Google AI APIs](https://ai.google.dev/). Ensure you have the necessary permissions and enable the required APIs.

Set up authentication by configuring the environment variables or authentication mechanisms as per the documentation of the Google AI APIs you're using.

Open your web browser and visit http://localhost:3000 to access the application.

## Usage
Once the application is running, users can interact with custom GPT by typing messages in the text input field and receiving responses in real-time. Additionally, they can leverage Google's AI capabilities by integrating various API endpoints into the application's functionality.

## Configuration
The application's configuration can be customized to adjust various parameters such as the ChatGPT model version, Google AI API credentials, or UI settings. Refer to the environment variables or configuration files for specific customization options.

## License
This project is licensed under the [MIT License](./LICENSE)



