developer              = evad3rs
| released               = {{date|2013|02|04}}
| discontinued           = 
| latest release version = 1.5.3
| latest release date    = {{date|2013|03|12}}
| programming language   = C
| operating system       = [[wikipedia:Microsoft Windows|Windows]] / [[wikipedia:OS X|OS X]] / [[wikipedia:Linux|Linux]]
| size                   = Windows:&nbsp;9.974&nbsp;MiB&nbsp;[ZIP]<br />OS&nbsp;X:&nbsp;9.481&nbsp;MiB&nbsp;[DMG]<br />Linux:&nbsp;9.405&nbsp;MiB&nbsp;[TAR.LZMA]<!-- Win,OSX,Linux = {10458359,9941722,9861405} -->
| platform               = 
| language               = [[wikipedia:English|English]]
| status                 = Deprecated
| genre                  = Jailbreaking
| license                = [[wikipedia:Freeware|Freeware]]
| website                = [http://evasi0n.com/iOS6 evasi0n.com/iOS6]
}}
'''evasi0n''' is a [[jailbreak]] tool that can perform an [[untethered jailbreak]] on [[iOS]] 6.0-6.1.2 for all [[#Supported Devices|supported devices]], excluding both [[Apple TV (3rd generation)]] revisions. It was first released on {{date|2013|02|04}} by [[evad3rs]], and is available for Windows, Mac OS X, and Linux (x86 and x86_64). There is also a [[Cydia.app|Cydia]] package called "evasi0n [[iOS]] 6.0-6.1.2 [[untethered jailbreak|untether]]" which can untether an existing [[tethered jailbreak]] without the need to restore and use the desktop tool. It is a [[userland]] [[jailbreak]]. [[User:posixninja|P0sixninja]] released the [https://github.com/OpenJailbreak/evasi0n6 source code] with his [https://twitter.com/p0sixninja/status/906567268334755841 Twitter announcement on 9-Sept-2017].

== Supported Devices ==
As of evasi0n's release, the only unsupported devices are the [[Apple TV (3rd generation)]] revisions, since the [[kernel]]s on these devices lack an injection vector to run unsigned code. All other devices running [[iOS]] 6.0-6.1.2 are supported (including iOS 5.2 for the [[K66AP|Apple TV (2nd generation)]]).

== Cydia Package ==
The Cydia package contains just three files:
 /private/var/evasi0n/amfi.dylib
 /private/var/evasi0n/evasi0n
 /usr/libexec/dirhelper

It also includes three Debian maintenance scripts: <code>prerm</code> (a bash script that cancels uninstallation if the device is not vulnerable to [[Limera1n Exploit|limera1n]]), as well as <code>postrm</code> and <code>extrainst_</code> binaries. 

== Version History ==
{| class="wikitable"
! Version
! Cydia Package Version
! Release Date
! #
! SHA-1 of evasi0n binary
! Changes
|-
! 1.0
| style="text-align:center;" | 0.1-1
| {{date|2013|02|04}}
| 1
| <code>f16f4592e5d65927faf98a25bce51b22ee9bc831</code>
| 
* Initial Release
|-
! 1.1
| style="text-align:center;" | 0.2-3
| {{date|2013|02|06}}
| 2
| <code>301003d8aa58a0a2e1bf7030bb903ca42a89c851</code>
| 
* Prevents Weather app from appearing on [[List of iPads|iPads]]
* Mitigated the long reboot issue
* Fixed freezing issue with after connecting multiple devices
* Fixed blinking of the jailbreak instructions on OS X.
* OS X app is now codesigned.
|-
! 1.2
| style="text-align:center;" | 0.3-1
| {{date|2013|02|08}}
| 3
| <code>75d140c53bdd615cc279932f843ab3af584086a5</code>
| 
* Disables [[OTA Updates|OTA updates]].
* Correct timezone issue in evasi0n binary if client fails to correct it.
|-
! 1.3
| style="text-align:center;" | 0.3-2
| {{date|2013|02|11}}
| 4
| <code>ff5a5e767acb4c9acf9a25555ae172ad254e596a</code>
| 
* Adds support for the [[N94AP|iPhone 4S]] on [[iOS]] 6.1.1.
|-
! 1.4
| style="text-align:center;" | 0.3-3
| {{date|2013|02|19}}
| 5
| <code>3b2cc5e2d7be397c09d369e83ea52094250d86e9</code>
|
* Added support for iOS 6.1.2
|-
! 1.5
| rowspan="2" style="text-align:center;" | 0.4-1
| {{date|2013|02|23}}
| 6
| <code>cd5a71b4d0b2767294049cc6b3b2ce3e09d68445</code>
|
* Improved boot time.
* Updated included Cydia package list.
|-
! 1.5.1
| {{date|2013|03|05}}
| 7
| <code>1a826416932e77f24c94da17884e48ccfe7cdbf6</code>
|
* Updated included Cydia package list.
|-
! 1.5.2
| rowspan="2" style="text-align:center;" | 0.4.1-1
| {{date|2013|03|11}}
| 8
| <code>3e89337956189e6654cd359995ac550f0372ac8b</code>
|
* Added French translation.
* Added Chinese translation.
* Added German translation.
* Updated bundled Cydia with localization fixes.
|-
! 1.5.3
| {{date|2013|03|12}}
| 9
| <code>3e89337956189e6654cd359995ac550f0372ac8b</code>
|
* Fixes Windows bugs.
|}

== Download ==
{| class="wikitable" style="white-space:nowrap;"
! Version
! OS
! SHA-1 Hash
! colspan="4" | Download
|-
! rowspan="3" | 1.0
| [[wikipedia:Linux|GNU/Linux]]
| <code>c9e4b15a161b89f0e412721f471c5f8559b6054f</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-linux-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/5dped2c9ejnk5r6ahfpg Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!0kUkXBLC!Q8e53kQZpLbGL7PquHWgQFhMU9Ru3WJWxBuzEdkiMJo MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2561828874/evasi0n-linux-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.tar.lzma RapidShare]
|-
| [[wikipedia:OS X|Mac OS X]]
| <code>23f99a0d65e71fd79ff072b227f0ecb176f0ffa8</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-mac-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/du66n0g9wl1j4ta57hpx Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!5h0BwQoa!KdRLFwNJ3OjMS-7Zs2YGQnsvPxAKEsaAjabY__8pNtY MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/3010870584/evasi0n-mac-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.dmg RapidShare]
|-
| [[wikipedia:Microsoft Windows|Windows]]
| <code>2ff288e1798b4711020e9dd7f26480e57704d8b2</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-win-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/tg1t0cz7oakvq7hsv0bd Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!d9ciUApQ!AkwevVU1OtUrEUU7U4fE-V8qqM9aINTAGgjkukShihE MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/3503186483/evasi0n-win-1.0-3c53ba10e2448d311b0f4157f2d7eb568f106c4f-release.zip RapidShare]
|-
! rowspan="3" | 1.1
| GNU/Linux
| <code>6c06a6be87e003eee470eb749b42ffbaafcc9e62</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-linux-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/8smyi2ud2ts41icmtf50 Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!Qw9wwJpC!IE3ZcRv9-yCc-w12Ktmd_AQbVV84xCdIycB7W0OyW8g MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/330748775/evasi0n-linux-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.tar.lzma RapidShare]
|-
| Mac OS X
| <code>ae9d20bc927976a1f55089cd80afca48de0f7a2e</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-mac-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/ydz8ctzuvyjuqb7y0oj5 Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!I0FmTK7Q!YTBYg3e9oEFYIFwFN56XfVqcHAdh1YacWW0OkFE1dHo MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2540645295/evasi0n-mac-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.dmg RapidShare]
|-
| Windows
| <code>4225b01afd4a4fd1277565954964bd3310ad8b5f</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-win-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/velx0yh66mmw4jlf4igm Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!1x9EzajI!CqMhmQ8rl6NODx6S4lOZVRNHyBJ9Dgt3TtRBl4_l2NA MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2426342155/evasi0n-win-1.1-baad71faf69b65b5d97f8fc1391846d5778b289d-release.zip RapidShare]
|-
! rowspan="3" | 1.2
| GNU/Linux
| <code>2e1d1f6c7e6ca775860df03298dce3b0d798658a</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-linux-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/jcerfiaug4ke7f4q6z15 Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!Ak12CQIJ!Mf6_W1l9xPQKvQUYOZEl9w_4yB0HbfqrTRWZ6BJKSjg MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/1511098224/evasi0n-linux-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.tar.lzma RapidShare]
|-
| Mac OS X
| <code>8f91aba478ad28bda800dc5c303be1699fcfb800</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-mac-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/qogbw1s82xi8ogdfk1co Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!wxMFAZhR!KIMDnVwbvscogces8L2z7j1aQIgxPZgsBygLou69gfk MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/3161324199/evasi0n-mac-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.dmg RapidShare]
|-
| Windows
| <code>9942559caf779da6526b9fd0e207d21554a8a9cf</code>
| style="text-decoration: line-through;" | [https://sites.google.com/site/evad3rs/evasi0n-win-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/ld4e7c2ckrjyaj1cym8g Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!9k0iQICT!M_gOkBSyYO5c86LqXX9UUWF-twF-wJMhH9ScPwd1CFE MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2387451293/evasi0n-win-1.2-54502235236cbca6b1fcdbce5694ae2e4c5eb703-release.zip RapidShare]
|-
! rowspan="3" | 1.3
| GNU/Linux
| <code>d93bc45653345e62a315e0a0aaa1b709aacd26c4</code>
| [https://sites.google.com/site/evad3rs/evasi0n-linux-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/yu314zif091koehui5pb Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!Rg0kyRIK!T-_u6CMAgTc1lFl0XMdjwjD3sBcAnOlIUK0GdR-Nh-s MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2098837020/evasi0n-linux-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.tar.lzma RapidShare]
|-
| Mac OS X
| <code>c239da3fd4e312c8468cdca967c86962b2cbd3f9</code>
| [https://sites.google.com/site/evad3rs/evasi0n-mac-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/cfbxzbn3p9gmj24tslwc Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!wgdgHCLb!AHLWLhCqoTQR-qWceDld_nODFZAo-MiMJbDug3my2iE MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2824336729/evasi0n-mac-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.dmg RapidShare]
|-
| Windows
| <code>92bbe23f125f3b0155334f1925943624e24ce130</code>
| [https://sites.google.com/site/evad3rs/evasi0n-win-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/spd5uii8p86ko6ypad1l Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!Uh0gVLbQ!YP63Pk2qb300H_bI17i8i3z7868m5aQPJEWaDob5Qe8 MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2063191667/evasi0n-win-1.3-1cb32faf1e4f4f6c890e6fcbeb004cb694c386f5-release.zip RapidShare]
|-
! rowspan="3" | 1.4
| GNU/Linux
| <code>95c34e7a7220d2dab2e93cf9bb62beb49aef8996</code>
| [https://sites.google.com/site/evad3rs/evasi0n-linux-1.4-91fc5a30e4caf41b22e85427e1b3b738f5158d8e-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/f6llokbz8k2a3ag08d54 Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!B5FGyQLY!QoSdQFK-8yWmXbwhBjr0YhXeFW5YQGih2ZUOzGIO9SA MEGA]
| rowspan="9" {{n/a}}
|-
| Mac OS X
| <code>96b62f303e335bb5c6b78034027606fee5fc93c3</code>
| [https://sites.google.com/site/evad3rs/evasi0n-mac-1.4-91fc5a30e4caf41b22e85427e1b3b738f5158d8e-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/flvifqy9csegg2dyk79n Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!10dgUABL!R8uxsTBRPD58gE6K7cF22QI2xtp0k6OAYcD6L6d-9g4 MEGA]
|-
| Windows
| <code>36adf9ccf62aaf770163666e757c7a89e9ba3a55</code>
| [https://sites.google.com/site/evad3rs/evasi0n-win-1.4-91fc5a30e4caf41b22e85427e1b3b738f5158d8e-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/eesitqovp4ac444txvau Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!04ljSZQJ!F9kaThdAaXyYiOINpn63WA1kEARYujnUh6SRl4gp7Ok MEGA]
|-
! rowspan="3" | 1.5
| GNU/Linux
| <code>923db21a9045df6aaaff27670be92330f4855a21</code>
| [https://sites.google.com/site/evad3rs/evasi0n-linux-1.5-9cde20f28818ac84a776f2db463c265db00c1021-release.tar.lzma Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/0uhcxb83r30519x59avl Box]
| class="rborderplz" style="text-decoration: line-through;"  | [https://mega.co.nz/#!5odg2TBQ!M_csICuu8BazHC16H5Y_zlv6hqw7ZFsz-rOoYkrXdeg MEGA]
|-
| Mac OS X
| <code>cccf7e5b4a83df8c05dcfed98b9627533c018541</code>
| [https://sites.google.com/site/evad3rs/evasi0n-mac-1.5-9cde20f28818ac84a776f2db463c265db00c1021-release.dmg Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/ip3yvihmkkp9qh3arixs Box]
| class="rborderplz" style="text-decoration: line-through;" |  [https://mega.co.nz/#!YpdiWJpZ!GDrEaV5xwMI8XUv2gKER6EstsD1MMgKJD-MkTo41MLM MEGA]
|-
| Windows
| <code>25799bbeea3733c26fb010e6aca432d686fd8f9f</code>
| [https://sites.google.com/site/evad3rs/evasi0n-win-1.5-9cde20f28818ac84a776f2db463c265db00c1021-release.zip Google Sites]
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/tnez6rzlyka0yovc59fu Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!M4En0DqT!TLDb1TO0bnRYxnvd53pcP31Yf0RoD50oeEN9nsERi9o MEGA]
|-
! rowspan="3" | 1.5.1
| GNU/Linux
| <code>cc0bd166a1480c2a838584b201981db1e45ca411</code>
| rowspan="9" {{n/a}}
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/q9kxt1rx26jtsp5t23jf Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!A9cGhJ7R!WBD8mEP44G8xto1QE6buXV8wVr9JjwE8ZzXR1GETZwA MEGA]
|-
| Mac OS X
| <code>4a0e9fb8b5f83fbee5e26d1d7db876cefd09832a</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/jz8730nj3fqhe4u16um0 Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!Jh8VBYwb!E2MPwwr6qlaljNAS_4A2AAN6iS0KZzxEjCaeW84tbM4 MEGA]
|-
| Windows
| <code>a220bb5fb1ccf5cf1cb666dc03e20ac54890835d</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/51vgle3imzdvero2krja Box]
| class="rborderplz" style="text-decoration: line-through;" | [https://mega.co.nz/#!M5FVzIxZ!ExWD6iJVoIO_vmJYuBvFrk0bW7MYmXfYnjDUea2Nhbc MEGA]
|-
! rowspan="3" | 1.5.2
| GNU/Linux
| <code>97fbeb932dd3cb22ec339ec4c2f95a17d570d30c</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/4t8gg74ybfmm0q6ca617 Box]
| rowspan="3" {{n/a}}
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2315522066/evasi0n-linux-1.5.2-7ef0895fb6c0ba200b952906c3d36594ace7bf84-release.tar.lzma RapidShare]
|-
| Mac OS X
| <code>051079f808f5c31f32ba09c6a39f09a8c3479157</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/umd13tz9eunklq0dp0pt Box]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/2207200894/evasi0n-mac-1.5.2-7ef0895fb6c0ba200b952906c3d36594ace7bf84-release.dmg RapidShare]
|-
| Windows
| <code>30d34e23f860eae28d4ae6513edc46ef8aa2042c</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/18ia7rds8ka8rc112inh Box]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/3354239509/evasi0n-win-1.5.2-7ef0895fb6c0ba200b952906c3d36594ace7bf84-release.zip RapidShare]
|-
! rowspan="3" class="blradiusplz" | 1.5.3
| GNU/Linux
| <code>620dcb7996b1f3497827b11876bf0c2fae069ecf</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/2wk6dtc31bw74j514d40 Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!klVWRThY!alwqx8rzv_v6xFH5wgnMCT2R9hDVRSxoWshFmMHvesU MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/496420809/evasi0n-linux-1.5.3-f284166e164e33735163af64b0af4e6336654345-release.tar.lzma RapidShare]
|-
| Mac OS X
| <code>54827d78cb45b7dae4e7566b9ed5c1b833d68850</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/1dtxycfpsyvp0katitwk Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!IlE33IJT!tk0UOjL8Wt7Np8UYi5LjQ3WKPnwqwWK-IY8HOzxsrsY MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/478466150/evasi0n-mac-1.5.3-f284166e164e33735163af64b0af4e6336654345-release.dmg RapidShare]
|-
| Windows
| <code>2f8c2f111a6afefd099ecb0ce5aab63f160940b8</code>
| style="text-decoration: line-through;" | [https://evad3rs.app.box.com/s/mh5vk7hpa7r3ymhnyjsz Box]
| style="text-decoration: line-through;" | [https://mega.co.nz/#!lscBQKST!88XCNjSPj0FYFlu1v3WApcrwW2XnHD_IEPKRef1RiWk MEGA]
| style="text-decoration: line-through;" | [http://rapidshare.com/files/1014635071/evasi0n-win-1.5.3-f284166e164e33735163af64b0af4e6336654345-release.zip RapidShare]
|}

== Exploits and Vulnerabilities ==
evasi0n takes advantage of several vulnerabilities:
* [[Symbolic Link Vulnerability]]
* [[Malformed PairRequest]]
* [[Timezone Vulnerability]] (CVE-2013-0979)
* [[Shebang Trick]]
* [[AMFID code signing evasion]]
* [[launchd.conf untether]]
* [[IOUSBDeviceFamily Vulnerability]] (CVE-2013-0981)
* [[ARM Exception Vector Info Leak]] (CVE-2013-0978)
* [[dynamic memmove() locating]]
* [[vm_map_copy_t corruption for arbitrary memory disclosure]]
* [[kernel memory write via ROP gadget]]
* [[Overlapping Segment Attack]] (CVE-2013-0977)

== Symbols in Untether code ==
{| class="wikitable" style="text-align:left;"
! Symbol
! v1
! v2
! v3
! v4
! v5
! v6
! v7
! v8/9
|-
| start
| 020B0
| 02EF8
| 02BFC
| 02BFC
| 02BFC
| 02E30
| ?
| 02A80
|-
| find_memmove_arm#search
| ?
| ?
| ?
| ?
| ?
| 0AFA0
| ?
| ?
|-
| find_memmove_thumb#search
| ?
| ?
| ?
| ?
| ?
| 0AFD0
| ?
| ?
|-
| find_memmove
| ?
| ?
| ?
| ?
| ?
| 0571C
| ?
| ?
|-
| find_memmove#exit
| ?
| ?
| ?
| ?
| ?
| 05762
| ?
| ?
|-
| _catch_exception_raise_state_identity
| ?
| ?
| ?
| ?
| ?
| ?
| ?
| 065B8
|}

== See Also ==
* [[evad3rs]]
* [[Patchfinder]]

== External Links ==
* [http://blog.accuvant.com/bthomasaccuvant/evasi0n-jailbreaks-userland-component/ Accuvant Labs analysis]
* [http://blog.azimuthsecurity.com/2013/02/from-usr-to-svc-dissecting-evasi0n.html Analysis by kernelpool]
* [http://www.nislab.no/content/download/38610/481190/file/NISlecture201303.pdf kernelpool presentation at NISlab: slides]
* [http://forelesning.hig.no/publish/1363953611-9b560e3de8f2/combined.mp4 kernelpool presentation at NISlab: video]
* [http://www.forbes.com/sites/andygreenberg/2013/02/05/inside-evasi0n-the-most-elaborate-jailbreak-to-ever-hack-your-iphone/ Explanation by planetbeing in Forbes]
* [https://github.com/NetsourceLabs/HopperScripts Hopper Script to demangle evasi0n strings] for Mac client of evasi0n, use in Hopper disassembler
* [http://support.apple.com/kb/HT5704 Apple Response: iOS 6.1.3 Security Fixes]
* [http://support.apple.com/kb/HT5702 Apple Response: iOS 5.2.1 (Apple TV) Security Fixes]
* [http://conference.hitb.org/hitbsecconf2013ams/materials/D2T1%20-%20Pod2g,%20Planetbeing,%20Musclenerd%20and%20Pimskeks%20aka%20Evad3rs%20-%20Swiping%20Through%20Modern%20Security%20Features.pdf Slides from HITB presentation in Amsterdam 2013]
* [http://www.quarkslab.com/en-blog+read+38 Quarkslab blog post describing how evasi0n bypasses code signing]
* [https://twitter.com/p0sixninja/status/906567268334755841 Announcement for public release of source]
* [https://github.com/OpenJailbreak/evasi0n6 Public source code]

[[Category:Jailbreaks]]
[[Category:Jailbreaking]]
[[Category:Cydia Packages]]
