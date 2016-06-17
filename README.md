
#Alter the Publisher application
- Copy /extension/gadget to {CARBON_HOME}/repository/deployment/server/jaggeryapps/publisher/extensions/assets/
- Copy the /img/gadget.png to {CARBON_HOME}/repository/deployment/server/jaggeryapps/publisher/themes/default/img
- Copy the /css/my-icons.css to {CARBON_HOME}/repository/deployment/server/jaggeryapps/publisher/themes/default/css
- Add the following line to the {CARBON_HOME}/repository/deployment/server/jaggeryapps/publisher/themes/default/pages/single-col-fluid.hbs:
```html
    <!-- Custom icons -->
    <link href="{{url "/themes/store/css/my-icons.css"}}" rel="stylesheet">
```

#Alter the Store application
- Copy /extension/gadget to {CARBON_HOME}/repository/depoyment/server/jaggeryapps/store/extensions/assets
- Copy /img/gadget.png to {CARBON_HOME}/repository/deployment/server/jaggeryapps/store/themes/store/img
- Copy /css/my-icons.css to {CARBON_HOME}/repository/deployment/server/jaggeryapps/store/themes/store/css
- Add the following line to the {CARBON_HOME}/repository/deployment/server/jaggeryapps/store/themes/store/pages/2-column-right.hbs:
```html
     <!-- Custom icons -->
    <link href="{{url "/themes/store/css/my-icons.css"}}" rel="stylesheet">
```
