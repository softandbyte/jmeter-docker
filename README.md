# jmeter-docker

More details on using this docker image is [here](http://www.testautomationguru.com/jmeter-distributed-load-testing-using-docker/)


#To start the master

```
sudo docker run -dit --name master softandbyte/jmmaster /bin/bash
```

#To start slaves

```
sudo docker run -dit --name slave01 softandbyte/jmserver /bin/bash
sudo docker run -dit --name slave02 softandbyte/jmserver /bin/bash
sudo docker run -dit --name slave03 softandbyte/jmserver /bin/bash
```
