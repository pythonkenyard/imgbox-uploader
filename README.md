# imgbox-uploader
a python based multi-file uploader for imgbox

**Requirements:**
Selenium
Chromedriver
Chrome

##**Usage**
input link to screens as system argument
e.g.
python imgbox.py "c:/user/pictures/photo1.jpg" "c:/user/pictures/photo2.jpg"

##**Usage in other scripts**
Script returns BB code of url to where files are stored same as imgbox outputs
input **list** of files to the imgbox class

e.g.
from imgbox import imgbox

screens = ["c:/user/pictures/photo1.jpg", "c:/user/pictures/photo2.jpg", "c:/user/pictures/photo3.jpg"]

filestoupload = imgbox(screens)
filestoupload.post()

Note:
Files uploaded as:
Family Friendly 
350x350 thumbnail resized (keeys original dimensions) 
Comments disabled.
