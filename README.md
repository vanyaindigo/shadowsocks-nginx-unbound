# shadowsocks-nginx-unbound

main.conf - моя конфигурация DNS-резолвера Unbound.

root_hints - скрипт для обновления адресов корневых серверов.

hosts_update - скрипт для блокировки трекеров и рекламы по DNS.

hosts_update_custom - альтернативный скрипт для блокировки трекеров и рекламы по DNS. Позволяет использовать собственные списки myblacklist и mywhitelist. Для этого их необходимо предварительно сосздать в папке /etc/unbound/.

unbound - ротация логов unbound

default - файл для настройки сайта Nginx, если не настраивали Unbound, замените resolver на что-то другое

nginx.conf - основные настройки Nginx

sysctl.conf - настройки параметров Linux
