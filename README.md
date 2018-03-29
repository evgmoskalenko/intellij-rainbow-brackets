# Rainbow Brackets [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?text=Rainbowify+your+IDE&url=https://github.com/izhangzhihao/intellij-rainbow-brackets&via=izhangzhihao&hashtags=rainbow,IntelliJIDEA,DriveToDevelop,idea,developers)

[![Join the chat at https://gitter.im/izhangzhihao/intellij-rainbow-brackets](https://badges.gitter.im/izhangzhihao/intellij-rainbow-brackets.svg)](https://gitter.im/izhangzhihao/intellij-rainbow-brackets?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/izhangzhihao/intellij-rainbow-brackets.svg?branch=master)](https://travis-ci.org/izhangzhihao/intellij-rainbow-brackets) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/1c72f2de07a5452da479565883d3ab74)](https://www.codacy.com/app/izhangzhihao/intellij-rainbow-brackets?utm_source=github.com&utm_medium=referral&utm_content=izhangzhihao/intellij-rainbow-brackets&utm_campaign=badger) [![codecov](https://codecov.io/gh/izhangzhihao/intellij-rainbow-brackets/branch/IC-2017.2/graph/badge.svg)](https://codecov.io/gh/izhangzhihao/intellij-rainbow-brackets) [![Rainbow Brackets Release](https://img.shields.io/github/release/izhangzhihao/intellij-rainbow-brackets.svg)](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) [![Plugin downloads](https://img.shields.io/jetbrains/plugin/d/10080-rainbow-brackets.svg)](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) [![Plugin version](https://img.shields.io/jetbrains/plugin/v/10080-rainbow-brackets.svg)](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/izhangzhihao/intellij-rainbow-brackets/issues)

## Rainbow Brackets / Rainbow Parentheses for IntelliJ IDEA based IDEs

## Compatible with

IntelliJ IDEA, PhpStorm, WebStorm, PyCharm, RubyMine, AppCode, CLion, Gogland, DataGrip, Rider, MPS, Android Studio

## Supported languages

Java, Scala, Clojure, Kotlin, Python, Haskell, Agda, Rust, JavaScript, TypeScript, Erlang, Go, Groovy, Ruby, Elixir, ObjectiveC, PHP, C#, HTML, XML, SQL, Apex language ...

## Screenshots

* with java

![](./screenshots/with-material-theme-ui.png)

* with scala

![](./screenshots/with-scala.png)

* with kotlin

![](./screenshots/with-kotlin.png)

* with HTML/XML

![](./screenshots/with-HTML.png)

* looking forward to your screenshots...

## Install

For Windows - <kbd>File</kbd> > <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>Browse repositories...</kbd> > <kbd>Search for "Rainbow Brackets"</kbd> > <kbd>Install Plugin</kbd> > <kbd>Restart IntelliJ IDEA</kbd>

For Mac - <kbd>IntelliJ IDEA</kbd> > <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Browse repositories...</kbd> > <kbd>Search for "Rainbow Brackets"</kbd> > <kbd>Install Plugin</kbd>  > <kbd>Restart IntelliJ IDEA</kbd>

## Config brackets colors

If you want to config the color, add this to your config file(APP_CONFIG/rainbow_brackets.xml), In my env(MAC os) is /Users/izhangzhihao/Library/Preferences/IntelliJIdea2018.1/options/rainbow_brackets.xml:

```xml
<option name="lightRoundBracketsColors">
      <array>
        <option value="0xE6B422" />
        <option value="0x43A047" />
        <option value="0x2196F3" />
        <option value="0x3F51B5" />
        <option value="0x00897B" />
      </array>
</option>
```

**NOTE: The lightXXX and the darkXXX should be the same size!**

The default color:

```kotlin
    var lightRoundBracketsColors = arrayOf(
            "0xE66A01",
            "0x1B5E20",
            "0x006BE7",
            "0x283593",
            "0x004D40"
    )

    var darkRoundBracketsColors = arrayOf(
            "0xE6B422",
            "0x43A047",
            "0x2196F3",
            "0x3F51B5",
            "0x00897B"
    )

    var lightSquareBracketsColors = arrayOf(
            "0x0B9087",
            "0x827717",
            "0x6444E6"
    )

    var darkSquareBracketsColors = arrayOf(
            "0x33CCFF",
            "0xD4E157",
            "0x8080FF"
    )

    var lightSquigglyBracketsColors = arrayOf(
            "0x0057D2",
            "0x558B2F",
            "0xFF6D27"
    )

    var darkSquigglyBracketsColors = arrayOf(
            "0x1976D2",
            "0x8BC34A",
            "0xFF9863"
    )

    var lightAngleBracketsColor = lightRoundBracketsColors
    var darkAngleBracketsColor = darkRoundBracketsColors
```

## Contribute

* `gradle test`
* `gradle runIde`
* `gradle buildPlugin`

## Acknowledgements

Intellij-rainbow-brackets is heavily inspired by [Rainbow Brackets for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
