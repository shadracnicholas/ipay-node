```
const Ipay = require('ipayafrica');
const ipay = new Ipay.IpayAfrica({vendor_id:'demo',hash_key:'demo',live:false});
const request={
    order_id:'123456',
    invoice_id:'123456',
    amount:10,
    telephone:'0700000000',
    email:'example@gmail.com',
    currency:'KES',
    param1:'',
    param2:'',
    param3:'',
    param4:''
    };

ipay.Rest(request,function(err,res){

});

```
