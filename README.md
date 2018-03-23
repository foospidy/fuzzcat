# fuzzcat

When you can't be bothered with figuring out better fuzzing tools

fuzzcat is a rudimentary network protocol fuzzer using bash, netcat, and other tools.

### Usage

For a list of options:

`./fuzzcat --help`

Example:

`./fuzzcat -h 127.0.0.1 -p 8080 -b 4096 -bz 256 -t char`

### Dependencies

- nc
- curl

### Better Fuzzing Tools

- https://github.com/secfigo/Awesome-Fuzzing
- https://www.owasp.org/index.php/Fuzzing
- https://blackarch.org/fuzzer.html
- https://github.com/orgcandman/Simple-Fuzzer
