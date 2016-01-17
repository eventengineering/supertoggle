# SuperToggle
A simple Jquery UI toggle button

![Example Super Selector](/examples/example.jpg?raw=true")

SuperToggle Includes a number of useful features:

- Custom On/Off Values
- Custom On/Off HTML
- Defined set of CSS classes for object customisation
- Default Value

Setup
================================
Setting up SuperToggle could not be simpler.

Include the css and the library
```html
<script type="text/javascript" src="supertoggle.js"></script>
```

Create an button element to be the SuperToggle.
```html
<button id="example-toggle"></button>
```

Turn the element into a SuperToggle with some simple javascript
```js
$("#example-toggle").supertoggle();
```

###Live Demo

A live demo of SuperToggle in action can be found [here](http://htmlpreview.github.io/?https://github.com/eventengineering/supertoggle/blob/master/examples/examples.html).

###Examples
A selection of demo selctors can be found in the ***/examples/examples.html*** file.


Setup Options
================================
There are a few simple setup options for SuperToggle.

```js
$("#example-toggle").supertoggle({
	onVal: true,
	onContent: "On",
	offVal: false,
	offContent: "Off",
	defaultState: true,
});
```

#### onVal
This parameter stores the value you want the SuperToggle to show when it is in its ***on*** state. *(default:****true****)*

#### onContent
This parameter stores HTML content of the SuperToggle in its ***on*** state. This can be either text or full HTML. *(default:"On")*

#### offVal
This parameter stores the value you want the SuperToggle to show when it is in its ***off*** state. *(default:****false****)*

#### offContent
This parameter stores HTML content of the SuperToggle in its ***off*** state. This can be either text or full HTML. *(default:"Off")*

#### defaultState
This parameter sets the value you want the SuperToggle to have when it is first created. *(default:****true****)*

CSS Clases
================================
SuperToggle elements are assigned a range of CSS classes to make it easier for you to manipulate the look, feel and function of the toggle.

Class | Element Description
---|---
supertoggle | The button element that is the SuperToggle.
on | Assigned to the toggle in its ***on*** state
off | Assigned to the toggle in its ***off*** state

