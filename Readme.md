
# Install

```
npm install gardener -g
npm install garden-core -g
git clone <me>
```

# Run

Examples:

Defaults to DIY data and beta market.

```
make
```

Load demos data agains beta market app:

```
PRELOAD_APP_DATA=demos make

Load demos data agains alpha market app:

```
PRELOAD_APP_MARKET=alpha PRELOAD_APP_DATA=demos make
```

# Reset

```
make clean
```

or

```
DEMOS_COUCHDB=http://demos:secret@localhost:5984 make clean
```
