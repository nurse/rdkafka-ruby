# 0.3.4
* Bump librdkafka to 0.11.3

# 0.3.3
* Fix bug that prevent display of `RdkafkaError` message

# 0.3.2
* `add_topic` now supports using a partition count
* Add way to make errors clearer with an extra message
* Show topics in subscribe error message
* Show partition and topic in query watermark offsets error message

# 0.3.1
* Bump librdkafka to 0.11.1
* Officially support ranges in `add_topic` for topic partition list.
* Add consumer lag calculator

# 0.3.0
* Move both add topic methods to one `add_topic` in `TopicPartitionList`
* Add committed offsets to consumer
* Add query watermark offset to consumer

# 0.2.0
* Some refactoring and add inline documentation

# 0.1.x
* Initial working version including producing and consuming
