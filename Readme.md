# Gguf-kit

This is my kit of **GGUF** tools.

## Marjor Components

- User Client side
- Downloader


>Original text latter move away



<details>
    
<summary>
Message 1
</summary>

Here is another task
Take a library
https://crates.io/crates/http-downloader
and implement download of https://huggingface.co/TheBloke/phi-2-GGUF/blob/main/phi-2.Q3_K_S.gguf
Download progress should be printed only if
downloaded 1/10 of percent and more then 1 second passed

We need to make sure that we do not print too many messages if file is too big and in opposite too many messages if internet connection is too fast

</details> 



<details>
<summary>
        Message 2
</summary>
 The first task was related to existing library
You can take for example
https://crates.io/crates/gguf-rs
We need an a program with cli interface to output data dependant on provided flags
For example 
--context-length
--estimated-ram-size
--eos-token-id 
</details>
    
