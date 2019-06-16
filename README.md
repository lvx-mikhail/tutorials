# tutorials
SCP App Model https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5ec8c983a0bf43b4a13186fcf59015fc.html

Docker
create container: docker run -t -i debian /bin/bash
update available packages to install: apt-get update
install curl: apt-get install curl
install nvm: curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
install node v8: nvm instal
node --version
npm --version
npm search @sap/cds
npm config ls -l | grep ^regi
npm search cds --registry https://npm.sap.com
npm view @sap/cds --registry https://npm.sap.com
npm list -g --depth=0
npm install -g @sap/cds --registry https://npm.sap.com --verbose | more
npm set @sap:registry=https://npm.sap.com
npm config list
npm i -g @sap/cds
npm list -g --depth=0
exit
docker ps -a
docker rm a9053149c986
npm list -g --depth=0

VC
code .

npm install //install all from package.json

CDS
cds srv/cat-service.cds
cds srv/cat-service.cds --to sql

cds deploy --to sqlite:db/my-bookshop.db
cds deploy
cds run

cds repl
cd r
const cds = require('@sap/cds').connect()
cds
cds.ql - query language
cds.ql.SELECT

cds.run(SELECT.from(cds.entities.Books))

npm run

SCP dev https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/00823f91779d4d42aa29a498e0535cdf.html

CPI https://flpnwc-b17dd9c60.dispatcher.us1.hana.ondemand.com/sites/CloudPlatform-onboarding#Integration_Services-Display

Best Practices for Enterprise APIs https://www.sap.com/documents/2017/12/ba1141bf-e37c-0010-82c7-eda71af511fa.html

DJ https://blogs.sap.com/2019/01/16/hands-on-sap-dev-with-qmacro-new-live-stream-series/

Book-shop https://developers.sap.com/tutorials/cp-apm-nodejs-create-service.html

API Guidelines https://www.sap.com/documents/2017/12/ba1141bf-e37c-0010-82c7-eda71af511fa.html
