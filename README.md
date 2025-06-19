
docker build -t dockerfile.python -f Dockerfile.python .  #Собрать образ из файла

docker run --rm dockerfile.python  № Запустить собраный образ



docker tag dockerfile.python cr.yandex/crpd88n3hgkffu717vb1/dockerfile.pythen:ter-itog



docker push cr.yandex/crpd88n3hgkffu717vb1/dockerfile.pythen:ter-itog
