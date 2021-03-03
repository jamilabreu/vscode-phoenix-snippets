# Phoenix Snippets

Working on a Phoenix/Elixir project?

Get up and running faster on [VS Code](https://code.visualstudio.com/) with code snippets for Elixir, Phoenix, and Phoenix LiveView (.ex, .html.eex, .html.leex).

## Supported languages

- elixir (.ex)
- html-eex (.html.eex, .html.leex)

## Snippets

Check out [the snippet files on Github](https://github.com/jamilabreu/vscode-phoenix-snippets/tree/master/snippets) for an up-to-date list of snippets.

### Shortcuts

#### Within `.html.eex`:

|                                  To create...                                   | Use shortcut |
| :-----------------------------------------------------------------------------: | :----------: |
|                                  <%= \_\_\_ %>                                  |      e=      |
|                              <%= case \_\_\_ do %>                              |     case     |
|                                 <%= cond do %>                                  |     cond     |
|                                   <% else %>                                    |     else     |
|                                    <% end %>                                    |      =e      |
|                         <%= for \_\_\_ <- \_\_\_ do %>                          |     for      |
|  <%= form_for \_\_\_, Routes.\_\_\_\_path(@conn, \_\_\_)}, \_\_\_, fn f -> %>   |      ff      |
|                         <%= error_tag \_\_\_, \_\_\_ %>                         |      et      |
|                     <%= label \_\_\_, \_\_\_, \"\_\_\_\" %>                     |      la      |
|                      <%= password_input \_\_\_, \_\_\_ %>                       |      pi      |
|                              <%= submit \_\_\_ %>                               |     sub      |
|                        <%= text_input \_\_\_, \_\_\_ %>                         |      ti      |
|                               <%= if \_\_\_ do %>                               |      if      |
|                       <%= link \"\_\_\_\", to: \_\_\_ %>                        |      lt      |
|                            <%= link to: \_\_\_ do %>                            |     ltb      |
|                      <%= render \"\_\_\_.html\", \_\_\_ %>                      |    render    |
|                             <%= unless \_\_\_ do %>                             |    unless    |
| <%= f = form_for \_\_\_, \"#\", [phx_change: :validate, phx_submit: :submit] %> |     ffl      |
|     <%= live_patch \"\_\_\_\", to: Routes.\_\_\_\_path(@socket, \_\_\_) %>      |      lp      |
|          <%= live_patch to: Routes.\_\_\_\_path(@socket, \_\_\_) do %>          |     lpb      |
|   <%= live_redirect \"\_\_\_\", to: Routes.\_\_\_\_path(@socket, \_\_\_\_) %>   |      lr      |
|        <%= live_redirect to: Routes.\_\_\_\_path(@socket, \_\_\_) do %>         |     lrb      |

#### Within ordinary Elixir code:

|                                         To create...                                          | Use shortcut |
| :-------------------------------------------------------------------------------------------: | :----------: |
|                                        inspect(\_\_\_)                                        |      i       |
|                                      IO.inspect(\_\_\_)                                       |      io      |
|                             IO.inspect(\_\_\_, label: \"\_\_\_\")                             |     iol      |
|                                 defmodule \_\_\_Web.\_\_\_ do                                 |     plug     |
|                            defmodule \_\_\_Web.\_\_\_Controller do                            |      co      |
|                               defmodule \_\_\_Web.\_\_\_Live do                               |      lv      |
|                            defmodule \_\_\_Web.\_\_\_Component do                             |      lc      |
|                              defmodule \_\_\_Web.\_\_\_View do"                               |      vi      |
|                                           ~L\"\"\"                                            |      sl      |
|                                assign(socket, \_\_\_: \_\_\_)                                 |      a       |
|                        def handle_event(\"\_\_\_\", \_\_\_, socket) do                        |      he      |
|                            def handle_info(\"\_\_\_\", socket) do                             |      hi      |
|                          def handle_params(params, \_url, socket) do                          |      hp      |
|                              def render(assigns) do\n\t~L\"\"\"                               |      re      |
| def render(assigns) do\n\tPhoenix.View.render(\_\_\_Web.\_\_\_View, \"\_\_\_.html\", assigns) |     ret      |
