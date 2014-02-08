# &lt;x-twitter-button&gt;

Web Component wrapper for Twitter Share button using Polymer.

> Maintained by [Tomomi Imura](https://github.com/yourname).

## Demo

> [Check it live](http://girliemac.github.io/x-twitter-button).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/x-twitter-button.html">
	```

3. Start using it!

	```html
	<x-twitter-button></x-twitter-button>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`lang`      | `en`, `fr`, `ar`, `de`, `ja`, `es`, `pt`, `ko`, `tr`, `ru`, `fil`, `zh-tw`, `zh-cn`, `hi`, `nl`, `sv`, `fi`, `pl`, `fa`, `he`, `ur`, `th`.                 | `en`               | Language
`count`      | `none`, `horizontal`, `vertical` 	   | `horizontal`               | Counter type
`size`   | `m`, `l`                     | `m`               | Button size
`tweetText`   | *string*                     | the title of the page               | Tweet text
`url`   | *string*                     | the URL of the page               | Share URL
`hashtag`   | *string*                     |                | Hashtag
`via`   | *string* (username)                   |                | "via @username"
`related`   | *string* (username)                    |                | Recommended
`dnt`   | *boolean*                     | `false`               |   Opt out tailored suggestions [?](https://support.twitter.com/articles/20169421)


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 Feb 7, 2014
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)