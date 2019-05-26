# BlazorObjectDumper
A simple component that allows you to bind to an instance of a class and press a button to view its data as JSON.  Useful when debugging.

This component allows the easy visualisation of the values currently held in an object and its child objects.  Add this component to a page and pass in a 
param for the object to monitor, then press the button to see the object's data as nicely formatted JSON.

Simply add the component to your page like this:  
```
<ObjectDumper ObjectToDump="@YourObjectToVisualise" />
```
