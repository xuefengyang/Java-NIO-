# Java NIO Tutorial

## Java NIO（New IO）是一个从Java 1.4开始旨在替代老式JavaIO（基于字节流，InputStream、OutputStream）的api，所以取名为：“新
## IO”，NIO提供了与标准IO不同的工作方式。主要的API如下：

#Java NIO: Channels and Buffers（通道与缓冲区）
##标准的IO API中主要是通过字节流和字符流工作，在NIO中你通过通道和缓冲区工作。数据总数从一个通道中读到缓冲区或者是从一个缓冲区中写入到通道中

#Java NIO: Non-blocking IO（非阻塞IO ）

##NIO允许你使用非阻塞的方式来操作IO。据一个例子，通过一个线程来从channel读取数据到buffer，当正在读取数据的时候线程不会阻塞住，它可以继续做其他的事情。一旦数据读取到缓冲区，线程可以继续处理它。同理写入数据到channel是一样的。

#Java NIO: Selectors（选择器）






