# ForeverRogueHUD skins

Forty skins, generated from the `SKINS` table in `ForeverRogueHUD.lua` (1.9.0). Pick one on the
**Skins** tab (`/frh skins`), with `/frh skin <name or key>`, or from a macro with
`/run FRH_SetSkin("key")`. The choice is stored in `ForeverRogueHUD_DB.skin` and travels with
profiles. A skin only recolours and picks an edge style; it never moves, resizes or rescales anything.

## Palette fields

| Field | Painted on |
|---|---|
| `bar` | energy bar fill |
| `swing` | swing timer fill (unless *Use skin colour* is off); its background is this colour at 25% |
| `combo` | combo points |
| `barBg` | energy bar background |
| `spark` | swing spark and ready flash |
| `text` | bar text, every label in the options window, swing tick marks |
| `accent` | window title, rules, section headers, selected tab, slider tint, edge inlays |
| `border` | bar outlines and the options window edge |
| `panel` | options window background |
| `iconEdge` | spell icon border |

## Edge styles

All edges are `WHITE8X8` tinted with `SetVertexColor`. Outlines sit 1 px outside the frame.

| Style | Bars and combo points | Spell icons |
|---|---|---|
| `flat` | no outline | border colour only |
| `line` | 1 px outline | border colour only |
| `bevel` | outline, light top line, dark bottom line | light top, dark bottom inlay |
| `rune` | outline with accent pips on the corners | accent pips inside the corners |
| `ember` | outline, dark top line, glowing 2 px accent base | dark top, glowing base |
| `frost` | outline, 2 px icy top line, pale corner pips | icy top, pale pips |
| `gilded` | outline with accent inlays top and bottom | accent inlays top and bottom |

## The skins

Colours are sRGB hex; `@` is the alpha.

