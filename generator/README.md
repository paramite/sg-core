# Generate collectd JSON AMQP or Ceilometer or Rsyslog messages

Connects to a QDR.  Generates either collectd JSON formated metrics or Ceilometer metrics or Rsyslog logs.  Sends the data to the bridge.

## Build

```bash
make
```

## Usage

```bash
./gen -v -n 4 127.0.0.1 5672
```
