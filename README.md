# YAGPDB Custom Commands

## General Information

This repository is a collection of custom commands made by me (Galen) that I have deemed suitable for public release.  
If you need assistance with using or have any feedback on these CCs, you can either open an issue at this repo or contact me on discord at galen#8183 (I am also in the YAGPDB.xyz support server, I may not accept unknown friend requests)  

If you don't know how to create a custom command, or just need a refresher/clarification, [this article](https://learn.yagpdb.xyz/the-custom-command-interface) explains the process in detail.  
I have included similar documentation within comments in CCs and the associated README files as is explained in the [YAGPDB CC website](https://yagpdb-cc.github.io/adding-ccs).  

*Note: CCs with recommended regex triggers will generally include `-` and mentioning \@YAGPDB.xyz as prefixes. This can be adapted to your server prefix with [this script](utility/adjustPrefix.gotmpl)*  

General information on YAGPDB.xyz custom commands is available in the [documentation](https://docs.yagpdb.xyz/) and [learning course](https://learn.yagpdb.xyz/).  

## Directory Hierarchy

<details><summary>Code Snippets</summary>

- [Decode caesar cipher](code_snippets/caesar.gotmpl)  
- [Parse flags](code_snippets/parseFlags.gotmpl)  

</details>

<details><summary>Fun</summary>

- [Wordle](fun/wordle)  
- [Minesweeper](fun/minesweeper.gotmpl)  

</details>

<details><summary>Utility</summary>

- [Adjust Prefix](utility/adjustPrefix.gotmpl)  
- [Convert colour](utility/colourConvert.gotmpl)  
- [Display Data Contents](utility/displayData.gotmpl)  
- [Show server emojis](utility/emojis.gotmpl)  
- [Export all CCs](utility/exportCC.gotmpl)  

</details>

---

## License

All code in this repository is free software: you can redistribute it and/or modify it under the terms of version 3 of the GNU General Public License as published by the Free Software Foundation  
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.  
You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/gpl-3.0.en.html>.  

Including the full [GPL v3 license](COPYING) in CCs is not feasible, due to the length of said license greatly exceeding CC size limitations.  
You should instead include the following license text when using code from this repository:  

```
Copyright: Galen CC, 2021-Present
Source: https://github.com/galen8183/yagpdb-cc
Released under license GPL version 3 (https://www.gnu.org/licenses/gpl-3.0.txt)
```
