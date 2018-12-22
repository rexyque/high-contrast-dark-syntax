# high-contrast-dark-syntax theme

A High Contrast, fully WCAG AA compliant theme with black as the background.
This theme was designed with C# in mind as I do most of my work in that language.
If you use a different language and the theme doesn't work well for
that language, feel free to submit a pull request!

## WCAG

The Web Content Accessibility Guidelines (WCAG) define guidelines for the level
of color contrast required to make text legible to individuals with visual
impairments, among other things. The full content of the guidelines is available
at https://www.w3.org/TR/WCAG20/

The guidelines define two levels of color accessibility, AA and AAA. The AAA
standard is more demanding than the AA standard. All of the default colors used
in this theme meet the AAA standards on a black background. They also all meet
AAA standards against the default selected text background at large sizes (18+).
However, because there is currently no way to change the color of font when it
is selected in Atom, I had to settle for only AA compliance against the default
selected text background at smaller fonts.

## Special Thanks

Special thanks to Donielle Berg and Adrian Rapp for developing colorsafe.co, a
tool which made this project much, much easier. If you want to change colors,
I'd suggest using them to find WCAG AAA compliant colors quickly.

I also want to thank the Center for Persons with Disabilities at Utah State
University for creating another useful tool for quickly checking the contrast
ratio of two different colors, as well as whether the combination conforms to
WCAG guidelines or not. That tool is available at https://webaim.org/resources/contrastchecker/
