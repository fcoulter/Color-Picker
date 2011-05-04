Color Picker
===========

Creates a simple color picker form field for mootools. It should work with versions 1.1, 1.2 and 1.3 (with compatibility) of mootools. It includes some basic validation to ensure that a valid color is entered.


![Screenshot](http://www.spiralscripts.co.uk/components/com_virtuemart/shop_image/product/Joomla_Color_Pic_4d4803c1d4a5f.jpg)

How to use
----------
The script requires a form field element, pass this to the color picker script along with the options, eg assuming your form field has the id cpicker:-

        window.addEvent('domready', function(){
		var colorInput = document.id('cpicker');
		
		var cpicker = new ColorPicker(colorInput,{cellWidth: 8, cellHeight: 12})
		});


