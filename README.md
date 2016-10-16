# dk2-tools
This repo holds all kind of tools for dungeon keeper 2

Meaning of the different folders:

## <a href="/Formats">Formats</a>:
This folder contains the structure-templates for reading Dungeon Keeper 2 file formats (like hiscores, addressbook, camera files etc.). Also there will be some easy scripts to convert them to other formats.

These files are meant to use with 010 Editor.

|File (extension)|Binary template|Purpose|
|---|---|---|
| *.spr | [sprite_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Archives/sprite_struct.bt) | Sprite archive |
| EngineTextures.dat | [texturecache_dat_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Archives/texturecache_dat_struct.bt) | Texturecache data archive |
| EngineTextures.dir | [texturecache_dat_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Archives/texturecache_dir_struct.bt) | Texturecache index directory |
| *.wad | [wad_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Archives/wad_struct.bt) | World asset directory |
| *.kcs | [kcs_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Camera/kcs_struct.bt) | Kamera sweep file |
| *.bf4 | [bf4_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Font/bf4_struct.bt) | Font file |
| *.kwd, *.kld | [kwd_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Level/kwd_struct.bt) | World / Level data file|
| *.kmf | [kmf_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Model/kmf_struct.bt) | Model file (to be extracted from Meshes.wad) |
| *BANK.map | [bank_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Sound/bank_struct.bt) | Sound bank file |
| *SFX.map | [sfx_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Sound/sfx_struct.bt) | Sound SFX File |
| *.sdt | [sdt_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Sound/sdt_struct.bt) | Sound data archive |
| Addressbook.dat | [addressbook_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/addressbook_struct.bt) | Addressbook for Mulitplayer |
| HiScores.dat | [hiscores_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/hiscores_struct.bt) | Hiscore file |
| JCN.dat | [jcn_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/jcn_struct.bt) | Japenese charakter names |
| MBToUni.dat | [mb2uni_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/mb2uni_struct.bt) | Multibyte to unicode |
| residx.dat | [residx_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/residx_struct.bt) | Resource index file |
| *.str | [str_struct.bt](https://github.com/ufdada/dk2-tools/blob/master/Formats/Text/str_struct.bt) | String file |
