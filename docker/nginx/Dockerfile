FROM php:5.6-cli
COPY . /usr/src/nds
WORKDIR /usr/src/nds
RUN php compose.phar install
CMD [ "php", 'app/console', "killerwolf:nds:googlenews" ]