## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSansShavian-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansShavian/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, canadian-aboriginal, math, old-permic, hebrew, duployan, syriac, coptic, todhri, malayalam, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>shavian</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Heiltsuk (Latn, 300 speakers), Ekpeye (Latn, 226,000 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Makaa (Latn, 221,000 speakers), Ma’di (Latn, 584,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mfumte (Latn, 79,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers), Dii (Latn, 71,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nzakara (Latn, 50,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Avokaya (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Ebira (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Yala (Latn, 200,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u1047C (U+1047C): X=290.0,Y=1.0 (should be at baseline 0?)

* u1047D (U+1047D): X=324.0,Y=1.0 (should be at baseline 0?)

* Aring (U+00C5): X=208.0,Y=773.0 (should be at cap-height 771?)

* Aring (U+00C5): X=373.0,Y=773.0 (should be at cap-height 771?)

* Aring (U+00C5): X=261.0,Y=773.0 (should be at cap-height 771?)

* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=447.0,Y=-1.0 (should be at baseline 0?)

* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

* c (U+0063): X=385.0,Y=537.5 (should be at x-height 536?)

* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?)

* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

* h (U+0068): X=173.0,Y=537.0 (should be at x-height 536?)

* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

* s (U+0073): X=343.5,Y=536.5 (should be at x-height 536?)

* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=11.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=102.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=346.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=442.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=685.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=775.0,Y=537.0 (should be at x-height 536?)

* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* u1047A (U+1047A) contains a short segment B&lt;&lt;180.0,307.0&gt;-&lt;180.0,313.0&gt;-&lt;179.5,319.5&gt;&gt;

* u1047A (U+1047A) contains a short segment B&lt;&lt;179.5,319.5&gt;-&lt;179.0,326.0&gt;-&lt;179.0,333.0&gt;&gt;

* u1047B (U+1047B) contains a short segment B&lt;&lt;179.0,203.0&gt;-&lt;179.0,210.0&gt;-&lt;179.5,216.5&gt;&gt;

* u1047B (U+1047B) contains a short segment B&lt;&lt;179.5,216.5&gt;-&lt;180.0,223.0&gt;-&lt;180.0,229.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wacute (U+1E82) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wcircumflex (U+0174) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wdieresis (U+1E84) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wgrave (U+1E80) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;613.0,293.0&gt;-&lt;612.0,275.0&gt;-&lt;612.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;612.0,267.5&gt;-&lt;612.0,260.0&gt;-&lt;612.0,257.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;382.0,412.0&gt;-&lt;382.0,399.0&gt;-&lt;388.5,388.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 8 | 117 | 6 | 119 | 0 | 
| 0% | 0% | 0% | 3% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
