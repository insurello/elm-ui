# elm-ui fork for Insurello

This is a fork of [elm-ui](https://github.com/mdgriffith/elm-ui) specifically for Insurello. It’s most likely not useful to anyone else.

Some facts about the fork:

- Based on elm-ui 1.1.7
- Merged Chrome focus fix: https://github.com/mdgriffith/elm-ui/pull/362
- Changed default focus styles from `:focus` to `:focus-visible`.
- Replaced `Element.focused` with `Element.focusedMouseAndKeyboard` (= `:focus`) and `Element.focusedKeyboardOnly` (=
  `:focus-visible`).
