CreateLables by Dr. G. Troska (georg.troska@uni-dortmund.de)
Creates PDF-Lables which can be used for Mira SMD-Containers (Mäuseklos) or others. 
Scripts are written in bash, templates are formated in Latex. You will need dmx-barcode-libs, too.
Create your own labletitles-file (see example labletitles-example.txt) then run:


./createlables labletitles-example.txt

Tested under Debian-like linux and Mac-OS 10.

Install dependencies on Debian based systems (tested on Ubuntu 14.04 64bit):
sudo apt-get install texlive-latex-extra texlive-fonts-recommended7 sudo apt-get install dmtx-utils
