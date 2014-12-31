# Hoodie/PouchDB Test app

This is a work-in-progress test app to play with Hoodie's
new `hoodie.store` API based on PouchDB.
See [hoodiehq/wip-hoodie-store-on-pouchdb](https://github.com/hoodiehq/wip-hoodie-store-on-pouchdb)
for more details

## Setup

```
git clone git@github.com:gr2m/hoodie-pouchdb-test.git
cd hoodie-pouchdb-test
npm install
hoodie start
# known issue: the first two loads take a very long time
# It's a problem with how /_api/_files/hoodie.js gets generated
```
