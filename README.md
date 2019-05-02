# validdotnet
.NET Validations

# Examples

| Method | Description | Example |
| ------ | ----------- | ------- |
| ThrowIfNull | Handling the null check and throw a `ArgumentNullException` if null | `value.ThrowIfNull(...` |
| ThrowIfNullOrEmpty | Handling the null and empty check of an array and throw a `ArgumentNullException` if null and ArgumentException if empty | `value.ThrowIfNull(...` |
| ThrowIfZero | Handling the zero check and throw a ArgumentException if TimeSpan.Zero | `timeSpan.ThrowIfZero()` |
| ThrowIfNullOrWhitespace | n/a | `str.ThrowIfNullOrWhitespace()` |
