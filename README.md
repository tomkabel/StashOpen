# Local Video Player opener

```bash
cd server
# install dependencies
npm i
# run server
node server.js
```

Works in conjunction with the `stash-open` [plugin](https://github.com/feederbox826/plugins/tree/main/plugins/stash-open)

## install
- Install the plugin on your stash server
- set the path replacement in settings on stash, in the format of oldpath,newpath. Multiple replaces can be specified
  `/mnt/porn,\\nas\secret\porn /mnt/videos,\\nas\videos`
- set the url used to access your stash instance itself
  `http://127.0.0.1:9999` or `http://my-nas.localhost:9999`
- make sure the node server is running on the same computer as your browser, otherwise there will be no way for them to communicate
- when the filename is clicked, the video file should be opened on the computer