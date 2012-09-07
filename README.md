## Usage

```sh
$ irb -I. -rclient
>> datomic = Datomic::Client.new 'http://localhost:9000', 'socrates'
>> dbname = 'daniel'
>> datomic.create_database(dbname)
```
