

**install**

# migrate es5 to repo from `create-single-spa root-config`
```
create-single-spa --dir root --moduleType root-config 
yarn --cwd root start --port 9900 
create-single-spa --dir app --framework angular
```

```
# launch
cd ~/snappi.dev/singleSpaPlayground
yarn --cwd root start &
yarn --cwd navbar start &       
yarn --cwd shared start &       
yarn --cwd app serve:single-spa:app &  
yarn --cwd marais serve:single-spa:app &     
```



# --framework angular
```
1. Run 'npm run serve:single-spa:app'
2. Go to http://single-spa-playground.org/playground/instant-test?name=app&url=%2F%2Flocalhost%3A9010%2Fmain.js&framework=angular to see it working!
```