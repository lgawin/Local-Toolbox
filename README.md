# Set of tools used in daily work

* **IT Tools**: encoders - e.g. `Base64`, hasghing - `MD5`, `SHA-1`, and more..., uuid/ulid generators, various formatters and converters, QR code generator, Regex tester  and many, many more useful stuff
* **Wiki Docs** - for taking notes

Run docker compose stack
```shell
docker compose up -d
```

Make sure your `/etc/hosts` contains 
```
127.0.0.1       tools.local
127.0.0.1       wiki.local
```

If so, you can access tools via [`http://tools.local`](http://tools.local) and [`http://wiki.local`](http://wiki.local).