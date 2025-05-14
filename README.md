# Adpro - Tutorial 9 - Publisher
Haliza N. S. Arfa | 2306211401 | Adpro A

---

## How much data your publisher program will send to the message broker in one run?

Jumlah data yang terkirim oleh publisher adalah lima data untuk setiap run. Ini karena pada `main.rs` terdapat lima kali `publish_event` dan setiap publish_event mengirim satu `UserCreatedEventMessage`.


## The url of: `amqp://guest:guest@localhost:5672` is the same as in the subscriber program, what does it mean?

Publisher dan subscriber mengakses URL yang sama, yaitu `amqp://guest:guest@localhost:5672`. Artinya, keduanya mengakses server AMQP yang sama.
Publisher dan subscriber saling berkomunikasi dengan satu message broker. Pesan yang dikirimkan oleh publisher akan diterima oleh subscriber yang terhubung ke server.


## Message Broker with RabbitMQ

### Running RabbitMQ as message broker
![1-running.png](1-running.png)

