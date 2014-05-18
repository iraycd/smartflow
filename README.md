# SmartFlow.JS #

> Forked from [FlowType](http://simplefocus.com/flowtype/) and with improved performance on screen resize. Stops the IE and WebFit to fire zillion times which happens when you resize on the other responsive font-resize engines.


## Example:

      $('body').smartflow({
       minimum   : 100,
       maximum   : 1200,
       minFont   : 6,
       maxFont   : 40,
       fontRatio : 30,
       lineRatio : 1.45
      }); 


      $('h1').smartflow({
       minFont   : 12,
       maxFont   : 60,
       fontRatio : 20
      }); 