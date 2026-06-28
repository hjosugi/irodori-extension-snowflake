# Native Source

The initial source snapshot was copied from `db/snowflake.rs` in the desktop app.

Source SHA-256: `cb9c693f090832d6d91b4dca176495e446ff7b436247d71692539e27f6493a5c`.


This directory is a migration staging area for `irodori.snowflake`. The active native
ABI shim lives in `src/lib.rs`; engine-specific connect/query/metadata behavior
should move here as the connector runtime contract is wired into the desktop app.

Engine status from `knowledge/engines.json`: `wired`.
