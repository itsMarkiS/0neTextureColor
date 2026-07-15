# ONE TEXTURE COLOR (example pack)
**CHECK THE GALLERY!! Everything works using only a few textures
btw, the textures are really ugly and rushed because this is purely an example pack for those who want to experiment with it, many things can be done with this and i havent seen no one making it**

This is a EXAMPLE Resource pack made really quick for the transmute palette function for [Atlases](https://minecraft.wiki/w/Atlas) in minecraft

### This feature allow you to add textures in one singlecolor, so all blocks/items of this type uses the exact same texture (only one file) but applying different colors (in this pack, it is gray)
![ExampleBlocks](https://cdn.modrinth.com/data/cached_images/c7bbed27a52ee69c85e17ba8e75491559875f2d9.png)![ExampleItems](https://cdn.modrinth.com/data/cached_images/e28acba8c1f91c32b9f10d87d19ead26997e0215.png)


and all these textures will be "dyed" and applied to some specific blocks (in this pack, its terracotta, wool, concrete, concrete powder and beds)

To add more textures and blocks, you need to add the original texture to the item/block atlas depending on what it is
![Atlas](https://cdn.modrinth.com/data/cached_images/ed401ee93522f1271e89e3d0968cadda5bf315a4.png)
  Then, youll need to change the item/block model, just to change its texture to "item_color" or "block_color" the original texture will be the prefix and the color will be the suffix for example, in the image there is "block/concrete" so the "red_concrete.json" in "models/block" will have to look like this

![Red Concrete model file](https://cdn.modrinth.com/data/cached_images/377d5c8b2f500716a423a313ad1de9cdb4ca95db.png)

To control the colors, you have to add them in the atlas and a texture in the palette folder, the gray one used for the default textures is named "null.png" the others are vanilla colors. It is important that all the palette textures have the same resolution/amount of colors 

![Palettes added in atlas](https://cdn.modrinth.com/data/cached_images/9d0939f6f6831df510c214166bca045de8978355.png)
![Example Palettes in the pack](https://cdn.modrinth.com/data/cached_images/dc21481868cf04c8711366a6bdfe7ee4c3ef873d.png)


OBS: This pack also makes beds use the entity folder and the old format from before 26.3
Special thanks to @ioblackshaw [enchanted_games]
