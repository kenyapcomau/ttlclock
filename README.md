# TTL clock

These are the Kicad design files for the TTL clock described in my [Hackaday project](https://hackaday.io/project/168157-ttl-binary-clock)

## Versioning

First release November 2019

## Notes

Due to the 2 LS load fan out of the CD4060 (U8), you should use a 74LS50 (U12) and not a standard TTL package, otherwise the 1 Hz signal will be unreliable. Anyway non-LS parts are rare these days. LS is lower power consumption too.

## Authors

* **Ken Yap**

## License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
