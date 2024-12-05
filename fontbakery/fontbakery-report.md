## FontBakery report

fontbakery version: 0.12.9



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Triodion-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[18] Triodion-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.fontbakery.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.9, while a newer 0.12.10 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">uk_Cyrl (Ukrainian)</td>
<td align="left">Some base glyphs were missing: ʼ, ґ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">uk_Cyrl (Ukrainian)</td>
<td align="left">Some auxiliary glyphs were missing: ʼ, ґ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
acutecomb (U+0301), gravecomb (U+0300), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030F (U+030F), uni0311 (U+0311), uni033E (U+033E), uni0360 (U+0360), uni0483 (U+0483), uni0485 (U+0485), uni0486 (U+0486), uni0486.upper (U+E000), uni04860300 (U+E003), uni04860300.upper (U+E004), uni04860301 (U+E001), uni04860301.upper (U+E002), uni0487 (U+0487) and uniA675 (U+A675)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni034F (U+034F), uni0484 (U+0484), uni1DC0 (U+1DC0), uni1DC1 (U+1DC1), uniA66F (U+A66F) and uniA67D (U+A67D)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: .null	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: afii10070	Contours detected: 1	Expected: 2

- Glyph name: afii10076	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: afii10103	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni0484	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: .null	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni0484	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 887 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 453:
plus</p>
<p>Width = 611:
less</p>
<p>Width = 376:
equal</p>
<p>Width = 600:
greater</p>
<p>Width = 466:
logicalnot</p>
<p>Width = 579:
plusminus, divide, multiply</p>
<p>Width = 360:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Font has **proper** whitespace glyph names? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Glyph 0x00A0 is called &quot;nbspace&quot;: Change to &quot;uni00A0&quot;</p>
 [code: not-recommended-00a0]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Z (U+005A): L&lt;&lt;187.0,38.0&gt;--&lt;189.0,38.0&gt;&gt; -&gt; L&lt;&lt;189.0,38.0&gt;--&lt;382.0,42.0&gt;&gt;

* u1F543 (U+1F543): L&lt;&lt;627.0,195.0&gt;--&lt;628.0,143.0&gt;&gt; -&gt; L&lt;&lt;628.0,143.0&gt;--&lt;628.0,115.0&gt;&gt;

* u1F544 (U+1F544): L&lt;&lt;40.0,115.0&gt;--&lt;40.0,143.0&gt;&gt; -&gt; L&lt;&lt;40.0,143.0&gt;--&lt;41.0,195.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;318.0,356.0&gt;--&lt;305.0,351.0&gt;&gt; -&gt; L&lt;&lt;305.0,351.0&gt;--&lt;294.0,347.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;269.0,462.0&gt;--&lt;271.0,653.0&gt;&gt; -&gt; L&lt;&lt;271.0,653.0&gt;--&lt;271.0,659.0&gt;&gt;

* uni040E (U+040E): L&lt;&lt;292.0,41.0&gt;--&lt;298.0,155.0&gt;&gt; -&gt; L&lt;&lt;298.0,155.0&gt;--&lt;303.0,232.0&gt;&gt;

* uni040E (U+040E): L&lt;&lt;346.0,281.0&gt;--&lt;339.0,154.0&gt;&gt; -&gt; L&lt;&lt;339.0,154.0&gt;--&lt;333.0,41.0&gt;&gt;

* uni0423 (U+0423): L&lt;&lt;292.0,41.0&gt;--&lt;298.0,155.0&gt;&gt; -&gt; L&lt;&lt;298.0,155.0&gt;--&lt;303.0,232.0&gt;&gt;

* uni0423 (U+0423): L&lt;&lt;346.0,281.0&gt;--&lt;339.0,154.0&gt;&gt; -&gt; L&lt;&lt;339.0,154.0&gt;--&lt;333.0,41.0&gt;&gt;

* uni046A (U+046A): L&lt;&lt;404.0,443.0&gt;--&lt;254.0,624.0&gt;&gt; -&gt; L&lt;&lt;254.0,624.0&gt;--&lt;245.0,633.0&gt;&gt;

* uni203B (U+203B): L&lt;&lt;295.0,340.0&gt;--&lt;339.0,383.0&gt;&gt; -&gt; L&lt;&lt;339.0,383.0&gt;--&lt;382.0,425.0&gt;&gt;

