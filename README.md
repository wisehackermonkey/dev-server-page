# orans.dev landing page
### quick start
```
yarn
yarn start
```

# for production
```
yarn 
yarn build
HTTPS=true SSL_CRT_FILE='./.cert/cert.pem' SSL_KEY_FILE='./.cert/key.pem' PORT=443 serve -s build

sudo forever-service install server -f " --watchDirectory /opt/dev-server-page/ -w"
sudo service server status
sudo service server start
sudo service server status

```

# how to use the service
```bash
Commands to interact with service server
Start   - "sudo service server start"
Stop    - "sudo service server stop"
Status  - "sudo service server status"
Restart - "sudo service server restart"
```
 