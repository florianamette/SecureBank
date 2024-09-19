# SecureBank
[![Docker Automated](https://img.shields.io/docker/cloud/automated/ssrd/securebank.svg)](https://hub.docker.com/r/ssrd/securebank)
[![Docker Build status](https://img.shields.io/docker/cloud/build/ssrd/securebank.svg)](https://hub.docker.com/r/ssrd/securebank/builds)
[![License](https://img.shields.io/github/license/ssrdio/SecureBank)](https://github.com/ssrdio/SecureBank/blob/master/LICENSE)

[![](https://sonarcloud.io/api/project_badges/measure?project=ssrdio_SecureBank&branch=master&metric=vulnerabilities)](https://sonarcloud.io/dashboard/?id=ssrdio_SecureBank&branch=master) 
[![](https://sonarcloud.io/api/project_badges/measure?project=ssrdio_SecureBank&branch=master&metric=bugs)](https://sonarcloud.io/dashboard/?id=ssrdio_SecureBank&branch=master) 
[![](https://sonarcloud.io/api/project_badges/measure?project=ssrdio_SecureBank&branch=master&metric=code_smells)](https://sonarcloud.io/dashboard/?id=ssrdio_SecureBank&branch=master) 

SecureBank is a FinTech application which contains all OWASP TOP 10 security vulnerabilities along with some other security flaws found in real-world applications.

![alt text](https://raw.githubusercontent.com/ssrdio/SecureBank/master/preview.gif "SecureBankPreview")


# Infrastructure
On the image below you can review how the application is built from the infrastructure point of view.
![alt text](https://raw.githubusercontent.com/ssrdio/SecureBank/master/infra.png "Docker infrastructure")

## Docker with multiple containers

 Run `docker-compose up`

## Users:
```
admin@ssrd.io:admin
developer@ssrd.io:test
yoda@ssrd.io:test
tester@ssrd.io:test
```
## Ports 
- 80 on this port SecureBank is accessible 
- 1080 is maildev server for user registration
- 5000 is hidden API

