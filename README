var win = Ti.UI.createWindow({
	backgroundColor : 'white'
});
var textfield = Ti.UI.createTextField({
	hintText : "Text"
});
win.add(textfield);
win.open();

var button = Ti.UI.createButton({
	title : "Hide",
	top : 10
});
button.addEventListener("click", function() {
	var keyboard = require('ti.keyboard');
	keyboard.hide();
});
win.add(button);
