Ridicuously simple.

This is just a plugin for a jquery that slides to anchors...I 
just get tired of remaking it all the time, and this will probably be 
more bug free has time goes on...hehe.

USAGE:
-----

	$('A').anchorSlide({
		topOffset : -90
	});

The options are in the source...and could change. But at the time of writing there are two.

topOffset set the point to slide to as the top of the object plus that number...so if you have a
	box that's at 350px from the top, but you want 15px of the page before it, then set topOffset to -15
	
slideTime is just the argument to the jquery animate function.