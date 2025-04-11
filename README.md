# UMHackathon
Steps:
1)Get Google API key in Google Colab
  1.1)Click on 'Gemini API key' under 'Secret' 
  1.2)Click 'Import Key from Google AI Studio' and you will get the API key
  1.3)Save the API key as the name GOOGLE_API_KEY;
2)Get Ngrok API Key from https://ngrok.com/ . 
  2.1)After signing in,you will see an Authtoken on the dashboard.
  2.2)Then, you have to copy and save the token in Google Colab 
  2.3)Save the API key as the name NGROK_AUTH_TOKEN
![image](https://github.com/user-attachments/assets/3b7a067a-38e7-4c2a-865a-96134d9f0e0e)
3)Ctrl + F9 to run all 
4)You will see the message 'Flask app is live at NgrokTunnel:',copy the url behind it 
![image](https://github.com/user-attachments/assets/08a5bef0-ee80-4a8e-beaa-850aca3f7a82)\
5)Open the html file with Visual Studio Code,replace the url in line 22 with the copied url.
![image](https://github.com/user-attachments/assets/d97c43fc-6a98-47b5-8a8d-b2fedd9fb9f8)
6)Download Live Server extension in Visual Studio Code 
7)Right click the html file and click 'Open with Live Server'.
8)Now you can chat with the chatbot
