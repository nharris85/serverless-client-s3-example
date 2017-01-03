serverless-client-s3-example
============================
Example using serverless v1.4.0 with serverless-client-s3

Installation
------------
```bash
$ clone git@github.com:nharris85/serverless-client-s3-example.git
$ cd serverless-client-s3-example
$ npm install
```

Deploy
------
**Using stage and region defined in serverless.yml**
```bash
$ sls client deploy
```

**Using options to overwrite stage and region**
```bash
$ sls client deploy --stage production --region us-west-2
```
