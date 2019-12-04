# rightinfo
rightinfo

#Copy prod files
cp -r dist/* ../fb.github.io/

#start server for https
./ngrok http 8080
