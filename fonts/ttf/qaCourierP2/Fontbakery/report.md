## Fontbakery report

Fontbakery version: 0.7.11

<details>
<summary><b>[1] Family checks</b></summary>
<details>
<summary>⚠ <b>WARN:</b> Make sure all font files have the same version value.</summary>

* [com.google.fonts/check/family/equal_font_versions](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/head.html#com.google.fonts/check/family/equal_font_versions)
* ⚠ **WARN** Version info differs among font files of the same font project.
These were the version values found:
* CourierPrime-Bold.ttf: 3.01799
* CourierPrime-BoldItalic.ttf: 3.017
* CourierPrime-Italic.ttf: 3.017
* CourierPrime-Regular.ttf: 3.01799
 [code: mismatch]

</details>
<br>
</details>
<details>
<summary><b>[9] CourierPrime-Bold.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> License URL matches License text on name table?</summary>

* [com.google.fonts/check/name/license_url](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url)
* 🔥 **FAIL** A known license URL must be provided in the NameID 14 (LICENSE INFO URL) entry. Currently accepted licenses are Apache: 'http://www.apache.org/licenses/LICENSE-2.0' or Open Font License: 'http://scripts.sil.org/OFL'
For a small set of legacy families the Ubuntu Font License 'https://www.ubuntu.com/legal/terms-and-policies/font-licence' may be acceptable as well.
When in doubt, please choose OFL for new font projects. [code: no-license-found]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks.</summary>

* [com.google.fonts/check/name/line_breaks](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/line_breaks)
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform MACINTOSH contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)
* ⚠ **WARN** OS/2 VendorID value 'QUQA' is not a known registered id. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: unknown]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: Dcroat	Contours detected: 3	Expected: 2
Glyph name: summation	Contours detected: 3	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary>

* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)
* ⚠ **WARN** Font is monospaced but 4 glyphs (0.9638554216867471%) have a different width. You should check the widths of: ['nonmarkingreturn', 'fl', 'uni0326', 'uni0326.case'] [code: mono-outliers]

</details>
<details>
<summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'.</summary>

* [com.google.fonts/check/name/rfn](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/rfn)
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]

</details>
<details>
<summary>⚠ <b>WARN:</b> Monospace font has hhea.advanceWidthMax equal to each glyph's advanceWidth?</summary>

* [com.google.fonts/check/monospace_max_advancewidth](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/monospace_max_advancewidth)
* ⚠ **WARN** This seems to be a monospaced font, so advanceWidth value should be the same across all glyphs, but 99.28% of them have a different value: nonmarkingreturn, space, A, Aacute, Abreve, Acircumflex, Adieresis, Agrave, Amacron, Aogonek and 402 more. [code: should-be-monospaced]
* ⚠ **WARN** Double-width and/or zero-width glyphs were detected. These glyphs should be set to the same width as all others and then add GPOS single pos lookups that zeros/doubles the widths as needed: uni0326 and uni0326.case [code: variable-monospaced]

</details>
<details>
<summary>⚠ <b>WARN:</b> Does GPOS table have kerning information?</summary>

* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)
* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[9] CourierPrime-BoldItalic.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> License URL matches License text on name table?</summary>

* [com.google.fonts/check/name/license_url](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url)
* 🔥 **FAIL** A known license URL must be provided in the NameID 14 (LICENSE INFO URL) entry. Currently accepted licenses are Apache: 'http://www.apache.org/licenses/LICENSE-2.0' or Open Font License: 'http://scripts.sil.org/OFL'
For a small set of legacy families the Ubuntu Font License 'https://www.ubuntu.com/legal/terms-and-policies/font-licence' may be acceptable as well.
When in doubt, please choose OFL for new font projects. [code: no-license-found]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks.</summary>

* [com.google.fonts/check/name/line_breaks](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/line_breaks)
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform MACINTOSH contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)
* ⚠ **WARN** OS/2 VendorID value 'QUQA' is not a known registered id. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: unknown]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: Dcroat	Contours detected: 3	Expected: 2
Glyph name: summation	Contours detected: 3	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary>

* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)
* ⚠ **WARN** Font is monospaced but 5 glyphs (1.2048192771084338%) have a different width. You should check the widths of: ['nonmarkingreturn', 'fl', 'uni2215', 'uni0326', 'uni0326.case'] [code: mono-outliers]

