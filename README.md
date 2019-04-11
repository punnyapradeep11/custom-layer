# custom-layer

create nodejs folder
run npm init
npm install the required modules under nodejs folder
u can include custom modules in nodejs folder (custom.js, data.json)

zip nodejs folder -> upload the folder by using aws console or using the following command

aws lambda publish-layer-version --layer-name "moment-layer" --description "NodeJS module of Moment JS library and custom" --license-info "MIT" --compatible-runtimes "nodejs8.10" --zip-file "fileb://C:/users/nodejs.zip"

--> this command will create/update the layer


