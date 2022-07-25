To pure RAKit add:

1. "yarn add gh-pages --dev"

2. add to scripts in package.json

    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"

3. "yarn deploy" to deploy