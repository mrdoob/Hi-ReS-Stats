Hi-ReS! Stats
========

#### Performance Monitor ####

This class provides a simple info box that will help you monitor your code performance.
So far available for Actionscript and HaXe.

* **FPS** Frames per second, how many frames were rendered in 1 second. The higher the number the better.
* **MS** Milliseconds needed to render a frame. The lower the number the better.
* **MEM** Memory your code is using, if it increases per frame is VERY wrong.
* **MAX** Maximum memory the application reached.

### Screenshot ###

![hires_stats.png](http://github.com/mrdoob/Hi-ReS-Stats/raw/master/assets/hires_stats.png)

### Usage ###

	addChild( new Stats() );

### Controls ###

* **CLICK** Top-half / bottom-half part of the panel to increase/decrease the FPS of the application.

### Download ###

[Stats.as](http://github.com/mrdoob/Hi-ReS-Stats/raw/master/src/net/hires/debug/Stats.as)  
[Stats.hx](http://github.com/mrdoob/Hi-ReS-Stats/raw/master/src/net/hires/debug/Stats.hx) (Ported by [David Wilhelm](http://github.com/bigfish))
