![](https://github.com/senselogic/SCURL/blob/master/LOGO/scurl.png)

# Scurl

URL scrambler.

## Description

Scurl makes the e-mail URLs a bit less bot-friendly by :
- encoding them in hexadecimal;
- encrypting them using an XOR mask based on a linear congruential generator.

## Sample

Plain URL:
```html
mailto:rick.deckard@nexus6.com
```

Encoded URL:
```html
&#x6d;&#x61;&#x69;&#x6c;&#x74;&#x6f;&#x3a;&#x72;&#x69;&#x63;&#x6b;&#x2e;&#x64;&#x65;&#x63;&#x6b;&#x61;&#x72;&#x64;&#x40;&#x6e;&#x65;&#x78;&#x75;&#x73;&#x36;&#x2e;&#x63;&#x6f;&#x6d;
```

Encrypted URL:
```html
&#x3b;&#xc0;&#xb5;&#xe3;&#x36;&#x2a;&#xda;&#xf9;&#x6f;&#x12;&#x67;&#xe9;&#x66;&#x28;&#xeb;&#x40;&#x4f;&#x4b;&#x90;&#xd7;&#x3c;&#xe0;&#x68;&#xd6;&#xf5;&#x37;&#x2a;&#x44;&#x25;&#x48;
```

## Version

1.0

## Author

Eric Pelzer (ecstatic.coder@gmail.com).

## License

This project is licensed under the GNU General Public License version 3.

See the [LICENSE.md](LICENSE.md) file for details.
