For macOS Users, type this command in console and run the main.py
env /usr/bin/arch -x86_64 /bin/zsh --login
#arch
#x86_64

To get back to arm64, use this:
env /usr/bin/arch -arm64 /bin/zsh --login
#arch
#arm64

navigate to project folder and create a venv
python -m venv venv

activate venv
source venv/bin/activate

install all the requirements
pip install -r requirements.txt

starting pipeline
python3 main.py