# WhatsApp ChatBot => recent extended GPT


Create a Personalized Chatbot Using Your WhatsApp Conversations:

WhatsApp Users:

Exporting Chat: Navigate to a chat in your WhatsApp application. Access settings and select the option to export your chat.

Edit Script: Before running the provided script, customize the placeholders 'YOUR_NAME' and 'OTHER_NAME' in the clean_whatsapp_chats.py script to match names from your chat file.

Run Script: Execute the following command:

python clean_whatsapp_chats.py whatsapp_chat.txt

Jupyter Notebook Steps:

First, initiate the prepare_files.ipynb notebook.
Fun awaits! Engage with your personalized bot at the bottom of this notebook.
For WeChat Enthusiasts:

WeChat preserves your chat history in an SQLite database. To fetch this:

Backup with iTunes: Use iTunes to back up your iPhone, ensuring you deselect the 'encrypt backup' option.

Extract Database File: With the help of iTools, access your backup.

Run WeChat Script: Implement the following command:

python clean_wechat_chats.py YOUR_DATABASE_PATH 
