# Huawei Map Clustering
A high performance marker clustering library for Huawei Map

<img src="Screenshots/100k.gif" width="320" height="685">

https://medium.com/@heydjbaby/100k-clustered-markers-with-huawei-map-ffcba4168727

## Motivation
Why not use [Huawei built in .clusterable(true)](https://developer.huawei.com/consumer/en/doc/development/HMS-Guides/hms-map-drawonthemap#h2-1586915875534)? Because it's very slow for >100 markers, which causes ANRs. But this library can easily handle thousands of markers (the video above demonstrates the sample application with 100 000 markers running on Huawei P40 Lite).
