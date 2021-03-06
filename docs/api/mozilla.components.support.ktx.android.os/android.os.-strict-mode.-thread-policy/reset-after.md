[android-components](../../index.md) / [mozilla.components.support.ktx.android.os](../index.md) / [android.os.StrictMode.ThreadPolicy](index.md) / [resetAfter](./reset-after.md)

# resetAfter

`inline fun <R> `[`ThreadPolicy`](https://developer.android.com/reference/android/os/StrictMode/ThreadPolicy.html)`.resetAfter(functionBlock: () -> `[`R`](reset-after.md#R)`): `[`R`](reset-after.md#R) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/support/ktx/src/main/java/mozilla/components/support/ktx/android/os/StrictMode.kt#L16)

Runs the given [functionBlock](reset-after.md#mozilla.components.support.ktx.android.os$resetAfter(android.os.StrictMode.ThreadPolicy, kotlin.Function0((mozilla.components.support.ktx.android.os.resetAfter.R)))/functionBlock) and sets the ThreadPolicy after its completion.

This function is written in the style of [AutoCloseable.use](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/use.html).

**Return**
the value returned by [functionBlock](reset-after.md#mozilla.components.support.ktx.android.os$resetAfter(android.os.StrictMode.ThreadPolicy, kotlin.Function0((mozilla.components.support.ktx.android.os.resetAfter.R)))/functionBlock).

