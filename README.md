# XCOM-Mod-Manager
XCOM Mod Manager allows you to have multiple Mods of XCOM without them interfering. For example, you can have a Long War 1.0 mod, a Long War B14 mod and a vanilla installation, and XCOM Mod Manager will help you to simply switch between the three installations.

## Installation
XCOM Mod Manager needs no setup. Your download should include a file called `xcomModManager.py`. Put this file inside `XEW`.

To use XCOM Mod Manager, you'll need Python 2.7, which is available on all platforms be it Mac, PC or Linux.

## Usage
First off, you need to make multiple copies of the `XEW` folder inside your XCOM Enemy Within install folder. To do this, go to the folder where the game is installed (this can be done through Steam). The number of copies is up to you, depending on the number of seperate 'mods' you want to keep. Rename each copy something like, `XEW - Long War` or `XEW - Vanilla`. You can leave a single folder named as `XEW` (this is your default installation).

Once you're done with that, you're all set. Run the script included (`xcomModManager.py`), and it'll sort through the folders, and scan them. It might ask you for a name for the default folder (the one named `XEW`).

Once the script is done scanning the folders, whenever you want to change the installation you want to play, just fire up the script again and it'll give you a list of your mods. Type in the number of the mod you want to play, and press enter. The script will exit. When you launch the game through Steam, the version you selected will be the one you launch.
