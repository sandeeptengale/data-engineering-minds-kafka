This repository consists of the Python Kafka clients implemented using Confluent Kafka API. Please check the step-by-step video tutorial on my [Youtube](https://www.youtube.com/watch?v=vOWePzuy-O8) channel. All these clients connect to the Kafka brokers via SASL_SSL security mode.

### Steps to prepare the setup before executing the script
1. Install librdkafka
`
brew install librdkafka
`

2. Install virtual environment
`
pip install virtualenv virtualenvwrapper
`

3. Create the virtual environment
`
python -m venv producer-tutorial
`

4. Activate the virtual environment
`
source venv/bin/activate
`

5. Install the python libraries inside the requirements file (for example - producer-requirements.txt)
`
pip install -r producer-requirements.txt
`


### Useful links
1. [Confluent Kafka Python API documentation](https://docs.confluent.io/platform/current/clients/confluent-kafka-python/html/index.html#)
2. [Confluent Kafka Python github repository](https://github.com/confluentinc/confluent-kafka-python)
3. [librdkafka documentation](https://docs.confluent.io/platform/current/clients/librdkafka/html/index.html)
4. [librdkafka configuration parameters](https://github.com/edenhill/librdkafka/blob/master/CONFIGURATION.md)
5. [Sticky Partitioning](https://www.confluent.io/blog/apache-kafka-producer-improvements-sticky-partitioner/)
6. [General Apache Kafka Producer configuration parameters](https://kafka.apache.org/documentation/#producerconfigs)




 