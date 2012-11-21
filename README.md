egrid
=====

egrid is a minimal SASS base grid based on foundation and skeleton.

It contains all the percentage goodness from Foundation combined with the simplicity of Skeleton with an on/off switch for a responsive or non-responsive grid.

The settings file includes the most common settings for the grid and allow flexibility. Below a description.


Change to false to disable the responsiveness of the grid

    $responsive: true;

The default margin and padding of the document as well as the color of the body background

    $body-margin: 10px;
    $body-padding: 10px;
    $body-background-color: white;

The width and gutter width of the grid

    $width: 960px;
    $columnpadding: 5px;

Default typography    

    $fontfamily: "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    $fontsize: 14px;
    $line-height: 20px;

  
Default colors for the text and anchors

    $color: #333;
    $a-color: #CC0000;
    $a-hover: $a-color;

Settings for the headers, the header sizes for h1 to h6 will be calculated based on the base header size. 

    $base-header-size: 40px;
    $header-color: black;
    $header-fontfamily: $fontfamily;

Form settings, these are basically variables for the originale Skeleton form styles

    $inputshadow: #333;
    $inputshadow-alpha: 0.5;
    $inputborder-color: #ccc;
    $input-color: $color;
    