* uni2DE6 (U+2DE6): L&lt;&lt;-300.0,521.0&gt;--&lt;-298.0,660.0&gt;&gt; -&gt; L&lt;&lt;-298.0,660.0&gt;--&lt;-296.0,755.0&gt;&gt;

* uni2DE6 (U+2DE6): L&lt;&lt;-90.0,730.0&gt;--&lt;-87.0,713.0&gt;&gt; -&gt; L&lt;&lt;-87.0,713.0&gt;--&lt;-86.0,708.0&gt;&gt;

* uni2DE60487 (U+F4E6): L&lt;&lt;-300.0,521.0&gt;--&lt;-298.0,660.0&gt;&gt; -&gt; L&lt;&lt;-298.0,660.0&gt;--&lt;-296.0,755.0&gt;&gt;

* uni2DE60487 (U+F4E6): L&lt;&lt;-90.0,730.0&gt;--&lt;-87.0,713.0&gt;&gt; -&gt; L&lt;&lt;-87.0,713.0&gt;--&lt;-86.0,708.0&gt;&gt;

* uni2DE8 (U+2DE8): L&lt;&lt;-81.0,793.0&gt;--&lt;-78.0,746.0&gt;&gt; -&gt; L&lt;&lt;-78.0,746.0&gt;--&lt;-70.0,632.0&gt;&gt;

* uni2DEE (U+2DEE): L&lt;&lt;-398.0,536.0&gt;--&lt;-398.0,618.0&gt;&gt; -&gt; L&lt;&lt;-398.0,618.0&gt;--&lt;-398.0,623.0&gt;&gt;

* uni2DF2 (U+2DF2): L&lt;&lt;-134.0,584.0&gt;--&lt;-134.0,570.0&gt;&gt; -&gt; L&lt;&lt;-134.0,570.0&gt;--&lt;-132.0,550.0&gt;&gt;

* uni2DF2 (U+2DF2): L&lt;&lt;-251.0,604.0&gt;--&lt;-250.0,582.0&gt;&gt; -&gt; L&lt;&lt;-250.0,582.0&gt;--&lt;-249.0,560.0&gt;&gt;

* uni2DF2 (U+2DF2): L&lt;&lt;-63.0,553.0&gt;--&lt;-64.0,573.0&gt;&gt; -&gt; L&lt;&lt;-64.0,573.0&gt;--&lt;-66.0,606.0&gt;&gt;

* uni2DF20487 (U+F4F2): L&lt;&lt;-134.0,584.0&gt;--&lt;-134.0,570.0&gt;&gt; -&gt; L&lt;&lt;-134.0,570.0&gt;--&lt;-132.0,550.0&gt;&gt;

* uni2DF20487 (U+F4F2): L&lt;&lt;-251.0,604.0&gt;--&lt;-250.0,582.0&gt;&gt; -&gt; L&lt;&lt;-250.0,582.0&gt;--&lt;-249.0,560.0&gt;&gt;

* uni2DF20487 (U+F4F2): L&lt;&lt;-63.0,553.0&gt;--&lt;-64.0,573.0&gt;&gt; -&gt; L&lt;&lt;-64.0,573.0&gt;--&lt;-66.0,606.0&gt;&gt;

* uni2DF3 (U+2DF3): L&lt;&lt;-252.0,653.0&gt;--&lt;-251.0,618.0&gt;&gt; -&gt; L&lt;&lt;-251.0,618.0&gt;--&lt;-250.0,598.0&gt;&gt;

* uni2DF3 (U+2DF3): L&lt;&lt;-81.0,592.0&gt;--&lt;-82.0,610.0&gt;&gt; -&gt; L&lt;&lt;-82.0,610.0&gt;--&lt;-84.0,655.0&gt;&gt;

* uni2DF30487 (U+F4F3): L&lt;&lt;-252.0,653.0&gt;--&lt;-251.0,618.0&gt;&gt; -&gt; L&lt;&lt;-251.0,618.0&gt;--&lt;-250.0,598.0&gt;&gt;

* uni2DF30487 (U+F4F3): L&lt;&lt;-81.0,592.0&gt;--&lt;-82.0,610.0&gt;&gt; -&gt; L&lt;&lt;-82.0,610.0&gt;--&lt;-84.0,655.0&gt;&gt;

* uni2DFD (U+2DFD): L&lt;&lt;-158.0,611.0&gt;--&lt;-158.0,573.0&gt;&gt; -&gt; L&lt;&lt;-158.0,573.0&gt;--&lt;-157.0,521.0&gt;&gt;

