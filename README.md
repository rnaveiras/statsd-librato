STATSD-GO
=========

Port of Etsy's statsd, written in Go.

This was forked from https://github.com/amir/gographite to provide
Ganglia submission support.

USAGE
-----

```
Usage of statsd-go:
  -address=":8125": UDP service address
  -flush-interval=10: Flush interval
  -ganglia="localhost": Ganglia gmond servers, comma separated
  -ganglia-port=8649: Ganglia gmond service port
  -ganglia-spoof-host="": Ganglia gmond spoof host string
  -graphite="localhost:2003": Graphite service address
  -percent-threshold=90: Threshold percent
```

