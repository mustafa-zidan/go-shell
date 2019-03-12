# go-shell

is a simple implementation of a shell in Go, A simple shell implementation in go as an effort to understand how shell works and understand go.
It demonstrates the basics of how a shell works.

That is: read, parse, fork, exec, and wait.

Since its purpose is demonstration (not feature completeness or even fitness for casual use),
it has many limitations, including:

	- Commands must be on a single line.
	- Arguments must be separated by whitespace.
 	- No quoting arguments or escaping whitespace.
    - No piping or redirection.
   	- Only builtins are: cd, help, exit.

## Contributing

Since this is the subject of a tutorial, I'm not looking to extend it with additional features at this time. So I won't be accepting any pull requests that aren't related to bug fixes (and I'm sure there are still bugs in the code!).

However, that doesn't mean that you shouldn't play with the code, make changes, and explore new features! That's the whole point of this project! It's just that other people are doing the same thing, and this project is merely a starting point for your own exploration.


## License

See LICENSE file