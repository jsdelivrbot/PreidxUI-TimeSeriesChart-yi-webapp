# PreidxUI-TimeSeriesChart-yi-webapp
This is the Demo for using PreidxUI components escapially the TimeSeriesChart to express timeseries Data.<br>
1. You should install the required UI components you want using bower package management in your <web_abb_repository>.


```shell
bower install px-vis-timeseries --save```
2. Add `<script src="bower_components/webcomponentsjs/webcomponents.js"></script>` in your html head.
3. Add `<px-vis-timeseries options={}></<px-vis-timeseries>` in your html body.
4. The option contains the attributes of the TimeSeriesChart.    
- `chart-data` is the timeseries data you want to diaplay.
- `series-config` is the format of your curves.
- `event-data` is the time that you want to display when some important events happen.
- `event-config` is the configuration of the events including the logo and color.
- `x-axis-config` & `y-axis-config` are the configration for x and y axes.
