- 👋 Hi, I’m @sakshammishra2
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sakshammishra2/sakshammishra2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->#-------------------------------------------------------------------------------
# Name:        module2
# Purpose:
#
# Author:      admin
#
# Created:     25-07-2023
# Copyright:   (c) admin 2023
# Licence:     <your licence>
#-------------------------------------------------------------------------------
def english_to_spanish_translator(word):
    # Dictionary containing English to Spanish translations
    translations = {
     'hello': 'hola',
     'world': 'mundo',
     'good': 'bueno',
     'morning': 'mañana',
     'hola'   :'hello',
     'mundo':'world',
     'bueno':'good',
     'mañana':'mornig',
     'Me llamo ':    'My name is' ,
     'Mi Nombre es'    :'My name is' ,
     'Hola, soy Markus':'     Hi, I’m Markus',
     '¿Cómo te llamas? ':'    What is your name?',
     '¿Cómo está usted?':    'How are you? (formal)',
     '¿Cómo estás?     ':'How are you? (informal)',
     '¿Qué tal?     ':'How are you? (informal) / What’s up?',
      '¿Cómo te va?     ':'How’s it going?',
     '¿Qué haces?     ':'What are you doing?',
     '¿Qué pasa?    ':'What’s happening?',
     'Bien, gracias     ':'Good, thank you',
     'Muy bien    ':'Very well',
     'Así, así     ':'So, so',
     'Como siempre    ':'As always',
     '¿Y tú?':'And you?',
     '¡Gracias!':'     Thank you!',
     '¡Muchas gracias!':'     Thank you very much!',
     '¡De nada!     ':'You’re welcome! / No problem!',
      'Por favor    ':'Please',
     '¡Perdon!     ':'Excuse me!',
     '¡Disculpe!    ':'Excuse me!',
     '¡Lo siento!     ':'Sorry! ',
     '¿Qué…?     ':'What?',
     '¿Quién…?     ':'Who?',
      '¿Cuándo…?     ':'When?',
     '¿Dónde…?    ':'¿Dónde…?',
     '¿Por qué…?    ':'Why?',
     '¿Cuál?     ':'Which?',
     '¿Cómo…?     ':'How?',
     '¿Qué hora tienes?':'     What time is it',
     '¿Cuánto cuesta eso':    'How much does it cost?',
     '¿Entiende?     ':'Do you understand?',
     '¡Puede repetirlo!':'    Can you say that again?',
     '¿Qué significa [word]?':'    What does [word] mean?',
     '¿Puedes hablar más despacio':'    Can you speak slowly?',
     '¿Dónde puedo encontrar un taxi?':'    Where can I find a taxi?',
     '¿Dónde está [hotel’s name] hotel?':'    Where is [hotel’s name] hotel?',
     'Sí     ':'Yes',
     'No    ':'No ',
     'Tal vez ':'    Maybe',
     'Claro    ':'Of course',



        # Add more translations here
    }

    # Convert the word to lowercase to handle case sensitivity
    word = word.lower()

    # Translate the word if it exists in the dictionary, otherwise return "Not Found"
    return translations.get(word, "Not Found")

# Example usage:
try:
    user_input = input("Enter an  spanish word to translate to English: ")
    translation = english_to_spanish_translator(user_input)
    print(f"Translation: {translation}")
except KeyboardInterrupt:
    print("\nTranslation process interrupted.")