</details>
<details>
<summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'.</summary>

* [com.google.fonts/check/name/rfn](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/rfn)
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]

</details>
<details>
<summary>⚠ <b>WARN:</b> Monospace font has hhea.advanceWidthMax equal to each glyph's advanceWidth?</summary>

* [com.google.fonts/check/monospace_max_advancewidth](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/monospace_max_advancewidth)
* ⚠ **WARN** This seems to be a monospaced font, so advanceWidth value should be the same across all glyphs, but 99.28% of them have a different value: nonmarkingreturn, space, A, Aacute, Abreve, Acircumflex, Adieresis, Agrave, Amacron, Aogonek and 402 more. [code: should-be-monospaced]
* ⚠ **WARN** Double-width and/or zero-width glyphs were detected. These glyphs should be set to the same width as all others and then add GPOS single pos lookups that zeros/doubles the widths as needed: uni0326 and uni0326.case [code: variable-monospaced]

</details>
<details>
<summary>⚠ <b>WARN:</b> Does GPOS table have kerning information?</summary>

* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)
* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[9] CourierPrime-Italic.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> License URL matches License text on name table?</summary>

* [com.google.fonts/check/name/license_url](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url)
* 🔥 **FAIL** A known license URL must be provided in the NameID 14 (LICENSE INFO URL) entry. Currently accepted licenses are Apache: 'http://www.apache.org/licenses/LICENSE-2.0' or Open Font License: 'http://scripts.sil.org/OFL'
For a small set of legacy families the Ubuntu Font License 'https://www.ubuntu.com/legal/terms-and-policies/font-licence' may be acceptable as well.
When in doubt, please choose OFL for new font projects. [code: no-license-found]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks.</summary>

* [com.google.fonts/check/name/line_breaks](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/line_breaks)
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform MACINTOSH contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)
* ⚠ **WARN** OS/2 VendorID value 'QUQA' is not a known registered id. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: unknown]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: Dcroat	Contours detected: 3	Expected: 2
Glyph name: summation	Contours detected: 3	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary>

* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)
* ⚠ **WARN** Font is monospaced but 4 glyphs (0.9638554216867471%) have a different width. You should check the widths of: ['nonmarkingreturn', 'fl', 'uni0326', 'uni0326.case'] [code: mono-outliers]

</details>
<details>
<summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'.</summary>

* [com.google.fonts/check/name/rfn](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/rfn)
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]

</details>
<details>
<summary>⚠ <b>WARN:</b> Monospace font has hhea.advanceWidthMax equal to each glyph's advanceWidth?</summary>

* [com.google.fonts/check/monospace_max_advancewidth](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/monospace_max_advancewidth)
* ⚠ **WARN** This seems to be a monospaced font, so advanceWidth value should be the same across all glyphs, but 99.28% of them have a different value: nonmarkingreturn, space, A, Aacute, Abreve, Acircumflex, Adieresis, Agrave, Amacron, Aogonek and 402 more. [code: should-be-monospaced]
* ⚠ **WARN** Double-width and/or zero-width glyphs were detected. These glyphs should be set to the same width as all others and then add GPOS single pos lookups that zeros/doubles the widths as needed: uni0326 and uni0326.case [code: variable-monospaced]

</details>
<details>
<summary>⚠ <b>WARN:</b> Does GPOS table have kerning information?</summary>

* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)
* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]

</details>
<br>
</details>
<details>
<summary><b>[9] CourierPrime-Regular.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> License URL matches License text on name table?</summary>

* [com.google.fonts/check/name/license_url](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url)
* 🔥 **FAIL** A known license URL must be provided in the NameID 14 (LICENSE INFO URL) entry. Currently accepted licenses are Apache: 'http://www.apache.org/licenses/LICENSE-2.0' or Open Font License: 'http://scripts.sil.org/OFL'
For a small set of legacy families the Ubuntu Font License 'https://www.ubuntu.com/legal/terms-and-policies/font-licence' may be acceptable as well.
When in doubt, please choose OFL for new font projects. [code: no-license-found]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks.</summary>

