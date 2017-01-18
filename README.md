# jQuery.numeric

jQuery numeric plugin.

## Configuration

Allows only valid characters to be entered into input boxes.

```
Note: fixes value when pasting via Ctrl+V, but not when using the mouse to paste side-effect: 
    Ctrl+A does not work, though you can still use the mouse to select (or double-click to select all)
```
 
### Example

``` javascript
 $('.numeric').numeric();
 $('.numeric').numeric(','); // use , as separator
 $('.numeric').numeric({ decimal : ',' }); // use , as separator
 $('.numeric').numeric({ negative : false }); // do not allow negative values
 $('.numeric').numeric({ decimalPlaces : 2 }); // only allow 2 decimal places
 $('.numeric').numeric(null, callback); // use default values, pass on the 'callback' function
```