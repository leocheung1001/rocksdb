# RockDB with YCSB benchmarks

This simple project is based on [RocksDB](https://github.com/facebook/rocksdb)

Useful files for running benchmarks:
The benchmarks are run through the standard RocksDB db_bench 
https://github.com/facebook/rocksdb/wiki/Benchmarking-tools

db_bench_tool.cc is the main db_bench file. In addition to the original benchmarks,
some YCSB workloads are also added in this repository.

If you happen to encounter some Windows line ending issues on a Mac. Please "clean" those files and you are good to go.
