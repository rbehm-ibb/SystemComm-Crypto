# Open Points
The document "Built-in Board Interface" gives a comprehensive overview of the interface.
There are a few open points:

  * All command are  given, but no timing (clk freq)
  * What reaction times form commands are required?
  * The doc list mostly SPI, but there is also Rx/Tx UART(KVL). Purpose?
  * What is McBSP with signals BCLK and /BFS ?
  * The documented commands allow firmware upload. Does this require  that we use the same controller?

  * I like to tap into the SPI (and possible others). For that we need some IF board to be able to do that. Otherwise there is no chance to reliably contact several pins.
  * We could use (if available) a controller with built-in crypto-hardware. This would make things easier and we would have a proven implementation.
  * 


