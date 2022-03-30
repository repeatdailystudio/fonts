
“Grade” (`GRAD` in CSS) is an [axis](/glossary/axis_in_variable_fonts) found in some [variable fonts](/glossary/variable_fonts). Changing the [grade](/glossary/grade) of a style makes it lighter or heavier in typographic [color](/glossary/color) without changing the [type](/glossary/type)’s overall [width](width), inter-letter spacing, or [kerning](/glossary/kerning)—unlike altering [weight](/glossary/weight). This is achieved by varying [stroke](/glossary/stroke) thicknesses (or other forms). Unlike weight, grade can be altered without causing changes in line breaks or layout.

The [Google Fonts CSS v2 API ](https://developers.google.com/fonts/docs/css2) defines the axis as:

| Default: | Min: | Max: | Step: |
| --- | --- | --- | --- |
| 0 | -1000 | 1000 | 1 |

Negative grade makes the style lighter, while positive grade makes it heavier. The units are the same as in the weight (`wght`) axis.

<figure>

![Two side-by-side type specimens of the word “slightly”, each shown with a variable axis represented beneath as a horizontal slider. The first specimen, with the slider most of the way to the left to represent a negative value on the axis, shows more contrast. The second specimen, with the slider most of the way to the right to represent a positive value on the axis, shows less contrast.](images/thumbnail.svg)

</figure>

In line with the current CSS spec, all custom axes should be referenced in UPPERCASE (only the officially registered variable axes should appear in lowercase). Also, when using the Google Fonts API, the uppercase axes have to appear first in the URL.
