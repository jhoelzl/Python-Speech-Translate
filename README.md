# Python-Speech-Translate

-You will need to setup a subscription with Microsoft Translator. [Click Here] (https://www.microsoft.com/en-us/translator/default.aspx) to get started.

-Speech API documentation can be [found here.] (https://docs.microsofttranslator.com/)

## Setup
Samples are written for Python 2 and assume that `pip` is installed. Recent versions of Python 2.7 come with `pip`.

The [`requests`](http://docs.python-requests.org/en/master/) and ['websocket-client'](https://pypi.python.org/pypi/websocket-client) packages are required:

pip install requests
pip install websocket-client

## Getting list of supported languages (languages.py)
This sample demonstrates how to obtain the list of languages supported by the speech translation API.

python languages.py

## Speech Translate (speech.py)
This sample demonstrates the use of Microsoft Translator Speech Translation API by translating an audio file

Fill your Azure Data Market Credentials

client_id = 'INSERT YOUR CLIENT ID'

client_secret = 'INSERT YOUR CLIENT SECRET'

Fill in the name of your audio file (PCM 16bit 16kHz mono WAV)

audio_file = 'INSERT AUDIO FILE FULL PATH'

python speech.py

## Getting Azure Data Market Token (adm.py)
This class illustrates how to get an Azure Data Market token given a Client Id and Client Secret

