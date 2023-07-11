# LightIntervalTree

> **Notice**<br>
**This project has been moved. Please see [Jamarino.IntervalTree](https://github.com/jamarino/IntervalTree) instead.**

A light-weight interval tree in C#. Heavily inspired by [RangeTree (GitHub)](https://github.com/mbuchetics/RangeTree), but this project provides a completely new implementation that is, from scratch, focused on reducing memory usage and allocations. `RangeTree` is still a great option if you need a fully featured interval tree.

This package currently offers two different interval tree implementations - `LightIntervalTree` and `QuickIntervalTree` - the former being the most memory-efficient and the latter using a bit more memory in exchange for some significant performance gains. Read on for more details and benchmarks.