[android-components](../../index.md) / [mozilla.components.service.glean.private](../index.md) / [MemoryDistributionMetricType](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`MemoryDistributionMetricType(disabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, category: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lifetime: `[`Lifetime`](../-lifetime/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, sendInPings: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, memoryUnit: `[`MemoryUnit`](../-memory-unit/index.md)`)`

This implements the developer facing API for recording memory distribution metrics.

To prevent the number of buckets from being unbounded, values larger than 1 TB
are truncated to 1 TB.

Instances of this class type are automatically generated by the parsers at build time,
allowing developers to record values that were previously registered in the metrics.yaml file.
