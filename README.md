# chordlord
ChordLord for Renoise 3

version 3.06.235 with 235 chords in all scales/keys and notes, edit step follow on record, a jump and up button, arpeggio (skip lines) with 4 modes in the options, window size, button size, chord complexity level…

this topic: https://forum.renoise.com/t/hurray-for-ChordLord/62253 https://renoise.com/tools/chordlord (English) https://renoise.com/tools/acordesenor (Español) https://renoise.com/tools/senhoracordes (Português) https://renoise.com/tools/accordseigneur (Français) https://renoise.com/tools/accordosignore (Italiano)

English version… com.eatme.ChordLord.3.06.235.xrnx (16.9 KB) Version en Español… Traduccion al Español: Susana Sanchez… com.eatme.AcordeSenor.3.06.235.xrnx (17.3 KB) Version en Português… Tradução para Português: Mila B… com.eatme.SenhorAcordes.3.06.235.xrnx (17.2 KB) Version en Français… Traduction en Français par Anna Biscaro… com.eatme.AccordSeigneur.3.06.235.xrnx (17.3 KB) Version in Italiano… Traduzione in italiano: Anna Biscaro… com.eatme.AccordoSignore.3.06.235.xrnx (17.2 KB)

This tool serves chords into the Pattern Editor when record mode is on, and previews chords using OSC server at port 8000 when record mode is off.

**if you have a good idea for a new feature, or find any bugs, please post in the Renoise forum topic or send me a private message on the Renoise forum or per email. For bug reports, please include information about how to reproduce the bug you found. **

Original development, 1/3rd of code by @pandabot and previous tool Scale Finder, 1/3rd of code by @Suva Donate to pandabot for development: https://paypal.me/benjohnson2001 Donate to @EatMe for development of 1/3rd and paying for the translations: http://eatme.pro/donate

This new version also has a button size to choose, skip lines set to the edit step in Renoise after each chord or makes an arpeggio of the chord when recording in the pattern editor with the Arpeggio (skip lines) option. The arpeggator has 4 modes: upwards + extra note, extra note + upwards, extra note + downwards, downwards + extra note. It also features a Window Size choice from 15 to 45 buttons deep. It features a chord library of 235 different chord types, selected in harmony to any tone and (mixed) scale. There are 4 chord complexity levels to choose (0 to 3).

demonstration:

https://soundcloud.com/eatme-mastering/chordlord-demo 5

Secret turbo user trick: Right click the Scroll to scroll big steps! Choose a default velocity and octave at the top of the Renoise window… Also use the tools Inversion to make chords lower/higher.

Download and open, doubleclick, or drap the tool into Renoise, version 3.1 or higher (currently: Renoise 3.3.4), to install the tool. You can then find the new version above via menu Tools… ChordLord 3.06.235 (235 chords), or the older versions of it with (43, 103, 133, 193, 217, 226, 231 chords) not used anymore.

You may also want to try pattern loop mode (numpad Enter) and play cursor following turned off (Scroll Lock button) when experimenting with Record mode on (if you do not want to enable the OSC server). More info on setting the firewall for the OSC server at the bottom of this post.

Recommended instruments / synthesizers to try this with: T-force Alpha Plus 2: https://mastrcode-music.de/en/vst-plugins/t-force-alpha-plus-2/ 7 (required: Visual C runtime, see the bottom of the page) (Windows VST Plugin) MauSynth: http://www.rinki.net/pekka/mausynth/ 4 (required: Visual C runtime, see http://www.rinki.net/pekka/mausynth/help.html 2 ) (Windows VST Plugin) Synth1: http://daichilab.com 3 (Windows & MacOs VST Plugin) Copy the synthesizers to (a / the) VST Plugin folder on your harddrive, and menu Edit… Preferences… Plugs/Misc → Browse for the VST Plugin folder to load these into Renoise.

Virtual Community Orchestra VSCO2: https://vis.versilstudios.com/vsco-community.html 2 (look up the Oliver’s .XRNI conversion for Renoise instruments) (Sample-based, any OS)

BLEEP.xrni (4.6 KB) - an instrument that sounds like it’s a computer - for download in the Renoise forum topic.

Download Renoise 3.3.4 (or the latest version) from http://www.renoise.com/download registered users can download the licensed version via the Renoise backstage.

