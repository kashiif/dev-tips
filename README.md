# dev-tips

## MAC / Linux

### Install bundled gems to custom directory

There may be instances when you are not allowed to install gems globally. To fix this, you can install gems into a custom 
directory:

Include the following in your `~/.bashrc`

```
export BUNDLE_PATH=/home/your-user-name/.bundles
```

remember to reload `.bashrc` by `source ~/.bashrc`
