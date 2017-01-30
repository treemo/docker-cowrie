# Cowrie Docker image build

## setup example

```
mkdir -p /var/log/cowrie/tty
chown $USER -R /var/log/cowrie/

docker run -d --name cowrie -p 22:2222 -v /var/log/cowrie/:/home/cowrie/cowrie/log/ --restart=always treemo/cowrie
```
