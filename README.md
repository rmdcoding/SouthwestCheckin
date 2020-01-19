# SW Checkin

![](http://www.southwest-heart.com/img/heart/heart_1.jpg)

This python script checks your flight reservation with Southwest and then checks you in at exactly 24 hours before your flight.  Queue up the script and it will `sleep` until the earliest possible check-in time.

## Requirements


This script should be ran on a host system that has Python3 installed.


### Host

* Python3 
* [pip](https://pypi.python.org/pypi/pip)


## Setup

### Host

#### Install Base Package Requirements

#### Assuming `pip` is Python3 version (pip3)
```bash
$ pip install -r requirements.txt
```



#### Usage

```bash
$ python ./checkin.py -c CONFIRMATION_NUMBER -fn FIRST_NAME -ln LAST_NAME
```

