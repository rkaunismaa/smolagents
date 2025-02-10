# smolagents

This will be my playground for the smolagents library from huggingface.

## Thursday, February 6, 2025

 1) python3 -m venv .smolagents
 2) source .smolagents/bin/activate
 3) pip install smolagents
 4) pip install jupyterlab
 5) pip install ipywidgets

 Wow. Ran the code in Quick_Demo.ipynb and it just works! 

 6) pip install 'smolagents[litellm]'
 7) pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
 8) pip install 'smolagents[transformers]'

 ## Monday, February 10, 2025

  9) pip install selenium helium pillow

  Ugh. Because I want to use Selenium and Helium, I need to download the ChromeDriver. 

  Current version of Brave on KAUWITB is Version 1.74.51 Chromium: 132.0.6834.160 (Official Build) (64-bit), so I need to download the ChromeDriver version 132.

  [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/)

  Remember once it is downloaded, you need to unzip it and COPY the chromedriver to /usr/bin

   1) sudo cp chromedriver /usr/bin/chromedriver
   2) sudo chown root:root /usr/bin/chromedriver
   3) sudo chmod +x /usr/bin/chromedriver

'The chromedriver version (133.0.6943.53) detected in PATH at /usr/bin/chromedriver might not be compatible with the detected chrome version (132.1.74.51); currently, chromedriver 132.0.6834.159 is recommended for chrome 132.*, so it is advised to delete the driver in PATH and retry'

OK. I downloaded 133.0.6943.53 of the Chromedriver and it is incompatible with the current version of Brave. I will try 132.0.6834.160.

OK Nice! I was able to get the chromedriver to work with Brave. I was able to run the code in the Quick_Demo.ipynb file.

