# Solana Minting Bot

#### This is an easy bot to setup which uses ChromeDriver to open up a new chrome instance and mint the nft you are looking for quicker than a human. This bot does not guarantee you will get your NFT, this bot simply goes faster than humans to mint and automates everything since you do not have to click yourself

### Support

-   [x] Window
-   [x] Mac (Intel + m1)
-   [ ] Linux

-   [x] MagicEden.io
-   [x] MonkeLabs.io

---

-   Like I said this bot uses ChromeDriver so on mac there is a possiblity that you will have to allow the software to run in your privacy settings. Check mac folder for more info.

-   The chrome window will appear **WITHOUT** loading the images, this is to ensure the fastest loading.

---

## Tutorial

---

1. Clone the repository / Download zip file

    > `git clone https://github.com/SolanaNFTCollector/Solana-Minting-Bot.git`

    OR

    > [Download Zip File](https://github.com/SolanaNFTCollector/Solana-Minting-Bot/archive/refs/heads/main.zip)

---

1. Open command prompt

---

2. Install all python module

    > `pip install selenium requests`

---

3. Replace Phantom Passphrase and password in `config.json`

    > `launchpadLink` --> Launchpad link on magic eden

    > `seedPhrase` --> your phantom wallet passphrase (Careful do not share this key)

    > `password` --> A password for your wallet

---

4. Open CMD and go to directory

    > `cd /path/to/directory/magiceden-mint-bot/windows`

---

4. Run the python file

    windows : `python main.py`

    mac : `python3 main.py`