# bank-transaction-handler
Reads, tokenizes, and applies a batch of bank transactions from different accounts by distributing work among 10+ worker threads. Pthread mutex locks ensure mutual exclusion in account data.
