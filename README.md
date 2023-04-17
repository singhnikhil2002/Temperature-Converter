# Temperature-Converter
Inside index.html we have inserted an Event Listeners onchange in input tag.
Inside script.js we have created the function used in onchange event.
We get the value using step event.target.value and store in a variable.
Then we use switch statement.
Inside this we decide with the case using event.target.value but with event.target.name
Then we change according to the case for celsius,fahrenhiet,kelvin.
When restrict the result upto 2 decimal value using .tofixed(2).
