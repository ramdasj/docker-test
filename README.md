Instructions on How To Test Docker image created from this Dockerfile

Install dgoss and goss to test the container. (Instructions for installing dgoss and goss: https://github.com/aelsabbahy/goss/tree/master/extras/dgoss)

After installing dgoss, get the goss.yaml in this repo (https://github.com/rsridivya/gannett_exercise/blob/master/goss.yaml) and run the following command in the same directory where goss.yaml exists.

dgoss run -p 8080:8080 rsridivya/gannett_exercise hello
This will test the container based on the tests cases given in goss.yaml
