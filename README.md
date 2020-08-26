Generate playing cards from a grid, some input SVG paths and a configuration
file.

See more on this:

- [Some SVG cards][]
- [A card layout - in Perl][]


# Installing/Hacking

Use [Carton][] to install the modules using the `cpanfile`.

```shell
carton install --deployment
```

Run passing the configuration file as only command-line parameter:

```shell
perl -I local/lib/perl5 cardstom cardstom.json
```

# COPYRIGHT & LICENSE

Icons in directory `input/game-icons` are [CC BY 3.0][] from
[game-icons.net][]:

- [hearts][], [diamonds][], [clubs][], and [spades][] by
  [Skoll][game-icons.net]
- [hops][] and [corn] by [Delapouite][]
- [acorn][] by [Lorc][]

Numbers and letters are extracted from font [Some Time Later][], which has the
following copyright notice in the [license file][stl-license] as of this
writing:

> Copyright (c) 2016 Fredrick R Brennan <copypaste@kittens.ph>
> with Reserved Font Name "SOME TIME LATER".
>
> This Font Software is licensed under the SIL Open Font License, Version 1.1.

The rest of the contents of this repository are licensed according to the
Apache License 2.0 (see file `LICENSE` in the project's root directory):

>  Copyright 2020 by Flavio Poletti
>
>  Licensed under the Apache License, Version 2.0 (the "License");
>  you may not use this file except in compliance with the License.
>  You may obtain a copy of the License at
>
>      http://www.apache.org/licenses/LICENSE-2.0
>
>  Unless required by applicable law or agreed to in writing, software
>  distributed under the License is distributed on an "AS IS" BASIS,
>  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
>  See the License for the specific language governing permissions and
>  limitations under the License.
>
>  Dedicated to the loving memory of my mother.

[Carton]: https://metacpan.org/pod/Carton
[Some SVG cards]: https://github.polettix.it/ETOOBUSY/2020/08/26/some-cards/
[A card layout - in Perl]: https://github.polettix.it/ETOOBUSY/2020/08/25/perl-card-layout/
[game-icons.net]: https://game-icons.net/
[hearts]: https://game-icons.net/1x1/skoll/hearts.html
[diamonds]: https://game-icons.net/1x1/skoll/diamonds.html
[clubs]: https://game-icons.net/1x1/skoll/clubs.html
[spades]: https://game-icons.net/1x1/skoll/spades.html
[acorn]: https://game-icons.net/1x1/lorc/acorn.html
[corn]: https://game-icons.net/1x1/delapouite/corn.html
[hops]: https://game-icons.net/1x1/delapouite/hops.html
[Delapouite]: http://delapouite.com/
[Lorc]: http://lorcblog.blogspot.com/
[CC BY 3.0]: http://creativecommons.org/licenses/by/3.0/
[Some Time Later]: https://github.com/ctrlcctrlv/some-time-later
[stl-license]: https://github.com/ctrlcctrlv/some-time-later/blob/fc77428d35750bed919ad2a5b6ddbd8481b760a8/LICENSE.TXT
