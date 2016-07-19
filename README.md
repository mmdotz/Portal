# Portal

** Portal is a game that consists of a series of puzzles that must be solved by teleporting the player's character and simple objects from one place to another.

In order to teleport, the player uses the Portal gun to shoot doors onto flat planes, like a floor or a wall. Entering one of those doors teleports you to the other.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `portal` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:portal, "~> 0.1.0"}]
    end
    ```

  2. Ensure `portal` is started before your application:

    ```elixir
    def application do
      [applications: [:portal]]
    end
    ```

