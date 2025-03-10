% ramalama-run 1

## NAME
ramalama\-run - Run specified AI Model as a chatbot

## SYNOPSIS
**ramalama run** [*options*] *model* [arg ...]

## OPTIONS

#### **--help**, **-h**
Print usage message

#### **--name**, **-n**
Name of the container to run the model in.

#### **--prompt**

Modify the prompt in the AI Chatbot

## DESCRIPTION
Run specified AI Model as a chat bot. Ramalama pulls specified AI Model from
registry if it does not exist in local storage. By default a prompt for a chat
bot will be started. When arguments are specified, the arguments will be given
to the AI Model and the output returned without entering the chatbot.

## EXAMPLES

Run command without arguments starts a chatbot
```
ramalama run granite

>
```

```
ramalama run merlinite "when is the summer solstice"
The summer solstice, which is the longest day of the year, will happen on June ...
```

## SEE ALSO
**[ramalama(1)](ramalama.1.md)**

## HISTORY
Aug 2024, Originally compiled by Dan Walsh <dwalsh@redhat.com>
