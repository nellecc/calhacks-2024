
<!-- NOT NEEDED install ngrok:
    curl -sSL https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
        | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
        && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" \
        | sudo tee /etc/apt/sources.list.d/ngrok.list \
        && sudo apt update \
        && sudo apt install ngrok

Add your ngrok token (find your command at https://dashboard.ngrok.com/get-started/setup/linux)
ngrok config add-authtoken YOUR_OWN_TOKEN_HERE -->

setup

linux:
    pip install fastapi
    pip install uvicorn
    sudo apt instal net-tools

    sudo npm install -g expo-cli


run this command on your machine inside the backend folder:
    uvicorn app:app --reload


To open the frontend, you need expo.
npm -v

Download the latest node.js and run npm install -g npm@latest



then: 
    npx expo start --tunnel
it will prompt you to install ngrok. click yes.

