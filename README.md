## Dependencies
- cdk
- python
- aws-cli

## Setup
```
virtualenv .env && source .env/bin/activate && \
    python -m pip install -r requirements.aws.txt && \
    python -m pip install -r requirements.app.development.txt && \
    python -m pip install -r requirements.app.txt && \
```

## Deploy
```
AWS_ACCOUNT_ID=<UPDATE> AWS_DEFAULT_REGION=<UPDATE> npm run deploy
```
