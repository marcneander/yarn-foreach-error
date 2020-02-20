### How to reproduce

```
$ cd packages/failure
$ yarn test
$ echo $?
1
$ cd ../..
$ yarn test
➤ YN0000: [failure]: Process exited without output (exit code 1)
➤ YN0000: Done in 0.31s
$ echo $?
0
```