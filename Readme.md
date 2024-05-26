### ChatGpt in terminal (free)

#### dependencies:
```
    brew install glow
    brew install curl
    brew install jq
```

#### Api-key:
    Free ApiKey[https://github.com/chatanywhere/GPT_API_free]

    https://api.chatanywhere.org/v1/oauth/free/github/render

#### install:
```
    git clone https://github.com/levanliu/chatgpt-shell-cli.git
    cd chatgpt-shell-cli
    sudo bash install.sh
```
#### Usage:
Chat Mode:
```
    chat
```

Chat Mode with initial prompt:
```
    chat -i "You are a code reviewer, find the bugs of following code"
```

Pipe Mode:
```
    echo "write a quick sort by c++" | chat
```
Parameters Mode:
```
    chat -p "What is the regex to match an email address?"
```

MarkDown format:
```
    glow | chat -p "What is the regex to match an email address?"
```
