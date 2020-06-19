# LightOpenId

This is a personal fork to incorporate the bare minimum patches to keep LightOpenId working in recent PHP versions until
I'm able to find a replacement for OpenID.

I do not maintain this library, nor should you. Please refer to the [parent
repository](https://github.com/Mewp/lightopenid) for further details. [OpenId](https://openid.net/) is dead, don't use it in new developments.

## Instalation

To download the files using [Composer](https://getcomposer.org/) you need to configure this fork as VCS repository in
your `composer.json` file:

    "repositories": {
        "lightopenid/lightopenid": {
            "type": "vcs",
            "url": "https://github.com/kAlvaro/lightopenid"
        }
    }

You will then be able to handle this copy of the library with exactly the same commands as the original, e.g.:     
    
    composer require lightopenid/lightopenid:dev-master