Version History:

Version History details *Italian version of ChordLord, AccordoSignore in v3.06.235 made available. Minor fixes in all translations. *French version of ChordLord, AccordSeigneur in v3.06.235 made available. *Portuguese version of ChordLord, SenhorAcordes in v3.06.235 made available. *Spanish version of ChordLord, AcordeSenor in v3.06.235 made available. *Bugfix update v3.06.235 from v3.05.235 - fixed issues (arpeggios would sometimes get inserted on reset inversion when changing some options like scale, note, window size, fixed) *Update v3.05.235 from v3.04.235 - Button size can be chosen, fixed an issue (arpeggios now do not get inserted on inversion and chord complexity level choosing, fixed) *Bugfix update v3.04.235 from v3.03.235 - fixed an issue (arpeggios would sometimes get inserted twice on chord button click) *Bugfix update v3.03.235 from v3.02.235 - arpeggios now all behave, extra note fixed better *Bugfix update v3.02.235 from v3.01.231 - arpeggios now behave with extra note as first, added 79 min79 Maj79 m/Maj79 chords, 235 chords in total *Bugfix update v3.01.231 from v2.09.231 - arpeggio w/ note-offs on step edit 0 now ok? *Bugfix update v2.09.231 from v2.08.231 - Note-offs on arpeggio fixed *Update v2.08.231 from v2.07.226 - 4 Arpeggio modes, 57 5Maj7 578 5Maj78 58 added, 231 chords in total *Update v2.07.226 from v2.06.226 - Chord complexity level picker (level 0 - level 3) *Update v2.05.226 from v2.05.226 - Window Size choice from 15-45 buttons *Update v2.05.226 from v2.04.226 - Jump up button, scroll extended to 320 *Bugfix update v2.04.226 from v2.03.226 - Some missing notes in ninth chords were fixed *Bugfix update v2.03.226 from v2.02.226 - Arpeggio skips lines correctly now (no extra at end) *Update v2.02.226 from v2.01.226 - Arpeggio checkbox in the options to skip lines on pattern editor record *Update v2.01.226 from v1.9.226 - jump button to skip lines (set edit steps in Renoise) *Update v1.9.226 from v1.8.217 - edit step jumps line on record, all chords up to the 12th *Bugfix update v1.8.217 from v1.7.217 - keyboard preferences showing correctly now *Bugfix update v1.7.217 from v2.6.217 - scrolling far enough now, credits info txt added *Update v1.6.217 from v1.5.193: end of chord list reached, scroll up, info text added, all variations of all chords up to the 9th chords have been added (217 chords in total now) *Update v1.5.193 from v1.4.193: name change to ChordLord (congratulations to the winner), fixed a little wider buttons for All Chords to display, more info text at options *Update v1.4.193 from v1.3.193: full chord name display text added, wider (fixed) button width, fixed no more dialog at add chord keyboard shortkey on no chords in display, fixed x7susb2 to be x7addb2 chord correctly, minor display long names in chords fixes *Update v1.3.193 from v1.2.193: info text added at options *Update v1.2.193 from v1.1.193: fixed scroll box for no more serious onscreen issues… to do v1.1.193: serious onscreen issues for having no scrollbar on regular and small desktop windows. *Update v1.1.193 from v.1.1.133: Added all 7th, 78th, 9sus2 9sus4 variations, some 10th, 193 chords in total. *Update v1.1.133 from v1.1.103: Added all 7b5 7#5 variations, x7susb2… 133 chords in total. *Bugfix v1.1.103 Maj7sus4b13 was displayed incorrectly as Maj7sus2b13 *Update v1.1.103 from v1.1.43: Added all sus2 sus4 variations and 6th9th chords… 103 in total. *Update v1.1.43 from v1.1: Name changed to com.eatme.MoreChordGun, indicating how many chords in version number *Update v1.1 from v1.0: Up to the 10th chords, add2 and add4 variations… *Minor fix: capital M for Majadd2 *Minor fix: version bumped up to 1.1, name changed to com.eatme.ChordGun.xrnx *to do: scrollbar on All Chords, not possible yet via the Renoise LUA ViewBuilder Api.

