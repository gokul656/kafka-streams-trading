# kafka-streams-trading
Trading logic POC with Kafka streams

Description:

`order-book` The order-book service generates mock BUY / SELL orders & save their transaction receipts in DB. <br/>
`matching-engine` This service has the trading logics to match orders. It consumes from orders.buy & orders.sell topics.

To run the services use,

``mvn spring-boot:run``
