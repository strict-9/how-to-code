# TrustNote 2.0 Mining Helper SDK for Python

### how to use

```
import miningHelper as helper

print ("pow:{0}".format(helper.get_pow()))
print ("trustme:{0}".format(helper.get_trustme()))
print ("coinbase:{0}".format(helper.get_coinbase()))

print ("TTT:{0} MN".format(float(helper.get_coinbase())/1000000))

print ("pow count:{0}".format(helper.get_pow_count()))
print ("trustme count:{0}".format(helper.get_trustme_count()))
print ("coinbase count :{0}".format(helper.get_coinbase_count()))

round_index = helper.get_round_index()
print ("round index:{0}".format(round_index))

unit_count = helper.get_unit_count()
print ("unit count:{0}".format(unit_count))

print ("am in trustme?:{0}".format(helper.is_round_in(round_index-1)))
```

### sample code

https://github.com/trustnote/how-to-code/blob/master/samples/miningDashboard/python/cli.py

