# Composer Docker Container
FROM zalari/composer:base
MAINTAINER Christian Ulbrich <christian.ulbrich@zalari.de>

ENV COMPOSER_VERSION master

# Install Composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

# Display version information
RUN composer --version
