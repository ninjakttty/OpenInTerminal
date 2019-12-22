<p align="center">
  <img width="100%" src="./Resources/screenshots/readme-header.png"><br/><br/>
  <a href="https://github.com/Ji4n1ng/OpenInTerminal/releases/tag/2.0.5"><img src="https://img.shields.io/badge/Version-2.0.5-blue.svg?longCache=true&style=for-the-badge"></a>
  <a href="https://github.com/Ji4n1ng/OpenInTerminal/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?longCache=true&style=for-the-badge"></a>
  <img src="https://img.shields.io/badge/Made With-Swift-red.svg?longCache=true&style=for-the-badge">
  <a href="https://travis-ci.org/Ji4n1ng/OpenInTerminal"><img src="https://img.shields.io/travis/Ji4n1ng/OpenInTerminal.svg?style=for-the-badge"></a>
</p>

English | [OpenInTerminal 中文说明](./Resources/README-zh.md)

[OpenInTerminal-Lite English](./Resources/README-Lite.md) | [OpenInTerminal-Lite 中文说明](./Resources/README-Lite-zh.md)

> HELP WANTED! Recently I have a signature problem with the version `2.1.0`. Please see [#61](https://github.com/Ji4n1ng/OpenInTerminal/issues/61). Thanks a lot!

## How to use 🚀

| Features | OpenInTerminal | OpenInTerminal-Lite & OpenInEditor-Lite |
| --- | --- | --- |
| Open current directory in Terminal (or Editor) | ![](./Resources/screenshots/main-open-in-terminal.gif) | ![](./Resources/screenshots/lite-run.gif) |
| Open selected folder or file in Terminal (or Editor) | ![](./Resources/screenshots/main-open-in-editor.gif) | ![](./Resources/screenshots/lite-run-editor.gif) |
| Copy path of the selected file or Finder window to Clipboard | ![](./Resources/screenshots/main-copy-path-to-clipboard.gif) |  ❌ Not Supported |

### More features

| Features | OpenInTerminal | OpenInTerminal-Lite & OpenInEditor-Lite |
| --- | --- | --- |
| Support Terminal, [iTerm](https://www.iterm2.com/), [Hyper](https://github.com/zeit/hyper) and [Alacritty](https://github.com/jwilm/alacritty). | ✅ | ✅ |
| Support [Visual Studio Code](https://code.visualstudio.com/), [VSCode Insiders](https://code.visualstudio.com/insiders/), [Atom](https://atom.io/), [Sublime Text](https://www.sublimetext.com/), [VSCodium](https://github.com/VSCodium/vscodium), [BBEdit](https://www.barebones.com/products/bbedit/) and [TextMate](https://macromates.com). | ✅ | ✅ |
| Set to open a new tab or window. | ✅ | ✅ |
| Support English, Chinese and French. | ✅ | ✅ |
| GUI preferences | ✅ | ❌ |
| Support keyboard shortcuts. | ✅ | ❌ |
| Support Dark Mode. | ✅ | ❌ |
| No need to run in the background | ❌ | ✅ |

## OpenInTerminal and OpenInTerminal-Lite (OpenInEditor-Lite) 👀

Which one to choose? Both of these apps are my children. If you like more powerful features and GUI preferences, then you can use `OpenInTerminal`. If you just need to open terminal or editor and don't want to keep the application in the background, then you can use `OpenInTerminal-Lite`. 

For me, I prefer the Lite version, which only needs to click once to complete the function (and the other needs to click twice 😂), and it is more lightweight.

For `OpenInTerminal-Lite` users:

Please check the document: [OpenInTerminal-Lite English](./Resources/README-Lite.md) | [OpenInTerminal-Lite 中文说明](./Resources/README-Lite-zh.md)

## How to install 🖥

### 1. Download

#### a) Homebrew (current version: 2.0.5)

```
brew cask install openinterminal
```

#### b) Manual (latest version: 2.0.5)

1. Download from [release](https://github.com/Ji4n1ng/OpenInTerminal/releases).

2. Move the app into `/Applications`.

> ⚠️ macOS will ask your permissions to access Finder and other applications when you run the app for the first time. Please give OpenInTerminal the permissions.

### 2. Check Finder Extension permission

Open the OpenInTerminal app. Go to `System Preferences` -> `Extensions` -> `Finder Extensions`, check the permission button as below.

<div>
  <img src="./Resources/screenshots/finder-extension-permission.png" width="450px">
</div>

### 3. Set OpenInTerminal to launch at login

Just check the `Launch OpenInTerminal at login` button in `Preferences`.

> Because the Finder Extension does not work when the main app is not running, it is very recommended to set OpenInTerminal to launch at login.

<div>
  <img src="./Resources/screenshots/pref-general.png" width="400px">
</div>

## Todo 👨‍💻

If you have a good idea, feel welcome to open a new [issue](https://github.com/Ji4n1ng/OpenInTerminal/issues/new/choose).

## Upcoming Features 🎉

🎉 OpenInTerminal finally supports Finder Extersion Standalone Operation Mode in version 2.1.0. It is not necessary to run OpenInTerminal in the background.

- Finder Extension Standalone Operation Mode.
- Finder context menu title will change to the current default terminal / editor.
- Open iTerm with split pane.

## Support ❤️

Hello, I am Ji4n1ng. I am a student and OpenInTerminal is an open source project I maintain in my spare time. It is free and open source. 

Recently because of strange bugs, signed OpenInTerminal(new version 2.1.0) cannot run on other computers. I don't know why. I will be very grateful that you can support me in purchasing an Apple Developer account ($99 is not a small number for students, it is close to my three-week living expenses.). 

Or someone can help me solve this problem. Please see [#61](https://github.com/Ji4n1ng/OpenInTerminal/issues/61). Thanks a lot!

| PayPal | AliPay | WeChat Pay |
| --- | --- | --- |
| [paypal.me/ji4n1ng](https://www.paypal.me/ji4n1ng) | ![AliPay](./Resources/screenshots/Alipay.jpg) | ![WeChatPay](./Resources/screenshots/WeChatPay.jpg) |

## FAQ ❓

<details><summary>1. What is the difference between OpenInTerminal and OpenInTerminal-Lite?</summary><br>
<p>OpenInTerminal currently has a normal version and a lite version. If you only need to open the terminal and don't need to keep the application in the background, then you can use the Lite version. If you like more powerful features, then choose the normal version. </p>
</details>

<details><summary>2. Finder Extension doesn't work</summary><br>
<p>Please check if there is an OpenInTerminal(main app) icon in the status bar. The Finder Extension will always be in the toolbar. But if the main app is not open, it will not work. It is recommended to set OpenInTerminal to launch at login in Preferences.</p>
</details>

<details><summary>3. I accidentally clicked on the <code>Don't Allow</code>  button.</summary><br>
<p>You can run the following command in the terminal. This will reset the permissions in the System Preferences.</p>
<br><code>tccutil reset AppleEvents</code><br>
</details>

<details><summary>4. Special characters in the <code>path</code>.</summary><br>
<p>Please do not use backslash <code>\</code> and double quotes <code>"</code> in the path.</p>
</details>

<details><summary>5. Open two Terminal windows on Mojave</summary><br>
<p>This problem usually occurs when Terminal is first started. So you can use <code>⌘W</code> to close Terminal window instead of using <code>⌘Q</code> to quit Terminal.</p>
</details>

## Changes 🗒

**version 2.0.5**

- Fix: check application exist bug

**version 2.0.4**

- Support TextMate
- Fix: keyboard shortcut bug

**version 2.0.3**

- Fix: Finder context menu icon supports dark mode

<details><summary>old version</summary><br>
<p><strong>version 2.0.2</strong></p>
<ul>
<li>Support Visual Studio Code - Insiders</li>
<li>Support for hiding the status bar icon</li>
</ul>
<p><strong>version 2.0.1</strong></p>
<ul>
<li>Support BBEdit</li>
<li>Add icon in Finder context menu</li>
<li>Fix: check application folder under home directory</li>
</ul>
<p><strong>version 0.10.2</strong></p>
<ul>
<li>Fix: Finder context menu does not appear on other disks.</li>
</ul>
<p><strong>version 0.10.1</strong></p>
<ul>
<li>iTerm will not leave `cd xxx` in history.</li>
<li>You need to click the `window` button or the `tab` button of iTerm again in `Preferences`.</li>
</ul>
<p><strong>version 0.10.0</strong></p>
<ul>
<li>Support keyboard shortcuts.</li>
<li>Support VSCodium.</li>
</ul>
<p><strong>version 0.9.1</strong></p>
<ul>
<li>Support French.</li>
</ul>
<p><strong>version 0.9.0</strong></p>
<ul>
<li>OpenInTerminal has been released after several weeks of development. If you have suggestions or there are bugs, please feel free to open an issue.</li>
</ul>
<p><strong>version 0.4.1</strong></p>
<ul>
<li>Support <code>Alacritty</code></li>
</ul>
<p><strong>version 0.4.0</strong></p>
<ul>
<li>You can set a default to open a new tab or window when using <code>Terminal</code> and <code>Hyper</code>.</li>
</ul>
<p><strong>version 0.3.0</strong></p>
<ul>
<li>Change name to <code>OpenInTerminal-Lite</code> (<code>OpenInTerminal</code> will come as a more powerful version in the future.)</li>
<li>Fix a bug that some special characters in the path would crash the program when opening Hyper.</li>
</ul>
<p><strong>version 0.2.0</strong></p>
<ul>
<li>Add terminal selector</li>
<li>Cancel running <code>clear</code> command when opening iTerm</li>
</ul>
<p><strong>version 0.1.1</strong></p>
<ul>
<li>Support <code>Hyper</code></li>
<li>Give priority to creating a new tab when opening iTerm</li>
</ul>
<p><strong>version 0.1.0</strong></p>
<ul>
<li>First release</li>
</ul>
<br>
</details>

## Special Thanks to ❤️

### Contributors

- [Camji55](https://github.com/Camji55)

### Translators

- [Dorian Eydoux](https://github.com/dorian-eydoux)

### Reference projects

- [jbtule/cdto](https://github.com/jbtule/cdto)
- [es-kumagai/OpenTerminal](https://github.com/es-kumagai/OpenTerminal)
- [tingraldi/SwiftScripting](https://github.com/tingraldi/SwiftScripting)
