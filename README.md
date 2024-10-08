# Маршрутизация через NAT-инстанс

В Yandex Cloud можно настроить связь нескольких ВМ с интернетом через NAT-инстанс с помощью [статической маршрутизации](https://yandex.cloud/ru/docs/vpc/concepts/routing#static). При этом будет использован только один публичный IP-адрес — тот, который присвоен NAT-инстансу.

В этом руководстве вы создадите тестовую ВМ и NAT-инстанс с помощью сервиса [Yandex Compute Cloud](https://yandex.cloud/ru/docs/compute/) и настроите маршрутизацию с помощью [Yandex Virtual Private Cloud](https://yandex.cloud/ru/docs/vpc/).

Подготовка инфраструктуры для маршрутизации через NAT-инстанс с помощью Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/routing/nat-instance), необходимые для настройки конфигурационные файлы `nat-instance.tf` и `nat-instance.auto.tfvars` расположены в этом репозитории.
