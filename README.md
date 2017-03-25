
In India,still a large section of our society is deprived of the basic needs of daily life i.e food,clothes,money,books etc.So, through this project, we are building a platform where the donors can directly communicate with the NGOs working in this field to donate their food,money,clothes etc.As there is a large amount of food wastage in parties,mess etc,so they can easily contact the nearest working NGO through this and NGO will recieve it from them.<br>
similarly, our chatbot provide a platform for people who are willing to donate foods , money ,clothes, books can donate it to the needy people.


<br><u><b>WORKING</b></u><br>
When the chatbot receives a message it parses the user message, tags part of speech, finds synonyms and concepts ,and finds which rule matches the input. If the match is found, the chatbot uses the corresponding template to generate a response.<br>
In order to respond differently in different context we have used Machine Learning tools.Machine learning lets us train an intent classification algorithm and we just need a training set of few thousands of example and it will pick the pattern in the data. The intent classification module identifies the intent of user message. Typically it is selection of one out of a number of predefined intent of user message. Intent classification can use context information such as intent of previous messages, user profile, and preferences. Entity recognition module extracts structure bits of information from the message.
<br>
 The response generation does all the calculation to generate the user request . It calls different external APIs or even asks the live agent to help with response generation.. All these responses should be correct according to domain specific logic. The response generator uses the context of the conversation as well as intent and entities extracted from the last user messages, in order to support multi message conversation.
 <br>
 we have used api.ai tools for building our chatbots.<br>
 we have also used facebook developer tools and heroku for deploying our app.<br> 

