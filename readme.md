# Simple Optimism Node on Fly.io

We've tried running an Optimism node on Fly.io. Here's what we've learned:
 * initial syncing takes a long time (~4 days in our case)
 * costs would be ~$200-240/m (depending on your needs, you might be better off
   renting an RPC)
 * monitoring and troubleshooting takes time

We're open sourcing our configuration files in case somebody wants to explore
the same setup direction.

## Deployment

To launch the containers, run:
```
$ flyctl deploy -a dtl -c dtl.toml
```
