# Install

```bash
gem ins zscan
gem ins eventmachine
cp config.yml.example config.yml
vi config.yml
```

# Use

Server

```bash
nohup ruby server.rb > log &
```

Local

```bash
ruby local.rb
```

# Test

Prepare gems used by test

```bash
gem ins rspec
gem ins pry
```

Then

```bash
ruby spec.rb
```
