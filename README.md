# nup-1
    defmodule Calculadora do
      use Mix.Project

      defmodule Potencia do
        def numeros(a, b) do
          a ** b
        end
      end

      defmodule Fatorial do
        def of(0), do: 1
        def of(n) when n > 0, do: n*of(n-1)
      end
    end

      defmodule Percentual do
        def numero(n)
        p = "#{Float.round(n * 100, 1)}%"
      end
    end
