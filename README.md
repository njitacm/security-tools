# sec-tools
- Repo to store anything about sec server


---


## :card_file_box: Directory Explanation

```s
# Use tree to get a nicer graphical implementation 
.

```
## Chacha Enc
```
$ echo 'bruh' | openssl.exe enc -k 'bruh on bruh' -nosalt -chacha20 2>/dev/null 
▒▒z@
$ echo 'bruh' | openssl.exe enc -k 'bruh on bruh' -nosalt -chacha20 2>/dev/null | cat -v
M--M-iM-^Rz@

$ openssl.exe enc -k 'bruh on bruh' -nosalt -chacha20 -in chacha-enc 2>/dev/null | cat -v
bruh

$ openssl.exe enc -k 'bruh on bruh' -nosalt -chacha20 -in chacha-enc 2>/dev/null | cat -v


```

## :warning: Disclaimer

--- 

<!-- 
- [Advanced Github Usage](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams)
- [Gitemojis for commiting](https://gitmoji.dev/)
- [Mermaid Syntax](https://mermaid-js.github.io/mermaid/#/)
-->