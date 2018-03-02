# webapp-boilerplate-reducer
Boilerplate code WebApp including reducer
## Setup
* `git clone https://github.com/sitevision/webapp-boilerplate-reducer.git`
* `cd webapp-boilerplate-reducer`
* `npm install`
* `npm run setup`
## Building
* `npm run zip` compress `/src` into `/dist`
* `npm run deploy` compress `/src` into `/dist` and upload to the addon configured in the setup task
* `npm run force-deploy` compress `/src` into `/dist` and upload to the addon configured in the setup task. This will overwrite the current webapp if it has the same webapp-version defined in manifest.json.