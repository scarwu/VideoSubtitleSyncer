# Video Subtitle Syncer

## Development

### Install Env Tools

~~~
sudo npm -g install gulp-cli yarn
~~~

### Install Packages

~~~
./setup.sh
~~~

### Generate Folder for Dev

web root path please set to ./src/boot

~~~
gulp # build development mode with live reload

# or

gulp prepare # build development mode
~~~

## Deploy Github Page

~~~
gulp release # build production mode
~~~
