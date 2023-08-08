# Run a Ping go-libp2p node

Tutorial can be found here in the libp2p documentation:

https://docs.libp2p.io/guides/getting-started/go/


## Build 

```
go build -o libp2p-ping-node
```

## Usage

Run a first node 

```bash
./libp2p-ping-node 

# libp2p node address: /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa
```

And run another one, requesting to ping it.

```bash
./libp2p-ping-node  /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa

# libp2p node address: /ip4/127.0.0.1/tcp/36627/p2p/12D3KooWA2wxB2aPMcSAwCio1JmKRd9XRHRywtwyy1juDUQGkxLm
# sending 5 ping messages to /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa
# pinged /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa in 1.016553ms
# pinged /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa in 1.099507ms
# pinged /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa in 657.763µs
# pinged /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa in 371.321µs
# pinged /ip4/127.0.0.1/tcp/36881/p2p/12D3KooWKvgdrVAKBGFgax2APfFrCjfRSZvREfXD1sxT6nJ61QDa in 2.291167ms
```