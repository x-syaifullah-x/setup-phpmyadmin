# SETUP PHPMYADMIN

### Install
- **Lighttpd**
    ```sh
    sudo apt install --no-install-suggests --no-install-recommends lighttpd phpmyadmin php8.4-cgi util-linux
    ```

- **Apache2**
    ```sh
    sudo apt install --no-install-suggests --no-install-recommends apache2 libapache2-mod-php phpmyadmin util-linux
    ```

### Run
```sh
open 127.0.0.1/phpmyadmin
```