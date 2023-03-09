# 📧 SumMail

SumMail is a Python script that summarizes your latest email using OpenAI's language model. With just a few clicks, SumMail distills the content of an email into a compact and easy-to-read format.

### 🚀 Quick Start
To get started, you'll need to:

- Clone this repository to your local machine.
- Install the required Python libraries using `pip install -r requirements.txt`.
- Set your email account credentials and OpenAI API key in a .env file.
- Run the `main.py` script.
- Once the script runs successfully, it will print the subject line of your latest email and a bulleted summary of its content.

### 📩 Email Setup
SumMail works with any email account that uses IMAP. To use SumMail, you'll need to set up the following environment variables:

```
IMAP_SERVER: the IMAP server address for your email provider.
IMAP_USERNAME: your email address.
IMAP_PASSWORD: your email password.
SENDER_EMAIL: the email address of the sender you want to summarize.
```

### 🔑 OpenAI API Setup
SumMail uses OpenAI's API to summarize your email content. To use SumMail, you'll need to set up an API key [here](https://platform.openai.com/account/api-keys)
 and add it to your `.env` file as `OPENAI_API_KEY`.


### 📝 License
This project is licensed under the [MIT License](./LICENSE) - see the LICENSE file for details.

### 🙏 Acknowledgments
- This script was inspired by the OpenAI API and the Python email library. 
- Special thanks to the developers who created these tools and made SumMail possible.

## Do you like this project?
<a href="https://www.buymeacoffee.com/cyphercut" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>
