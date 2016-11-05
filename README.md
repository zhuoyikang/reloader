# Reloader

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `reloader` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:reloader, "~> 0.1.0"}]
    end
    ```

  2. Ensure `reloader` is started before your application:

    ```elixir
    def application do
      [applications: [:reloader]]
    end
    ```

# reloader

if set the config to true , when you run your application by `iex -S mix`, and you change you code and `mix compile` it , the reloader will auto upgrade the change ,so you don't need to restart your application again

``` 
# config.exs
config :reloader, run: true
```
