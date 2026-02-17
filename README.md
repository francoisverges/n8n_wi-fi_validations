# n8n Wi-Fi Validations
n8n workflow to automate some Wi-Fi validations.

These n8n Wi-Fi validation workflows have been presented at WLPC Phoenix 2026.
Feel free to copy, modify and enhance them as you wish.

> ❗**Important note**: these are still work in progress. Especially for the AI workflow, do not trust EVERYTHING it tells you.  

## Requirements
1. Wi-Fi Explorer Pro must be used to perform the Wi-Fi scan
2. The Wi-Fi Explorer Pro profile located under the **wfe-profile** folder must be used to do the Wi-Fi scan
3. The results of the Wi-Fi scan must be exported as a csv file in Wi-Fi Explorer Pro using the **"File > Export All Networks..."** menu

## Import workflow in your n8n instance
1. In n8n, create a new workflow
2. Paste the JSON text from one of the files located under the **n8n-workflows** folder
3. The nodes should appear in your n8n instance ready for editing

### AI workflow
If you imported the ai-worflow, you will need to do the following in n8n to make it work on your end:
1. Add credentials to these services
    1.  Google Sheet
    2. Your favourit AI chat (I used Gemini on my end)
2. Adjust the AI Chat node to match your favourite AI chat tool
3. Create a new google sheet with the same content as this one: https://docs.google.com/spreadsheets/d/1DOz3Wi7lUrTJJw0FocM8NL1_sY_r7iS9iceSUOIu_P4/edit?usp=sharing
4. Adjust the Google Sheet node to use your credentials and retrieve data from the new sheet you have just created


Have fun and share what you are coming up with 🙂

François Vergès
