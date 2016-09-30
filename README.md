# [WIP] Ding

This is a very simple solution to help with short-term organisation. The beep sound uses the motherboard audio, so it works even if your speakers are muted. Furthermore, it works wherever there's a terminal including ssh sessions.

No dependencies, optional installation via `pip`, and less than 100 lines of code.

## Installation

Download the ding.py binary and run it however you please.

```
$ ./ding.py in 1s
```


`pip` coming soon

## Scenarios

- You want to start work after browsing the news for a bit, but you don't want to get carried away and do no work. Set a timer for 15 minutes:
```
$ ding in 15m
```
- You need to leave at 17:00 and you want to have time to get ready:
```
$ ding at 16:45
```

- Pomodoro technique
```
$ alias pomo="ding in 25m"
$ pomo
```


## Example usage:

```
$ ding in 2m
$ ding in 2h 15m
$ ding in 2m 15s

$ ding at 17:30
$ ding at 17:30:21
```