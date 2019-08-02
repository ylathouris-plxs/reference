# Heroku Reference

**Pre-boot**

Heroku's pre-boot feature enables us to deploy without downtime. To enable pre-boot, run the following command. 

```
heroku features:enable -a legalgateway-${env} preboot
```