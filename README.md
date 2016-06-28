#ipv4ToLocation
##develop environment
 
    python3.5.1
    python2.7.11

##Install

    pip3 install ipv4ToLocation.py

##Usage
Code:

```python
import ipv4ToLocation
print(ipv4ToLocation.findIP("192.168.199.1"))
print(ipv4ToLocation.findIP("114.114.114.114"))
```

Output:

    {'area': '对方和您在同一内部网', 'country': '局域网'}
    {'area': '信风网络科技有限公司公众DNS服务器', 'country': '江苏省南京市'}