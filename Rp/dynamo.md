#### Amazon Dynamo (Highly available key value store)

- Partionting
  - Consistent Hashing.
- High Available writes
  - Vector clocks with reconciliation during reads.
- Handling Temporary Failures
  - Sloppy quorum and hinted handoffs.
- Handling permanent failures
  - Anti-entropy using Merkle trees.
  - Synchronize diverged replicas.
- Membership and failure detection
    - Gossip based membership protocol and failure detection.
    - De centralized membership info storing.