| # | Name | Key | Style | bar | swing | combo | accent | text | spark | barBg | border | panel | iconEdge |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Rogue Classic | `rogue_classic` | flat | #FFF569 | #D9D9F2 | #FF9900 | #33CCFF | #FFFFFF | #FFFFFF | #403D1A @70% | #595966 @100% | #0D0D12 @94% | #333333 @100% |
| 2 | Emberforge | `emberforge` | ember | #DB5C1A | #A84D2E | #FF9E26 | #FF8C2E | #FFF2E0 | #FFD980 | #290F08 @80% | #803814 @100% | #170D0A @95% | #9E451A @100% |
| 3 | Frostgrave | `frostgrave` | frost | #3380CC | #5785A8 | #8CD9FF | #99E0FF | #EDF7FF | #D9F2FF | #0A1729 @80% | #4D80A8 @100% | #0A121C @95% | #66A6D9 @100% |
| 4 | Venomdusk | `venomdusk` | line | #478F24 | #6B4D94 | #B3F233 | #A8EB42 | #F0FFE6 | #CCFF80 | #0D1C0A @80% | #427024 @100% | #0D120F @95% | #5C992E @100% |
| 5 | Runeblade | `runeblade` | rune | #386BC7 | #6666B8 | #73CCFF | #66C7FF | #EBF5FF | #B3E6FF | #0A1226 @80% | #3D619E @100% | #0A0D1A @95% | #4D8CE6 @100% |
| 6 | Cryptlight | `cryptlight` | bevel | #5C8566 | #757A61 | #BFF2B3 | #B3F2B8 | #EBFAE6 | #D9FFD9 | #0F1712 @80% | #4D6652 @100% | #0D120F @95% | #6B9470 @100% |
| 7 | Wyrmfire | `wyrmfire` | ember | #D13D1F | #BD6B1A | #FFCC33 | #FFB833 | #FFF2D9 | #FFE673 | #260A08 @80% | #852914 @100% | #170A0A @95% | #B3381A @100% |
| 8 | Bloodmoon | `bloodmoon` | bevel | #A81A24 | #853342 | #F24D4D | #EB424D | #FFEBEB | #FF9999 | #210508 @82% | #6B141A @100% | #14080A @95% | #991F24 @100% |
| 9 | Ashen Covenant | `ashen_covenant` | flat | #707075 | #857A70 | #CCC7BD | #D1CCC2 | #F5F2ED | #FFFFFF | #141414 @80% | #575452 @100% | #121212 @95% | #6B6966 @100% |
| 10 | Deepstone | `deepstone` | bevel | #5C6B80 | #756B5C | #9EBDDB | #94B8DB | #EDF2FA | #D9E6FF | #0F1217 @82% | #475261 @100% | #0D0F14 @95% | #5C6B80 @100% |
| 11 | Hollow Lantern | `hollow_lantern` | gilded | #C2751A | #80668F | #FFD159 | #FFCC52 | #FFF5DB | #FFEB99 | #1F1208 @80% | #855C1A @100% | #120D12 @95% | #B88024 @100% |
| 12 | Gilded Reliquary | `gilded_reliquary` | gilded | #AD801F | #8F3D3D | #FFDB66 | #FFD661 | #FFF7E0 | #FFF2B3 | #1C1408 @82% | #9E7A29 @100% | #140F0A @95% | #CC9E33 @100% |
| 13 | Plaguewick | `plaguewick` | line | #75851F | #705C80 | #D1EB47 | #CCEB4D | #F7FFE0 | #E6FF8C | #141708 @80% | #5C6B1F @100% | #0F120A @95% | #809429 @100% |
| 14 | Stormcall | `stormcall` | rune | #4266DB | #7075A8 | #B3CCFF | #A8C7FF | #F0F5FF | #E6F2FF | #0A0F29 @80% | #4257A8 @100% | #0A0D1C @95% | #5775E6 @100% |
| 15 | Iron Vigil | `iron_vigil` | bevel | #667585 | #807066 | #C7D6E6 | #BDD1E6 | #F2F7FC | #FFFFFF | #121417 @82% | #5C6670 @100% | #0F1214 @95% | #758594 @100% |
| 16 | Obsidian Oath | `obsidian_oath` | line | #61388F | #4D5770 | #B880FF | #B37AFF | #F2EBFF | #D9B3FF | #0D0817 @85% | #4D3375 @100% | #08080D @96% | #7047A8 @100% |
| 17 | Sunken Choir | `sunken_choir` | frost | #1F858F | #427099 | #73EBE0 | #6BE6DB | #E6FFFC | #B3FFF2 | #081A1C @80% | #296B75 @100% | #081214 @95% | #33949E @100% |
| 18 | Thornmantle | `thornmantle` | line | #3D803D | #806138 | #9EE066 | #99DB66 | #F0FFE6 | #CCFF99 | #0A1A0A @80% | #3D6633 @100% | #0D120A @95% | #528F47 @100% |
| 19 | Wolfsbane | `wolfsbane` | rune | #804DB8 | #66708F | #D19EFF | #CC99FF | #F7EDFF | #E6CCFF | #140D21 @80% | #664294 @100% | #0F0A17 @95% | #8F5CCC @100% |
| 20 | Cinderhall | `cinderhall` | ember | #B34D33 | #8F7061 | #FF8F52 | #FF854D | #FFF0E6 | #FFBF80 | #210F0A @82% | #753829 @100% | #140D0D @95% | #9E4733 @100% |
| 21 | Moonwell | `moonwell` | frost | #5770D6 | #7580B3 | #C7DBFF | #C2D6FF | #F2F7FF | #EBF5FF | #0D1229 @80% | #576BB8 @100% | #0A0D1C @95% | #708FF0 @100% |
| 22 | Serpent Coil | `serpent_coil` | line | #298A5C | #85752E | #80F299 | #75EB94 | #EBFFF0 | #BFFFCC | #081A12 @80% | #2E704D @100% | #0A120D @95% | #389E6B @100% |
| 23 | Bonewarden | `bonewarden` | bevel | #8F8061 | #75706B | #EBE0BD | #EBDEB8 | #FCF7EB | #FFFAE6 | #1A1712 @80% | #7A7057 @100% | #12120F @95% | #A39470 @100% |
| 24 | Nightshade | `nightshade` | rune | #752985 | #4D4D8F | #E075F0 | #DB70EB | #FAEBFF | #FFB3FF | #14081A @84% | #612970 @100% | #0D0812 @96% | #8F38A3 @100% |
| 25 | Dawnsteel | `dawnsteel` | gilded | #808599 | #AD7542 | #FFD68F | #FFD18A | #FFFAF0 | #FFF2CC | #14141A @80% | #858594 @100% | #121217 @95% | #B3A88F @100% |
| 26 | Grimoire | `grimoire` | rune | #703D4D | #665C8F | #DBA8F5 | #D6A3F0 | #FAF0FA | #F2CCFF | #140A0F @84% | #663D57 @100% | #0F0A0F @96% | #8F5780 @100% |
| 27 | Torchbearer | `torchbearer` | ember | #CC7014 | #945C38 | #FFC247 | #FFBD42 | #FFF5DB | #FFE68C | #241205 @80% | #8F5214 @100% | #140F08 @95% | #C2701A @100% |
| 28 | Verdant Ruin | `verdant_ruin` | bevel | #4D804D | #707A66 | #B3E68F | #ADE08A | #F2FFEB | #D9FFBF | #0D170D @80% | #476642 @100% | #0D120D @95% | #618F5C @100% |
| 29 | Saltbound | `saltbound` | flat | #4D7A8A | #858070 | #BDE6EB | #B8E0E6 | #F2FCFC | #E6FFFF | #0D1417 @80% | #4D6B75 @100% | #0D1214 @95% | #618A94 @100% |
| 30 | Wraithglass | `wraithglass` | frost | #4D8580 | #6B758F | #A8FAEB | #A3F5E6 | #EDFFFC | #CCFFFA | #0A1717 @72% | #4D8580 @90% | #0A1214 @92% | #66B3A8 @100% |
| 31 | Emberwood | `emberwood` | ember | #995729 | #66753D | #FAA857 | #F5A352 | #FFF2E0 | #FFD18C | #1C0F08 @82% | #704224 @100% | #140F0A @95% | #995C2E @100% |
| 32 | Silver Chalice | `silver_chalice` | gilded | #7A808A | #8F4D5C | #EBF0FA | #E6EBF7 | #FFFFFF | #FFFFFF | #17171A @80% | #999EA8 @100% | #121214 @95% | #C7CCD6 @100% |
| 33 | Rotgarden | `rotgarden` | line | #66702E | #7A4D57 | #CCD65C | #C7D15C | #FAFCE0 | #F2FF99 | #121408 @82% | #576129 @100% | #0F120A @95% | #7A8A38 @100% |
| 34 | Starfall | `starfall` | rune | #4D42B3 | #8066A8 | #FFE68F | #FFE08A | #F7F5FF | #FFF5CC | #0D0A21 @82% | #4D479E @100% | #0A0A17 @96% | #7066E6 @100% |
| 35 | Trollhunt | `trollhunt` | bevel | #338070 | #9E5C3D | #FA995C | #F59457 | #F2FFF7 | #FFD9A6 | #081714 @80% | #386B61 @100% | #0A120F @95% | #47998A @100% |
| 36 | Brimstone | `brimstone` | ember | #BD750F | #9E3824 | #FFD633 | #FFD12E | #FFF7D6 | #FFF280 | #211405 @82% | #8A5C0F @100% | #140F08 @95% | #BD8014 @100% |
| 37 | Gloam | `gloam` | flat | #5C4D7A | #706170 | #C2ADE6 | #BDA8E0 | #F5F0FC | #EBE0FF | #0F0D14 @82% | #52476B @100% | #0D0D12 @95% | #706194 @100% |
| 38 | Frostfang | `frostfang` | frost | #4D8FB8 | #708094 | #CCF2FF | #C7F0FF | #F2FCFF | #EBFFFF | #0D1A24 @80% | #578FB3 @100% | #0A121A @95% | #75BDEB @100% |
| 39 | Beastcaller | `beastcaller` | line | #8F6633 | #577A42 | #F5BD66 | #F0B861 | #FFF7E6 | #FFE099 | #1A120A @82% | #70522E @100% | #120F0A @95% | #997038 @100% |
| 40 | Vaultlight | `vaultlight` | gilded | #998538 | #617099 | #FFEB8F | #FFE685 | #FFFAE6 | #FFF7BF | #1A170A @82% | #948038 @100% | #12120D @95% | #C7AD47 @100% |

## Readability

The mocked test suite computes the WCAG contrast of every palette: for the 39 themed skins the text
colour is at least 3:1 against both the energy fill and the swing fill, and for all 40 it is at least
4.5:1 against the bar background and 7:1 against the options window. **Rogue Classic** is the
unchanged 1.8.0 look (white text on a bright yellow energy bar, about 1.1:1 on the fill itself) and is
exempt from the fill check on purpose; it relies on the font's drop shadow, as it did before.
These are computed from the palette numbers, not seen on screen: the bar art
(`UI-StatusBar`) darkens the fill a little in game, and none of it has been looked at in the client.
