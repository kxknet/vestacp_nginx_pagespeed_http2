# Description
Пересборка Nginx c модулем Google PageSpeed и http/2 для VestaCP.  
Перезаписывает шаблоны default.stpl and default.tpl.  
Ребилдит конфиг Nginx для всех ваших сайтов.
# Установка
    apt-get install sudo
    cd /usr/local/src/
    git clone https://github.com/kxknet/vestacp_nginx_pagespeed_http2.git
    cd vestacp_nginx_pagespeed_http2/
    chmod +x rebuild.sh
    sudo ./rebuild.sh
Ссылки
-----------
<https://vestacp.com/>  
<http://nginx.org/download/>  
<https://developers.google.com/speed/pagespeed/module/>  
<https://ddosov.net> 