* uni2DFD0487 (U+F4FD): L&lt;&lt;-158.0,611.0&gt;--&lt;-158.0,573.0&gt;&gt; -&gt; L&lt;&lt;-158.0,573.0&gt;--&lt;-157.0,521.0&gt;&gt;

* uniA640 (U+A640): L&lt;&lt;107.0,685.0&gt;--&lt;165.0,681.0&gt;&gt; -&gt; L&lt;&lt;165.0,681.0&gt;--&lt;230.0,678.0&gt;&gt;

* uniA640 (U+A640): L&lt;&lt;149.0,288.0&gt;--&lt;248.0,391.0&gt;&gt; -&gt; L&lt;&lt;248.0,391.0&gt;--&lt;383.0,522.0&gt;&gt;

* uniA641 (U+A641): L&lt;&lt;107.0,470.0&gt;--&lt;165.0,467.0&gt;&gt; -&gt; L&lt;&lt;165.0,467.0&gt;--&lt;230.0,465.0&gt;&gt;

* uniA641 (U+A641): L&lt;&lt;165.0,467.0&gt;--&lt;230.0,465.0&gt;&gt; -&gt; L&lt;&lt;230.0,465.0&gt;--&lt;392.0,465.0&gt;&gt;

* uniA675 (U+A675): L&lt;&lt;-215.0,514.0&gt;--&lt;-243.0,620.0&gt;&gt; -&gt; L&lt;&lt;-243.0,620.0&gt;--&lt;-244.0,623.0&gt;&gt;

* uniA675 (U+A675): L&lt;&lt;-345.0,514.0&gt;--&lt;-369.0,620.0&gt;&gt; -&gt; L&lt;&lt;-369.0,620.0&gt;--&lt;-370.0,623.0&gt;&gt;

* uniE92B (U+E92B): L&lt;&lt;58.0,589.0&gt;--&lt;58.0,670.0&gt;&gt; -&gt; L&lt;&lt;58.0,670.0&gt;--&lt;58.0,676.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10017 (U+0410): B&lt;&lt;292.5,468.0&gt;-&lt;305.0,488.0&gt;-&lt;315.0,510.0&gt;&gt;/B&lt;&lt;315.0,510.0&gt;-&lt;304.0,496.0&gt;-&lt;290.0,482.5&gt;&gt; = 13.713271806952509

* u1F312 (U+1F312): B&lt;&lt;468.0,49.0&gt;-&lt;442.0,33.0&gt;-&lt;425.0,33.0&gt;&gt;/B&lt;&lt;425.0,33.0&gt;-&lt;432.0,32.0&gt;-&lt;435.0,32.0&gt;&gt; = 8.13010235415596

* u1F318 (U+1F318): B&lt;&lt;376.5,763.0&gt;-&lt;384.0,766.0&gt;-&lt;393.0,768.0&gt;&gt;/L&lt;&lt;393.0,768.0&gt;--&lt;379.0,768.0&gt;&gt; = 12.528807709151492

* u1F377 (U+1F377): B&lt;&lt;466.5,415.5&gt;-&lt;489.0,424.0&gt;-&lt;507.0,431.0&gt;&gt;/B&lt;&lt;507.0,431.0&gt;-&lt;499.0,430.0&gt;-&lt;487.5,430.0&gt;&gt; = 14.12548915823142

* u1F41F (U+1F41F): B&lt;&lt;516.0,308.0&gt;-&lt;543.0,314.0&gt;-&lt;730.0,332.0&gt;&gt;/B&lt;&lt;730.0,332.0&gt;-&lt;702.0,336.0&gt;-&lt;675.5,337.5&gt;&gt; = 13.62826507913694

* u1F41F (U+1F41F): L&lt;&lt;833.0,445.0&gt;--&lt;914.0,405.0&gt;&gt;/B&lt;&lt;914.0,405.0&gt;-&lt;900.0,416.0&gt;-&lt;900.0,434.0&gt;&gt; = 11.875815566048908

* uni263D (U+263D): B&lt;&lt;117.0,764.0&gt;-&lt;107.0,766.0&gt;-&lt;96.0,767.0&gt;&gt;/B&lt;&lt;96.0,767.0&gt;-&lt;110.0,763.0&gt;-&lt;128.5,749.0&gt;&gt; = 10.750966993188039

* uni263D (U+263D): B&lt;&lt;124.5,28.5&gt;-&lt;113.0,20.0&gt;-&lt;106.0,20.0&gt;&gt;/B&lt;&lt;106.0,20.0&gt;-&lt;113.0,19.0&gt;-&lt;116.0,18.5&gt;&gt; = 8.13010235415596

