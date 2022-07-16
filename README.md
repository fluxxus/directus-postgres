# Directus with Postgres Database on Elestio

This is a minimal example of a Directus site with postgres database created using directus init

Click on the button below to deploy this repository with CI/CD on Elestio:

<a href="https://dash.elest.io/deploy?source=cicd&social=Github&url=https://github.com/elestio-examples/directus-postgres"><img src="deploy-on-elestio.png" alt="Deploy on Elest.io" width="180px" /></a>

<img src="screenshot.png" alt="screenshot of the Directus app" width="100%" />

# Steps to clone this repository and run locally.


### Step 1: Clone this repository

```
git clone YOUR_REPOSITORY_URL
```
### Step 2: Go to project folder

```
cd directus
```

### Step 3: Install dependencies

```
npm install
```

Rename `.env.sample` to `.env`.

### Step 4: Run your app in dev mode

```
npx directus start
```

### Step 5: Make some changes and push
Try to make some change in your Directus project then push to the git repository

After few seconds to few minutes your change will be deployed on your CI/CD target 🚀
