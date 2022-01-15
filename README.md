<h1 id="nemo">nemo</h1>

<p>A vim theme inspired by the <a href="https://zambumon.github.io/projects/nautilus">Nautilus keycap set</a> by Zambumon. It depends on the value of `background` unlike the original one.</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr><td align="center"><strong>nemo-dark</strong></td><td align="center"><strong>nemo-light</strong></td></tr>
<tr>
<td><img src="/img/screenshot-nemo-dark.png" alt="screenshot of the nemo-dark vim theme" width="282" /></td>
<td align="center"><img src="/img/screenshot-nemo-light.png" alt="screenshot of the nemo-light vim theme" width="282" /></td>
</tr>
</table>

<blockquote>
  <p>pictured font: <a href="http://input.fontbureau.com/">Input Mono Narrow</a> (1.2x line spacing)</p>
</blockquote>

<h2 id="options">options</h2>

<p>You can tweak the following options by adding lines to your `vimrc’.</p>

<p>Disable highlighted <strong>current line number</strong>:</p>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>let g:nemoCursorLineNr = 'off'
let g:nemoCursorLineNr = 'off'
</code></pre></div></div>

<p>Disable the highlighted <strong>line number background</strong>:</p>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>let g:nemoLineNr = 'off'
let g:nemoLineNr = 'off'
</code></pre></div></div>

<h2 id="palette">palette</h2>

<p>nemo consists of 8 theme-distinct <strong>base colours</strong>, which are used for most interface elements, and 8 standard <strong>accent colours</strong> (common to the “haystackandroid theme family”) used for syntax highlighting.</p>

<blockquote>
  <ul>
    <li><strong>hues</strong> were selected at the scale of 1/48 (7.5°) colour wheel intervals</li>
    <li><strong>saturations</strong> and <strong>values</strong> were selected at the scale of 1/24 (4.17%)</li>
    <li>the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">ISO 3:1 contrast standard</a> is met by nearly all text/background combinations, exceptions being made for some transient-highlighted backgrounds (e.g. cursorcolumn, cursorline)</li>
  </ul>
</blockquote>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light accents</th>
      <th style="text-align: left">dark accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/1d1d2b.png" height="24" width="42" /> <code class="highlighter-rouge">1d1d2b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/f55050.png" height="24" width="42" /> <code class="highlighter-rouge">f55050</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/bf5858.png" height="24" width="42" /> <code class="highlighter-rouge">bf5858</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/2c2c3b.png" height="24" width="42" /> <code class="highlighter-rouge">2c2c3b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e06a26.png" height="24" width="42" /> <code class="highlighter-rouge">e06a26</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/b56f45.png" height="24" width="42" /> <code class="highlighter-rouge">b56f45</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/616175.png" height="24" width="42" /> <code class="highlighter-rouge">616175</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d4ac35.png" height="24" width="42" /> <code class="highlighter-rouge">d4ac35</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ab8e38.png" height="24" width="42" /> <code class="highlighter-rouge">ab8e38</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/77778a.png" height="24" width="42" /> <code class="highlighter-rouge">77778a</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/219e21.png" height="24" width="42" /> <code class="highlighter-rouge">219e21</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/508a50.png" height="24" width="42" /> <code class="highlighter-rouge">508a50</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/8b8b9e.png" height="24" width="42" /> <code class="highlighter-rouge">8b8b9e</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/1b9e9e.png" height="24" width="42" /> <code class="highlighter-rouge">1b9e9e</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/458a8a.png" height="24" width="42" /> <code class="highlighter-rouge">458a8a</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/a3a3b5.png" height="24" width="42" /> <code class="highlighter-rouge">a3a3b5</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/468dd4.png" height="24" width="42" /> <code class="highlighter-rouge">468dd4</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/557b9e.png" height="24" width="42" /> <code class="highlighter-rouge">557b9e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/ddddf0.png" height="24" width="42" /> <code class="highlighter-rouge">ddddf0</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/a26fbf.png" height="24" width="42" /> <code class="highlighter-rouge">a26fbf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/8b6a9e.png" height="24" width="42" /> <code class="highlighter-rouge">8b6a9e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/f0f0ff.png" height="24" width="42" /> <code class="highlighter-rouge">f0f0ff</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/d46a84.png" height="24" width="42" /> <code class="highlighter-rouge">d46a84</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ab6a7a.png" height="24" width="42" /> <code class="highlighter-rouge">ab6a7a</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/f55050.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/e06a26.png" height="24" width="42" />
<strong>Orange</strong>, the colour of fire, can be associated with the preliminary “warmup” phase of some activity; literally, this could be the heating-up of a hearth for forging, or a stove for cooking. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/d4ac35.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings, yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/219e21.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/1b9e9e.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as marking mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/468dd4.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/a26fbf.png" height="24" width="42" />
<strong>Purple</strong>, often associated with (historically) rare purple dyes produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/d46a84.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into life as one types their names.</p>


