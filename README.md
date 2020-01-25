# receiptnotice

#### Software Principle

-Install an app on the phone, and then this service listens to the notifications received by the phone. If it receives a notification of receipt, it pushes the information to the specified URL.

#### How to use this software

-Add the software to the system whitelist after installation, each Android method is different

-Open the software to automatically jump to the Get notification permission page, allowing the app to monitor notifications

-Return to the software homepage, fill in the url you want to accept the payment information notification. After receiving the payment notification, the software will use the post method to send json information.

-For detailed usage, refer to [wiki] (https://github.com/WeihuaGu/receiptnotice/wiki)

#### This works with server projects

| getreceipt-server |
|:-|
| [getreceipt-server] (https://github.com/WeihuaGu/getreceipt-server) |

##### Donate
[![](https://img.shields.io/badge/%E6%8D%90%E5%8A%A9-%E6%94%AF%E4%BB%98%E5%AE%9D%7C%E5%BE%AE%E4%BF%A1%7C%E4%BA%91%E9%97%AA%E4%BB%98%7CPayPal-green.svg)](https://weihuagu.github.io/donate)


##### Reference project
| ||
|-|-|
| This software is modified from NLservice | [NLservice] (https://github.com/WHD597312/NLservice) |
| Real-time logcat | [Lynx] (https://github.com/pedrovgs/Lynx) |

##### Open source license
This project uses the standard Apache 2.0 license

##### [Chinese README](https://github.com/WeihuaGu/receiptnotice/blob/master/README-zh.md)
