github.com/gabr

INFO q0 Learning materials in order:
	https://www.youtube.com/watch?v=XCsL89YtqCs
	https://golang.org/doc/code.html
	https://tour.golang.org
	>	https://golang.org/doc/effective_go.html	q1
	https://www.youtube.com/watch?v=f6kdp27TYZs
	https://www.youtube.com/watch?v=QDDwwePbDtw
	https://golang.org/doc/codewalk/sharemem/
	https://vimeo.com/53221558
	https://golang.org/doc/articles/wiki/
	https://golang.org/doc/codewalk/functions/

INFO q2 Oficial language docs
	https://golang.org/doc/
	https://golang.org/ref/spec

INFO q3 Sources of news
	https://blog.golang.org/

INFO q4 About printing int as binary.

	The '%b' makes integer to be presented as binary string.
	But it will not show leading zeros.

	In order to pad resulted string, the number representing
	width has to be putted before format char: '%8b'.
	Unfortunately the default padding (even for binary) are
	spaces. To used '0' padding prefix the format with '0'.

	Result (eight zeros padded binary format): '%08b'

TODO q1 Finish reading docs

TODO q5 Skills to acquire (project name in brackets)

	Testing (firstrecurrchar, ...)
		https://golang.org/pkg/testing/
	Benchmarks
		https://dave.cheney.net/2013/06/30/how-to-write-benchmarks-in-go
	Command line arguments (cliexample)
	Files operations
		Open/Close (typedlog)
	>	Write/Read text files (gocat)
		Write/Read binary files
		Create/Move/Delete
		Finding files - directories tree exploration
	Strings manipulations
		Create
		Trim
		Split
		Iterate chars/runes (firstrecurrchar)
		Replace
		Substrings
	Regular expressions
	DLL/libs imports
	Network communication
		tcp:
			server
			client
		http:
			server
			client
	WebApi	
	WebSite

