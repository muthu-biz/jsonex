# Jsonex
`jsonex` is lightweight command-line JSON processor written as an [escript](https://hexdocs.pm/mix/master/Mix.Tasks.Escript.Build.html) to convert JSON into Elixir.

## Installation

1. Install Elixir with [asdf](https://github.com/asdf-vm/asdf-elixir)
2. Clone this repository
3. Run `mix escript.build`
4. Add `./bin/` to your `$PATH`

## Example

$ echo '{"Welcome": "to Elixir"}' | jsonex 