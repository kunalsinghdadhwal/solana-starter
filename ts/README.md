### Task1: Mint and ata

#### Mint
```bash
kunal@Crusader:~/solana-starter/ts$ pnpm run spl_init

> turbin3-solana@1.0.0 spl_init /home/kunal/solana-starter/ts
> ts-node ./cluster1/spl_init.ts

Creating New token Mint
Mint created successfully
Mint Address: F2a2mKwMhhZnwEU2p6nJUy3n19qVZUnYyn86Sp87o1Y
```

#### ATA
```bash
kunal@Crusader:~/solana-starter/ts$ pnpm run spl_mint

> turbin3-solana@1.0.0 spl_mint /home/kunal/solana-starter/ts
> ts-node ./cluster1/spl_mint.ts

Your ata is: 8b4Xov8NwciDKLdu43hSUJu9x5uBEzrEJoyJEvAMxeKv
Your mint txid: 637kMw9oLzXUG2Wcqp6FmMnhcs5RKR7GjczBTLUvNw6keunu39FLRCihWqzXJCJxi85oZWkBsyXsqAenPZYYeBaK
```

### Task2: SPL Metadata

#### Metadata
```bash
kunal@Crusader:~/solana-starter/ts$ pnpm run spl_metadata

> turbin3-solana@1.0.0 spl_metadata /home/kunal/solana-starter/ts
> ts-node ./cluster1/spl_metadata.ts

2W97mWBFKK4oDRa6jLqcKXcKg5ae5dTBvYjxMV1EdGzWGvZmUZaSxApCuPngapGawVdQqpDmcJ1Wf2JdGtUoEzNs
```

### Task3: SPL Transfer

#### Transfer
```bash
kunal@Crusader:~/solana-starter/ts$ pnpm run spl_transfer

> turbin3-solana@1.0.0 spl_transfer /home/kunal/solana-starter/ts
> ts-node ./cluster1/spl_transfer.ts

bigint: Failed to load bindings, pure JS will be used (try npm run rebuild?)
From ATA: 8b4Xov8NwciDKLdu43hSUJu9x5uBEzrEJoyJEvAMxeKv
To ATA: 49LDtKAruHsuj8boa7hUixCCYXPQYhxKoMXbzTQx31B5
Your transfer txid: 2ggkunMt5ihnxjGLUzK56n8e5CL8VZUQ3Nd4gdTEtteN4S6vxLjyPrN5bXxGvjUadZrxWdk4PeJ66iSKpxJBomYV
```
