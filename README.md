# gogs.service
gogs service for systemd

### How to use?

```
git clone https://github.com/sersoong/gogs.service.git
cd gogs.service
```

**Edit the gogs.service file.Replace all \* with your setting value in the file.**

**And copy it to ``/lib/systemd/system/``.**

**Then Run**
```
#sudo systemctl start gogs
#sudo systemctl enable gogs
```
**Or Stop with**
```
#sudo systemctl stop gogs
```
