# 235,886 Words

## Usage

Get the package

```
go get github.com/tidwall/words
```

Loop though all the words

```go
for _, word := range words.Words {
    println(word)
}
```

Get a random word

```go
word := words.Words[rand.Intn(len(words.Words)]]
println(word)
```

