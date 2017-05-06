# encode-decode

The program in this challenge is a very simple messaging system. There is a database of messages, and users can read their messages one at a time.

To run the program there are 2 inputs you need:

- a username
- a hash of the last message you read (so you can read the next one)

Run the program like this:

```
node index.js <username> <hash>
```

Test with:   

node index.js bigbird88 60b725f10c9c85c70d97880dfe8191b3
