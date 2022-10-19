Make a playable piano in Scratch!

<details>
<summary>This challenge uses the "Music" extension. Expand this for more info...</summary>
<br>
You need to load the extension in the scratch editor:
<img src="/assets/images/scratch_extensions.png" style="max-height:25%">

<br><br>
<a href="https://en.scratch-wiki.info/wiki/Scratch_Wiki:Table_of_Contents/Music_Blocks">Documentation on the Music blocks</a>

</details>
<br>

This challenge has different levels:

<img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper">
* Display at least 5 keys
* Keys should play a sound when clicked
* Keys should also be playable by hitting number keys (e.g. pressing '1' makes the first key play)
* When a key is playing a sound, the key should change its appearance (e.g. change color)

<details>
<summary>Hint 1: Which blocks?</summary>

Use the <a href="https://en.scratch-wiki.info/wiki/When_()_Key_Pressed_(Events_block)">When [key] pressed</a> and <a href="https://en.scratch-wiki.info/wiki/When_This_Sprite_Clicked_(block)">When this sprite clicked</a> blocks to trigger the note, and <a href="https://en.scratch-wiki.info/wiki/Play_Note_()_for_()_Beats_(block)">Play note</a> block to actually play the note.
<br>

The 'play note' block has a note picker if you click into it:

<img src="/assets/images/scratch_play_note_screenshot.png" style="max-width:25%">
</details>
<br>

<img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper"><img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper">
* Everything from the 1 pepper version
* Add at least 2 buttons that play different songs when pressed. If you need easy songs:
  * Twinkle Twinkle Little Star is: C C G G A A G / F F E E D D C
  * Mary Had a Little Lamb is: E D C D E E E / D D D E E E
* Add a way to control the tempo of the music (hint: if you display a variable on the canvas, you can right click on it and change it to a slider, and also set the allowed numerical range for the slider)
* Add a metronome that plays the tempo in the background

<details>
<summary>Hint 1: Setting the tempo</summary>

Use the <a href="https://en.scratch-wiki.info/wiki/Set_Tempo_to_()_(block)">Set tempo</a> block to set the tempo from a variable.
</details>
<details>
<summary>Hint 2: Setting the metronome volume</summary>

Put the blocks for playing the note in the "stage", rather than in a sprite, and use the <a href="https://en.scratch-wiki.info/wiki/Set_Volume_to_()%25_(block)">Set volume</a> block to lower the volume. This block only sets the volume for the sprite/stage it is in, so other sounds will still play at full volume.
</details>
<br>

<img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper"><img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper"><img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper"><img src="/assets/images/pepper.svg" alt="pepper" class="inline-pepper">
* Everything from the 1 pepper version
* Include a "record" function:
  * Press a button to start recording
  * Play notes
  * Press a button to stop recording
  * Press another button to play back your song

Note that your recording only needs to play back the sequence of notes, not the timing of them. For example, if the recording user plays: "A C D ... [waits a few seconds] F", the recording would play "A C D F" (without the pause).

<details>
<summary>Hint 1: Storing the song</summary>
Use a <a href="https://en.scratch-wiki.info/wiki/Scratch_Wiki:Table_of_Contents/List_Blocks">List</a> to record the list of notes played.
</details>

<details>
<summary>Hint 2: Song representation</summary>
You will need to record a list of words that represent the song. When playing back the song, you will need to go through each item in the list, and use a series of <a href="https://en.scratch-wiki.info/wiki/If_()_Then_(block)">if/then</a> blocks to decide which note to play based on the value of the word.
</details>

<details>
<summary>Hint 3: Looping</summary>
<a href="https://scratch.mit.edu/discuss/topic/26012/?page=1#post-231388">This post</a> shows one way to loop over every item in a list.
</details>

{% include scratch_submission.md %}
{% include scratch_resources.md %}

