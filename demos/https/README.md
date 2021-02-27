# HTTPS client

Simple https client example.
Connects using TLS and sends simple GET request.

## Usage

1. Compile

```c
gcc client.c -o client -lssl -lcrypto
```

2. Obtain ip address of some service with `dig`:

```sh
dig duckduckgo.com
```

2. Run
```c
./client <obtained_service_ip> 443
```