* [com.google.fonts/check/name/line_breaks](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/line_breaks)
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform MACINTOSH contains a line-break. [code: line-break]
* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/vendor_id](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id)
* ⚠ **WARN** OS/2 VendorID value 'QUQA' is not a known registered id. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: unknown]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (2048) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: Dcroat	Contours detected: 3	Expected: 2
Glyph name: summation	Contours detected: 3	Expected: 1 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata.</summary>

* [com.google.fonts/check/monospace](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/monospace)
* ⚠ **WARN** Font is monospaced but 5 glyphs (1.2048192771084338%) have a different width. You should check the widths of: ['nonmarkingreturn', 'fl', 'uni2215', 'uni0326', 'uni0326.case'] [code: mono-outliers]

</details>
<details>
<summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'.</summary>

* [com.google.fonts/check/name/rfn](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/rfn)
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]
* ⚠ **WARN** Name table entry ("Copyright (c) 2015
Quote-Unquote Apps (http://quoteunquoteapps.com)
with Reserved Font Name Courier Prime.

This Font Software is licensed under the SIL Open Font License
Version 1.1. This license is copied below
and is also available with a FAQ at: http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development of collaborative font projects
to support the font creation efforts of academic and linguistic communities
and to provide a free and open framework in which fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used
studied
modified and redistributed freely as long as they are not sold by themselves. The fonts
including any derivative works
can be bundled
embedded
redistributed and/or sold with any software provided that any reserved names are not used by derivative works. The fonts and derivatives
however
cannot be released under any other type of license. The requirement for fonts to remain under this license does not apply to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright Holder(s) under this license and clearly marked as such. This may include source files
build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the copyright statement(s).

"Original Version" refers to the collection of Font Software components as distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to
deleting
or substituting -- in part or in whole -- any of the components of the Original Version
by changing formats or by porting the Font Software to a new environment.

"Author" refers to any designer
engineer
programmer
technical writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted
free of charge
to any person obtaining a copy of the Font Software
to use
study
copy
merge
embed
modify
redistribute
and sell modified and unmodified copies of the Font Software
subject to the following conditions:

1) Neither the Font Software nor any of its individual components
in Original or Modified Versions
may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled
redistributed and/or sold with any software
provided that each copy contains the above copyright notice and this license. These can be included either as stand-alone text files
human-readable headers or in the appropriate machine-readable metadata fields within text or binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s) unless explicit written permission is granted by the corresponding Copyright Holder. This restriction only applies to the primary font name as presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software shall not be used to promote
endorse or advertise any Modified Version
except to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s) or with their explicit written permission.

5) The Font Software
modified or unmodified
in part or in whole
must be distributed entirely under this license
and must not be distributed under any other license. The requirement for fonts to remain under this license does not apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND
EXPRESS OR IMPLIED
INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT
PATENT
TRADEMARK
OR OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM
DAMAGES OR OTHER LIABILITY
INCLUDING ANY GENERAL
SPECIAL
INDIRECT
INCIDENTAL
OR CONSEQUENTIAL DAMAGES
WHETHER IN AN ACTION OF CONTRACT
TORT OR OTHERWISE
ARISING FROM
OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.") contains "Reserved Font Name". This is an error except in a few specific rare cases. [code: rfn]

</details>
<details>
<summary>⚠ <b>WARN:</b> Monospace font has hhea.advanceWidthMax equal to each glyph's advanceWidth?</summary>

* [com.google.fonts/check/monospace_max_advancewidth](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/monospace_max_advancewidth)
* ⚠ **WARN** This seems to be a monospaced font, so advanceWidth value should be the same across all glyphs, but 99.28% of them have a different value: nonmarkingreturn, space, A, Aacute, Abreve, Acircumflex, Adieresis, Agrave, Amacron, Aogonek and 402 more. [code: should-be-monospaced]
* ⚠ **WARN** Double-width and/or zero-width glyphs were detected. These glyphs should be set to the same width as all others and then add GPOS single pos lookups that zeros/doubles the widths as needed: uni0326 and uni0326.case [code: variable-monospaced]

</details>
<details>
<summary>⚠ <b>WARN:</b> Does GPOS table have kerning information?</summary>

* [com.google.fonts/check/gpos_kerning_info](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info)
* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]

</details>
<br>
</details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS |
|:-----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 29 | 243 | 25 | 251 |
| 0% | 1% | 5% | 44% | 4% | 45% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
