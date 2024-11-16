# Intro
The Jupyter notebook in this folder was designed to be opened in Google Colab, a free cloud-based Jupyter notebook environment.

The notebook contains a script that plays a gamebook randomly multiple times and collects statistics on the outcomes. The script was tested with a gamebook written in **Twine** with **Harlowe** format and exported to HTML!

# Instructions

1. Open notebook in Google Colab.
2. Run cells that install Selenium and Chrome WebDriver.
3. Upload your gamebook HTML file to Colab - to the main directory.
4. Adjust config:
    1. In a proper cell - change the name of the gamebook file.
    2. Change the number of iterations.
5. Run the script + analyze the results.


# How it works

The script searches to `tw-link` selectors in a HTML game and randomy selects one of them. It repeats this process for a specified number of iterations and collects statistics on the outcomes.

# Addons

Apart from the jupyter notebook itself, you will find here also a very simple game in a HTML format and Twee file that was used to create it. It's a good starting point to test the script and play with it.
