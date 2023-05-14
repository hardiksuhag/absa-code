Installation Instructions:

Setup a venv:
$python3 -m venv ./venv


Install Dependencies:
$python3 -m pip install -r requirements.txt


Install 'CRF++-0.58' using the '.tar.gz' file present in /tools/:
(look online for installation instructions)
Roughly they are:

$cd tools
$tar xvfz CRF++-0.58.tar.gz -C ./
$cd CRF++-0.58
$./configure
$make
$sudo make install

Check using the following command:
$crf_learn -v
# absa-code
