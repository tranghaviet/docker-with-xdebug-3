# Config Xdebug 3 on Docker (Nginx + PHP FPM)

First step: add `127.0.0.1 phpinfo.local` to you `hosts`

## PHPSTORM

In Languages & Frameworks > PHP > Debug:
- External connections: uncheck all
- Xdebug:
  + Debug port: 9003. Check: Can except external connections
  + Check all
  
Click **Start Listen** and add a breakpoint

When you access http://phpinfo.local at the first time the PHPStorm will promote a dialog to except connection just click accept. After that PHPStorm save a server with the path mapping at Languages & Frameworks > PHP > Servers

## VS Code

Install PHP Debug

## Ref

https://matthewsetter.com/setup-step-debugging-php-xdebug3-docker/
