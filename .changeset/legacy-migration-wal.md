---
"@react-native-async-storage/async-storage": patch
---

Android: checkpoint the old `RKStorage` database before migrating it, so data that is still in the WAL file is not lost.