related to this tool: Nudge (one lane) tool: https://forum.renoise.com/t/nudge-note-block-editing-tool/45609/28 Renoise to MIDI tool: Midi Convert | Renoise Print My Chords tool: Print My Chords | Renoise (Renoise 2.7 and 2.8 tool) Scale Finder (deprecated): Scale Finder | Renoise Everything “Chord” tools: Chords | Renoise For Recording with the sampler: How to enable Audio Recording of the Stereo Mix Sum on Windows and MacOS and Linux Free starter pack for Renoise on Windows

Miscellaneous / FAQ:

How do I install ChordLord? How do I uninstall ChordLord / the previous MoreChordGun / ChordGun? How do I enable OSC server? How to set the firewall for OSC server? How do I use the keyboard with ChordLord? How do I use ChordLord?

How do I install ChordLord?

Download the ChordLord .xrnx file to your computer. Open the ChordLord.xrnx file (associated with Renoise by the Renoise installer) or drag-and-drop the tool into an open Renoise window. in Renoise, menu Tools… will show the ChordLord tool to open by clicking it in the menu.

How do I uninstall ChordLord / the previous MoreChordGun / ChordGun?

in Renoise, go to menu Tools… Tool Browser. select the tool. click the Uninstall button.

How do I enable OSC server?

ChordLord can preview clicked chords via the enabled OSC server. in Renoise, go to menu Edit… Preferences… and select the OSC tab. check the mark at Enable OSC Server. (make sure the Port is set to 8000) Your firewall will display a message “OK to permit Renoise?”

How do I set the firewall?

Windows firewall will display a message “OK to permit Renoise?” on enabling the OSC server. In your firewall, only allow Renoise in the “Private” domain (your local computer). To make sure the rule is set to only connect from your computer / the private domain, in Windows 10: open the Start menu, type Firewall, open the Firewall settings click " Advanced settings " at the left list. at the Incoming set of rules on the top left seek up the rules for TCP and UDP of Renoise (if you have already allowed it) or create a New rule (right top) twice, one for protocol TCP and one for protocol UDP for the Program of Renoise.exe to Allow the program to have incoming connectivity. open the properties of the incoming TCP rule for Renoise (double click the rule or right-click, properties) at the tab Advanced of the rule at the top section Profiles, only check the “Private” and click " Apply " " OK ". open the properties for the incoming UDP rule for Renoise (double click the rule or right-click, properties) at the tab Advanced of the rule at the top section Profiles, only check the “Private” and click " Apply " " OK ". You may need to restart Renoise for the firewall rules to be set in place.

How do I use the keyboard with ChordLord?

in Renoise, open menu Edit… Preferences… and go to the Keys tab. in the Search box, type chordlord. set the keyboard keys for ChordLord. Make sure there are no other assignments before clicking Assign, or the old assignment will be gone. The last clicked chord in each column can be quickly accessed with the “Insert Scale Chord” 1 to 7 shortcut keys. The inversion can be in/decremented with shortcut keys You can go up and down in the list of chords with set keys for increment and decrement chord type. The scale and root (tonic note) can be incremented and decremented with shortcut keys.

How do I use ChordLord?

make sure you have the latest version installed (visit this topic): https://forum.renoise.com/t/hurray-for-ChordLord/62253

open Renoise with ChordLord installed (see 1. ) 
select an instrument to use on the right panes top in Renoise 
select a default velocity and octave on the top of the Renoise window 
select (optionally) Pattern Block Loop with [Numpad ENTER] for live jamming 
select your Edit Step for with Record enabled 
in Renoise from menu Tools… click ChordLord. 
click the Options button to see the Options and more information 
focus the cursor to the Renoise Pattern Editor and enable Record mode [ESC] 
enable or disable play cursor follow 
click any chord in ChordLord, and it will go to the pattern with the selected instrument and default velocity. 
enable the OSC Server in Renoise (see 3. and 4. ) and disable Record mode and any chord clicked will be previewed with the selected instrument with default velocity. 
The “jump” and “jump up” button can be used to not enter a chord but skip the editing cursor to a number of lines set as Edit Step in the Renoise pattern editor. 
The “arpeggio” checkbox in the options will skip the number of lines set as Edit Step in Renoise between the notes. This only works with Play Cursor Follow disabled. 
Renoise shortcut keys to set the Edit Step are (CTRL)+(numbers above keyboard, + - ) 
The extra options can be made visible with the Options button in ChordLord.
