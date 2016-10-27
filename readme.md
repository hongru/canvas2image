
# Canvas2image #
a tool of saving or converting canvas to images

## Demo ##
[canvas2image](https://superal.github.io/canvas2image/)

## Code ##
you can just use it like this  
filename is optional, default is Date.now()

    Canvas2Image.saveAsImage(canvasObj, width, height, type, fileName)
    Canvas2Image.saveAsPNG(canvasObj, width, height, fileName)
    Canvas2Image.saveAsJPEG(canvasObj, width, height, fileName)
    Canvas2Image.saveAsGIF(canvasObj, width, height, fileName)
    Canvas2Image.saveAsBMP(canvasObj, width, height, fileName)
    
    Canvas2Image.convertToImage(canvasObj, width, height, type)
    Canvas2Image.convertToPNG(canvasObj, width, height)
    Canvas2Image.convertToJPEG(canvasObj, width, height)
    Canvas2Image.convertToGIF(canvasObj, width, height)
    Canvas2Image.convertToBMP(canvasObj, width, height)
    
## License
MIT
