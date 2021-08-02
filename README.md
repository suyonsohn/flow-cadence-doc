### Make sure /usr/local/bin is in your $PATH environment variable.
`vim .bashrc`


`export PATH="/usr/local/bin:$PATH"`


`source .bashrc` (Reload)




### Check if Flow's been installed properly
`flow version`


`flow cadence`



### Syntax
`log("hello")`


`var isGood: Bool = false`


### [Integers](https://docs.onflow.org/cadence/language/values-and-types/#integers)


### [Function Declarations](https://docs.onflow.org/cadence/language/functions/#function-declarations)



Declare a function named `double`, which multiples a number by two.


The special argument label _ is specified for the parameter,


so no argument label has to be provided in a function call.


```
fun double(_ x: Int): Int {
    return x * 2
}
```