* uni263E (U+263E): B&lt;&lt;359.5,749.0&gt;-&lt;378.0,763.0&gt;-&lt;392.0,767.0&gt;&gt;/B&lt;&lt;392.0,767.0&gt;-&lt;382.0,766.0&gt;-&lt;372.0,764.0&gt;&gt; = 10.234802763423207

* uni263E (U+263E): B&lt;&lt;372.0,18.5&gt;-&lt;375.0,19.0&gt;-&lt;382.0,20.0&gt;&gt;/B&lt;&lt;382.0,20.0&gt;-&lt;376.0,20.0&gt;-&lt;364.0,28.5&gt;&gt; = 8.13010235415596

* uniA656 (U+A656): B&lt;&lt;505.0,411.0&gt;-&lt;522.0,426.0&gt;-&lt;535.0,436.0&gt;&gt;/B&lt;&lt;535.0,436.0&gt;-&lt;521.0,429.0&gt;-&lt;495.0,418.0&gt;&gt; = 11.003540851749474
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* N (U+004E): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* T (U+0054): L&lt;&lt;350.0,504.0&gt;--&lt;352.0,124.0&gt;&gt;

* e (U+0065): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* eacute (U+00E9): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* ecircumflex (U+00EA): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* edieresis (U+00EB): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* egrave (U+00E8): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;380.0,166.0&gt;--&lt;25.0,165.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;216.0,635.0&gt;--&lt;215.0,361.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;149.0,654.0&gt;--&lt;151.0,388.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;151.0,349.0&gt;--&lt;152.0,4.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;377.0,244.0&gt;--&lt;379.0,4.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;591.0,654.0&gt;--&lt;594.0,4.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;172.0,761.0&gt;--&lt;173.0,450.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;173.0,404.0&gt;--&lt;175.0,0.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;690.0,761.0&gt;--&lt;691.0,438.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;691.0,341.0&gt;--&lt;692.0,0.0&gt;&gt;

