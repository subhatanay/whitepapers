## Kafka 

A distributed messaging based log-aggregator.

### Key components :: 

1. topic :: A stream of messages of a particular type is defined by a topic.

2. brokers :: The  published  messages  are  then  stored  at  a  set  of  servers  called brokers.

3. producers :: A client/application which can publish messages to a topic.

4. consumers :: A client/application act as consumer which can subscribe to one or more topics from the brokers,  and  consume  the  subscribed  messages  by pulling  data from the brokers.

5. message :: data which serialized to popular encoding format (avro, json, protobuf) and converted bytes array which needs to transmitted to topic via a producer.

6. partition :: Kafka  is  distributed  in  nature,  an  Kafka  cluster  typically  consists  of  multiple  brokers.  To  balance  load,  a  topic  is  divided into multiple  partitions  and  each  broker  stores  one  or  more  of  those partitions. partition helps to balance the load accross the consumers.

## how topics stores in distributed kafka cluster .

### Storage

#### Physcial Storage 

#### Logical Storage

## How consumers get messages from kafka brokers? 

## Kafka's Caching logic 

## Data transfering logic over network

## How kafka brokers manage multiple consumers offset information.

## Consumer Groups

## How partition help to distribute data accross multiple consumers

## How consumers are consume data from different partition.

## Delivery Guanrantes

## Pros/Cons



