# YousList

Block filter for [Adblock Plus][], [uBlock][] and [1Blocker][].

[Adblock Plus]: https://adblockplus.org/
[uBlock]: https://github.com/chrisaljoudi/uBlock
[1Blocker]: http://1blocker.com/

## Usage

```
https://github.com/yous/YousList/raw/master/youslist.txt
```

### Adblock Plus

Install the browser plugin of Adblock Plus and add a subscription as 'YousList' with the above URL.

### uBlock

Install the browser plugin of uBlock and add a custom filter with the above URL.

### 1Blocker

Open [Rules.1blockpkg][] and select 1Blocker from the "Open In" menu.

[Rules.1blockpkg]: https://cdn.rawgit.com/yous/YousList/master/Rules.1blockpkg

## Testing

For the tests of your filter, make a temporary subscription served by your local machine by:

``` sh
ruby -run -ehttpd . -p8000
```

Add a filter using `http://localhost:8000/youslist.txt`.

## Contributing

New issues and pull requests are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for further details.

## License

Content of the YousList is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