* uni0470 (U+0470): L&lt;&lt;380.0,40.0&gt;--&lt;379.0,782.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: j̀ j́ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ȉ ȋ i̾ i҃ i҄ i҅ i҆ i҇ i᷀ i᷁ iⷠ iⷡ iⷢ iⷣ iⷤ iⷥ iⷦ iⷧ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Mango (Latn, 77,000 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Gulay (Latn, 250,478 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Fur (Latn, 1,230,163 speakers), South Central Banda (Latn, 244,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Southern Kisi (Latn, 360,000 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Yala (Latn, 200,000 speakers), Basaa (Latn, 332,940 speakers), Vute (Latn, 21,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Bafut (Latn, 158,146 speakers), Bete-Bendi (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ekpeye (Latn, 226,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Nateni (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ngbaka (Latn, 1,020,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, canadian-aboriginal, syriac, coptic, math, tai-le, malayalam, old-permic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+10FB GEORGIAN PARAGRAPH SEPARATOR: try adding georgian</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, yi, myanmar, manichaean, tagbanwa, arabic, kharoshthi, hatran, khudawadi, sinhala, javanese, zanabazar-square, hebrew, buginese, malayalam, khojki, nko, gunjala-gondi, pahawh-hmong, thaana, tai-viet, mahajani, tifinagh, grantha, tagalog, kayah-li, psalter-pahlavi, khmer, limbu, newa, tai-le, kannada, batak, tamil, kaithi, siddham, hanifi-rohingya, sogdian, phags-pa, oriya, gurmukhi, chakma, syloti-nagri, bengali, devanagari, tibetan, buhid, masaram-gondi, tirhuta, hanunoo, takri, balinese, mongolian, sundanese, dogra, telugu, duployan, tai-tham, warang-citi, modi, new-tai-lue, lao, brahmi, rejang, cham, sharada, syriac, thai, mandaic, gujarati, saurashtra, lepcha, meetei-mayek, bhaiksuki</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, yi, myanmar, manichaean, tagbanwa, arabic, kharoshthi, khudawadi, sinhala, old-hungarian, javanese, zanabazar-square, hebrew, buginese, malayalam, khojki, nko, gunjala-gondi, pahawh-hmong, thaana, tai-viet, mahajani, tifinagh, grantha, tagalog, kayah-li, psalter-pahlavi, khmer, limbu, newa, tai-le, kannada, batak, tamil, kaithi, siddham, hanifi-rohingya, sogdian, phags-pa, oriya, gurmukhi, chakma, syloti-nagri, bengali, devanagari, tibetan, buhid, masaram-gondi, tirhuta, hanunoo, takri, balinese, mongolian, sundanese, dogra, telugu, duployan, tai-tham, warang-citi, modi, new-tai-lue, lao, brahmi, rejang, cham, sharada, syriac, thai, mandaic, gujarati, saurashtra, lepcha, meetei-mayek, bhaiksuki</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, phags-pa, arabic, syriac, hebrew, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, phags-pa, syriac, hebrew, nko</li>
<li>U+2010 HYPHEN: try adding one of: yi, sundanese, arabic, kharoshthi, kayah-li, lisu, cham, coptic, syloti-nagri, hebrew, armenian, kaithi, sora-sompeng</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: meroitic, old-hungarian</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, tai-tham, math, yi</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+2241 NOT TILDE: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: yi, khudawadi, sinhala, hebrew, malayalam, nko, gunjala-gondi, pahawh-hmong, thaana, tai-viet, psalter-pahlavi, soyombo, newa, hanifi-rohingya, oriya, chakma, marchen, hanunoo, balinese, duployan, tai-tham, warang-citi, syriac, sharada, thai, khojki, saurashtra, meetei-mayek, tagbanwa, zanabazar-square, adlam, wancho, elbasan, tifinagh, grantha, limbu, gurmukhi, syloti-nagri, devanagari, sundanese, mongolian, modi, new-tai-lue, rejang, brahmi, gujarati, kharoshthi, bassa-vah, mahajani, caucasian-albanian, miao, mende-kikakui, tamil, kaithi, sogdian, tibetan, coptic, tirhuta, buhid, masaram-gondi, takri, dogra, lao, ahom, mandaic, math, lepcha, tagalog, myanmar, manichaean, javanese, buginese, armenian, symbols, kayah-li, khmer, tai-le, kannada, batak, siddham, phags-pa, canadian-aboriginal, osage, bengali, music, telugu, cham, old-permic, bhaiksuki</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+263D FIRST QUARTER MOON: try adding symbols</li>
<li>U+263E LAST QUARTER MOON: try adding symbols</li>
<li>U+271A HEAVY GREEK CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2734 EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+29DF DOUBLE-ENDED MULTIMAP: try adding math</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E43 DASH WITH LEFT UPTURN: try adding glagolitic</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E0EC : not included in any glyphset definition</li>
<li>U+E2EA : not included in any glyphset definition</li>
<li>U+E3C0 : not included in any glyphset definition</li>
<li>U+E5D0 : not included in any glyphset definition</li>
<li>U+E5D1 : not included in any glyphset definition</li>
<li>U+E5D2 : not included in any glyphset definition</li>
<li>U+E5D3 : not included in any glyphset definition</li>
<li>U+E5D4 : not included in any glyphset definition</li>
<li>U+E5D5 : not included in any glyphset definition</li>
<li>U+E5D6 : not included in any glyphset definition</li>
<li>U+E8E1 : not included in any glyphset definition</li>
<li>U+E8E3 : not included in any glyphset definition</li>
<li>U+E8E5 : not included in any glyphset definition</li>
<li>U+E901 : not included in any glyphset definition</li>
<li>U+E903 : not included in any glyphset definition</li>
<li>U+E904 : not included in any glyphset definition</li>
<li>U+E92A : not included in any glyphset definition</li>
<li>U+E92B : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EE : not included in any glyphset definition</li>
<li>U+F4F0 : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+F4F3 : not included in any glyphset definition</li>
<li>U+F4FD : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB05 LATIN SMALL LIGATURE LONG S T: not included in any glyphset definition</li>
<li>U+1F311 NEW MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F312 WAXING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F313 FIRST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F314 WAXING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F315 FULL MOON SYMBOL: try adding symbols</li>
<li>U+1F316 WANING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F317 LAST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F318 WANING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F319 CRESCENT MOON: not included in any glyphset definition</li>
<li>U+1F347 GRAPES: not included in any glyphset definition</li>
<li>U+1F377 WINE GLASS: not included in any glyphset definition</li>
<li>U+1F41F FISH: try adding symbols</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
<li>U+F0023 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.637x (1637)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 16 | 119 | 7 | 107 | 0 | 
| 0% | 0% | 1% | 6% | 47% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
