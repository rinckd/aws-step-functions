# aws-step-functions


## Windows Powershell Commands
* don't forget the double pipe... 

`npm run sls -- -- create -t aws-nodejs`

## Generate Cloudformation Templates

`npm run sls -- -- deploy`

## Invoke

* powershell also needs quote escapes...

```
npm run sls -- -- invoke stepf --name simple-maths --data '{\"x\":\"42\", \"y\":\"13\"}'
npm run sls -- -- invoke stepf --name simple-maths --data '{\"x\":42, \"y\":13}'
npm run sls -- -- invoke stepf --name hello --data '\"foo\"'
```