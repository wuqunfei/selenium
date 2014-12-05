# Selenium Test on App Cloud with Grid mode, Support Heroku and Openshift
------
> * 1.fix htmlunit cache clean problem, clean cache by new method
> * 2.Add params that can support deploy on Pass cloud like heroku, openshift node
> * 3.fix binding host function is not working bug
> * 4.fix http header redirect not working problem
> * 5.make arrange node form sort to random to improve performance

## How to Use it on App Cloud? 
------
> * Add localBindingHost and localBindingPort for redirect on App CLoud
> * Example: -host $OPENSHIFT_GEAR_DNS -port 80 -localBindingHost $OPENSHIFT_DIY_IP -localBindingPort $OPENSHIFT_DIY_PORT

