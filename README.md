# dio

Read/Write command using Direct I/O.

## Usage

**Write file using Direct I/O:**

```console
$ cat /path/to/srcfile | dio write dstfile
```

**Read file using Direct I/O:**

```console
$ dio read /path/to/srcfile
```

## Install

**homebrew tap:**

```console
$ brew install k1LoW/tap/dio
```

**manually:**

Download binany from [releases page](https://github.com/k1LoW/dio/releases)

**go get:**

```console
$ go get github.com/k1LoW/dio
```

## Temporary Install

``` console
$ source <(curl https://raw.githubusercontent.com/k1LoW/dio/master/use)
```
