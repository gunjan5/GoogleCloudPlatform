basic Golang app to learn Google Cloud Platform

- download and install Google Go SDK
- write your go app
- write the config file `app.yml`
- `go get google.golang.org/appengine/cmd/aedeploy`
- `gcloud config set project yello-world-2016`
- `gcloud auth login` then login to your Gmail
- Deploy: `aedeploy gcloud preview app deploy app.yaml --set-default`
- Go to: `https://yello-world-2016.appspot.com/`
