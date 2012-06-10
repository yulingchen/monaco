monaco
======

Monaco is web application framework build based on Backbonejs, that allows you to easly create web based applications.

Monaco can be used for applications that don't require interaction with the server to exchange data, but it really shines when it is used with Restfull JSON APIs.

Main Components
---------------

**Router** : Monaco's router is an engine that will link URLs to specific methos of your application. The methods linked with each url pattern can be located anywhere in your application, giving you more flexibility. You can also capture information from the url and pass to its linked method, as well as pass static infomation as additional paramenters. The router also allows you to name urls, so you can reference them in yor code, making your application more mantainable.

**Model** : A model in monaco is a dataset representation of your application. It can be used to fetch a list of items or an individual item.

**View**  : A view controls what appears on the application, in some applications it might be considered a 'page', but the view it is much more than just that, it also controls the interaction between the end user and your page through events.

**Widget** : A widget is the content that will be presented to the end user so he/she can interact with your application. Each view will be composed of one of many widgets. Widgets might be linked with data that comes from the model, so that everytime the model changes the widget will reflect the change automatically.

**Form** : A form is a special kind of Widget capable of serializing HTML form elements, perform input validation and convert it to a Model.

**Transition** : Trasition is a manager capable of transfering the focus from one view to the other. It gives you the flexibility to decide what to do with the origin and destination views. Also monaco ships with a special CSS file that you can use to enable effects in your transitions.


Internal Features
-----------------

**Local Caching** : Monaco provides you with a local caching engine that will speed up your application, giving your end-users a better experience. Local caching comes disabled by default, but can be easly enabled when bootstraping your application.

**Model-Widget Binding** : TODO

**Events** : TODO




