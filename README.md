# Roundify (Firefox userChome & userContent)
A custom `userChrome.css` and `userContent.css` that rounds corners, and enables users to add a background to the default Firefox newtab page. This image is defined as `image.png` in the `/image` directory. I also enable use of a custom font in the Firefox UI. I use Poppins, which I will not distribute in this repository in respect to its creator, Indian Type Foundry. You may install any font you like within the `/fonts` directory, and you will need to edit `line 4` in `userChrome.css` and `line 6` in `userContent.css` accordingly.


**NOTE**: This userchrome.css is currently (partially) incompatible with the new sidebar tabs on Firefox, as the CSS selectors for both are the same.
