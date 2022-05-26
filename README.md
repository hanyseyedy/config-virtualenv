### the config of virtualenv in linux - ubuntu:

install virtualenv:<br />
`sudo apt install virtualenv`<br />
`virtualenv -p python3 venv`

activate venv:<br />
`source venv/bin/activate`

install pip: <br />
`sudo apt install python3-pip`

pip list and freeze: <br />
`pip list`
`pip freeze`

make directory src: <br />
`mkdir src`

make requierments.txt file and write freeze list into that: <br />
`pip freeze > requierments.txt`

insert log of installed packages list into requierments.txt file: <br />
`pip install-r requierments.txt`

make main.py file: <br />
`touch main.py`
