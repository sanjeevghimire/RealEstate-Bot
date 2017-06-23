# RealEstate-Bot
A ChatBot for real estate based on Swift and Watson services






## Steps to Execute

1. Create Credentials for Conversation services
2. Create Credentials for Text-To-Speech services
3. Create Credentials for Speech-To-Text services

4. update the credentials.swift file

```
public struct Credentials {
    
    public static let ConversationUsername = “<conversation username>"
    public static let ConversationPassword = “<conversation password>"
    public static let ConversationWorkspace = “<conversation workspace id>"
    public static let SpeechToTextUsername = “<speech to text username>”
    public static let SpeechToTextPassword = “<speech to text password>"
    public static let TextToSpeechUsername = “<text to speech username>"
    public static let TextToSpeechPassword = “<text to speech password>"

}

```

5. Open the project in Xcode
6. Voila!


For more details see my blog [here](http://sanjeevghimire.com/create-home-search-chatbot-using-swift-watson-services/)
