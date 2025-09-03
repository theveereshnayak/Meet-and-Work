# Meet and work
# Installation
* 1 - clone repo https://github.com/theveereshnayak/Meet-and-Work
* 2 - Create an account on agora.io and create an app to generate an APP ID
* 3 - Update APP ID, Temp Token and Channel Name in room_rtc.js
```javascript
let APP_ID = "YOU-APP-ID"
```

## Contact Form Setup

This project uses [Web3Forms](https://web3forms.com/) to handle contact form submissions.

To use the contact form:

1. Go to [Web3Forms](https://web3forms.com/).
2. Register and add your email to get an **Access Key**.
3. In the `form` tag, update the `access_key` value with the key you received:

   ```html
   <form action="https://api.web3forms.com/submit" method="POST">
     <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
     <!-- Add your fields -->
   </form>
# To run
 Run the project by opening the index.html file located in the portfolio folder in your browser.



