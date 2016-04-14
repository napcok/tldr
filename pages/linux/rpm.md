# rpm

> Menedżer pakietów RPM.

- Pokaż wersję pakietu httpd:

`rpm -q {{httpd}}`

- Pokaż wersje wszystkich pasujących pakietów:

`rpm -qa '{{mariadb*}}'`

- Znajdź pakiet do którego należy plik i pokaż jego wersję:

`rpm -qf {{/etc/postfix/main.cf}}`

- Pokaż pliki należące do pakietu:

`rpm -ql {{kernel}}`

- Pokaż skrypty z pliku RPM:

`rpm -qp --scripts {{some.rpm}}`

- Pokaż zmienione, zagubione lub źle zainstalowane pliki z pasujących pakietów:

`rpm -Va '{{php-*}}'`
