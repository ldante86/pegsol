<h2 id="program">PROGRAM</h2>
<p><strong>pegsol</strong> - a solitaire game.</p>
<h4 id="usage">USAGE</h4>
<p>pegsol [-flag] [peg hole]</p>
<h6 id="flags">FLAGS</h6>
<table>
<tbody>
<tr class="odd">
<td align="left">-h</td>
<td align="left">view this help and exit</td>
</tr>
<tr class="even">
<td align="left">-n</td>
<td align="left">disable status bar and score</td>
</tr>
<tr class="odd">
<td align="left">-t <em>p h</em></td>
<td align="left">set peg and hole tokens</td>
</tr>
</tbody>
</table>
<p>This is a very old solitaire game. Gameplay consists of jumping over pegs to eliminate them. The goal of the game is to clear the board of pegs, leaving one.</p>
<p>A default peg is a &quot;<strong>o</strong>&quot; A default hole is a &quot;<strong>.</strong>&quot;</p>
<p>The gameplay and appearance was inspired by a game called &quot;Le solitaire&quot; which can be found in the graphical emacs editor. The only difference is that, in the emacs version, the arrow keys are used.</p>
<p>To move a peg:</p>
<pre><code>        w
     a     d
        s</code></pre>
<p>To select a peg, press <strong>ENTER</strong> (or <strong>SPACE</strong>) and a message on the bottom will appear. To deselect it, press <strong>ENTER</strong> again the and the message will go away. Holes cannot be selected. Once a peg is selected, move in your desired direction, and if the destination is a hole and the jumped obstacle is a peg, then the destination will become your current position and the jumped peg will disappear.</p>
<p>To quit the game, press <strong>q</strong> or <strong>ctrl-c</strong>.</p>
