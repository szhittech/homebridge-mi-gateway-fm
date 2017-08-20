# homebridge-mi-gateway-fm
[![npm version](https://badge.fury.io/js/homebridge-mi-gateway-fm.svg)](https://badge.fury.io/js/homebridge-mi-gateway-fm)

XiaoMi Gateway FM plugin for HomeBridge.
Thanks for [nfarina](https://github.com/nfarina)(the author of [homebridge](https://github.com/nfarina/homebridge)), [wfr](https://github.com/wfr)(the author of [mihome-binary-protocol](https://github.com/OpenMiHome/mihome-binary-protocol)), [aholstenson](https://github.com/aholstenson)(the author of [miio](https://github.com/aholstenson/miio)), all other developer and testers.   

## Installation
1. Install HomeBridge, please follow it's [README](https://github.com/nfarina/homebridge/blob/master/README.md).  
If you are using Raspberry Pi, please read [Running-HomeBridge-on-a-Raspberry-Pi](https://github.com/nfarina/homebridge/wiki/Running-HomeBridge-on-a-Raspberry-Pi).  
2. Make sure you can see HomeBridge in your iOS devices, if not, please go back to step 1.  
3. Install packages.   
```
npm install -g miio homebridge-mi-gateway-fm
```

## Configuration
```
    "accessories": [
        {
			"accessory": "MiGatewayFM",
			"name": "MiGatewayFM",
			"ip": "192.168.88.xx",
			"token": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
        }
     ]
```

	 
## Version Logs
### 0.0.1
1.Switch on/off XiaoMi Gateway FM.   