```bash
$ cargo run -q -p hola

$ cargo run -q -p hola --bin hola

$ cargo run -q -p hola --bin welcome
```

```
Добро пожаловать на курс «Hands-on основы Rust»

¯\_(ツ)_/¯

Добро пожаловать на курс «Hands-on основы Rust»
```

### Заметки

- `-q` - quiet
- `-p` - указывает на имя пакета (`--package`), которое определяется полем `name = "..."` в файле `Cargo.toml`
- по умолчанию имя бинарника `src/main.rs` совпадает с именем пакета
- в секции `[[bin]]` файла `Cargo.toml` можно поменять имя какого-либо бинарника

Подробнее: [cargo manifest](https://doc.rust-lang.org/cargo/reference/manifest.html)
