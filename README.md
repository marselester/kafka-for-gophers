# [Kafka for Gophers](https://go-talks.appspot.com/github.com/marselester/kafka-for-gophers/kafka.slide)

In order to write reliable Go programs that use Apache Kafka,
one should understand what basic Kafka concepts are.
If you've ever felt uneasy about what happens with your service
when a message is lost or written more than once, you should read
[Kafka: The Definitive Guide](https://www.confluent.io/resources/kafka-the-definitive-guide/).

When it comes to choose a Go library to work with Kafka,
the decision could be tough. I would recommend to check out https://github.com/segmentio/kafka-go.

[This presentation](https://go-talks.appspot.com/github.com/marselester/kafka-for-gophers/kafka.slide)
provides an overview of how to achieve reliable data delivery with Kafka in Go.

Run present to view the slides with notes:

```
$ git clone https://github.com/marselester/kafka-for-gophers.git
$ cd ./kafka-for-gophers/
$ go run golang.org/x/tools/cmd/present -notes
```
