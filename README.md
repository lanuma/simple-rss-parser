# RSS Parser Library - CodeIgniter 3
## Description
This is a simple implementation to get data from RSS Feed.

## Install
Simply copy `libraries` folder to your `application/libraries/` folder

## Usage
Afte you install this library correctly, you shloud be able to use.
```php
$config['url'] = '[RSS FEED URL]';
$config['limit'] = 20;
$this->load->library('rss_parser', $config);
$rss = $this->rss_parser->parse();
```
and you also can set url and set limit after load library
```php
$this->load->library('rss_parser', $config);
$this->rss_parser->setUrl('RSS FEED URL');
$this->rss_parser->setLimit(20);
$rss = $this->rss_parser->parse();
```
$rss variable will return rss element as array

## Contributing
Pull request welcome if you have idea or make this library more effective.
