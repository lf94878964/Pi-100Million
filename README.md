# Pi (π) Digit Files

This repository contains plain text files with the value of π (pi) truncated to different numbers of decimal places. Each file starts with `3.` followed by the digits after the decimal point (no extra whitespace or trailing newline).

## Files

| File | Decimal digits | File size |
|---|---|---|
| `pi_10.txt` | 10 | 12 bytes |
| `pi_100.txt` | 100 | 102 bytes |
| `pi_1000.txt` | 1,000 | 1,002 bytes |
| `pi_10000.txt` | 10,000 | 10,002 bytes |
| `pi_100000.txt` | 100,000 | 100,002 bytes |
| `pi_1000000.txt` | 1,000,000 | 1,000,002 bytes |
| `pi_10000000.txt` | 10,000,000 | 10,000,002 bytes |
| `pi_50000000.txt` | 50,000,000 | 50,000,002 bytes |
| `pi_100000000.7z` | 100,000,000 | 100,000,002 bytes | 

> The `pi_100000000.7z` archive needs to be decompressed.

## Example

`pi_10.txt`:
```
3.1415926535
```

## Format

Each file follows the pattern:

```
3.<N digits of pi>
```

where `<N digits of pi>` is the first N digits of π after the decimal point.