# server

- `npm i express cors mongodb dotenv`

# $ node

> require('crypto').randomBytes(64).toString('hex')

---

# Heroku

## One time for my computer

- create heroku account (set-your-app-name)
- verify email
- install heroku cli
- heroku login

## **For Each Project One Time**

- heroku create
- make sure you: git add . > git commit > git push
- git push heroku main
- Go to heroku Dashboard > Current Project > Settings > Reveal Config Vars
- copy paste config vars from <.env> file
- Make sure you have whitelisted all ip address to access mongoDB

## UPDATE SERVER with new changes

- Make changes
- make sure you: git add > git commit > git push
- git push heroku main
