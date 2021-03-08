# crypto-business-cards
Project of hi-tech business cards on the Utopia P2P theme.

## Concept

create 3D printed business cards using Utopia uCode and displaying the account public key.

## RESULT

![photo 1](https://github.com/Sagleft/crypto-business-cards/raw/main/images/photo1.jpg)
![photo 2](https://github.com/Sagleft/crypto-business-cards/raw/main/images/photo2.jpg)

## How to start

First you need to [download the client](https://u.is/en/download.html).

Next, create an account.

Next, find the button with the settings icon in the upper right. After clicking on it, a window will open with your public key and uCode.

![screenshot 1](https://github.com/Sagleft/crypto-business-cards/raw/main/images/account_1.png)

Next, save the uCode image. Open the template.psd file in your graphics editor. If you don't have a graphics editor, you can use [photopea.com](https://www.photopea.com/)

![screenshot 2](https://github.com/Sagleft/crypto-business-cards/raw/main/images/account_2.png)

Replace uCode with your own, enter any desired text in the same color as in the template. These colors of templates are due to the technical features of the utility with which we will continue to work.

Save the image to the `tool` folder as JPEG image.

Make sure you have python2 installed on your system.

Go to the `tool` folder and run in the console:

```bash
python2 makestl.py image.jpg model.stl
```

where:
* `image.jpg` - your template image filename;
* `model.stl` - the name under which to save the model;

In a couple of seconds, your model will be ready. You can import it into any 3D editor or 3D print slicer. For example, you can use Chitubox if your printer supports SLA technology.

![model screenshot](https://github.com/Sagleft/crypto-business-cards/raw/main/images/model_screenshot.png)

Resize the model to 90x50x3 mm.

3D print! Enjoy!
