---
title:   Servidor Web Interno
isChild: true
anchor:  builtin_web_server
---

## Servidor Web Interno {#builtin_web_server_title}

Você pode notar um arquivo server.php no código do Laravel. O objetivo deste arquivp é permitir que você execute o projeto sem a necessidade de configurar um web server (ex: Apache ou Nginx) na sua máquina.
Este servidor é apenas para objetivos de desenvolvimento, e tem como requisito principal que a versão do seu PHP seja superior à 5.4. Você pode utilizá-lo usando um dos seguintes comandos:

{% highlight console %}
> php -S localhost:8000 server.php
{% endhighlight %}

ou simplesmente (O comando a seguir funciona **apenas** para Laravel `v4.x`):

{% highlight console %}
> php artisan serve
{% endhighlight %}

Você também pode especificar argumentos:

{% highlight console %}
> php artisan serve --port=8080 --host=local.dev
{% endhighlight %}
