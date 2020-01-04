Original library https://github.com/dialogflow/dialogflow-fulfillment-nodejs

Changes:

- The Card support **MULTI buttons**

Example:

```
let card = new Card('card title');
card.setImage('https://developers.google.com/actions/images/badges/XPM_BADGING_GoogleAssistant_VER.png');
card.setText('This is the body text of a card.  You can even use line\nbreaks and emoji! 💁');
card.setButton1({text: 'This is a button', url: 'https://assistant.google.com/'});
card.setButton2({text: 'This is a button', url: 'https://assistant.google.com/'});
card.setButton3({text: 'This is a button', url: 'https://assistant.google.com/'});
   
const anotherCard = new Card({
	title: 'card title',
    text: 'card text',
    imageUrl: https://developers.google.com/actions/images/badges/XPM_BADGING_GoogleAssistant_VER.png,
       
    buttonText1: 'This is a button',
    buttonUrl1: 'https://assistant.google.com/',
    buttonText2: 'This is a button',,
    buttonUrl2: 'https://assistant.google.com/',
    buttonText3: 'This is a button',,
    buttonUrl3: 'https://assistant.google.com/',
});
```
    
