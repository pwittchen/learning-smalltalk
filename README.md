# learning-smalltalk
Repository created in order to learn basics about Smalltalk programming language

## Preparation and executing first program on Linux

Install Smalltalk:

```
sudo apt-get install gnu-smalltalk
```

Create Hello World program in `hello_world.st` file:

```smalltalk
"Hello world Program"

'Hello World!' printNl !
```

Execute program:

```
/usr/bin/gst hello_world.st
```

You should see the following output:

```
'Hello World!'
```

You can also run Smalltalk console by typing:

```
/usr/bin/gst -q
```

and write code directly there.

## References
- [Smalltalk website](http://www.smalltalk.org/)
- [Smalltalk on Wikipedia](https://en.wikipedia.org/wiki/Smalltalk)
- [Hello world program in Smalltalk on Linux](http://www.thegeekstuff.com/2009/10/smalltalk-hello-world-example-how-to-write-and-execute-smalltalk-program-on-linux-os/)
