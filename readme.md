todo - make look good

adding emojis
- for creating a new category, make a new texture in the textures/font/emojis folder
- make sure emojis are 8x8, and laid out in some form of array/grid
- create a new json in the font folder, use the existing one(s) as an example
- change "file" to the new texture
- "chars" is laid out the same way as your emoji texture, use a comma for new rows, add a \uE~~~ for each emoji in the texture
- create a new json in the emojis folder, keyed with a corresponding \uE~~~ in the font file, with a list of aliases for that emoji

- for adding to an existing category, just add the images to an existing texture and add to the existing json files corresponding to the texture