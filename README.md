# Installation

## Add this to your composer.json file

```
{
  "repositories": [{
    "type": "composer",
    "url": "https://packages.pixney.com"
  }]
}
```

## Require the block 
`composer require pixney/title_block-extension`

## Dump 
`composer dump`

## Install block

`php artisan addon:install pixney.extension.title_block`

## Copy views
If you have used avviare to setup your theme, you can simply run the following command to copy the necessary view files over to your theme directory:

`pixney:publish pixney.extension.title_block`

If you haven't used avviare, simply copy the files within `resources/views/block` to your theme: 
`resources/blocks/title_block`
directory

 
