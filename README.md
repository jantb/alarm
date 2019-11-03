# Alarm
## Deploying

```bash
 mvn clean package appengine:deploy -Dapp.deploy.projectId=home-12
```

To view your app, use command:
```
gcloud app browse
```
Or navigate to `https://alarm.sipp.io`.
