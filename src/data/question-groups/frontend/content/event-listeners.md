To add an event listener on an element, you have to first “get” that element through one of the many methods of the document object (i.e. getElementById, etc) and then use the addEventListener method of the obtained object.

The method will receive the event name (i.e. ‘click’, ‘keyup’, ‘mouseup’, etc), the event handler function and, optionally, a boolean indicating whether the event should be captured during the capturing phase.