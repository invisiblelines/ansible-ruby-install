# Ruby Install

Installs Ruby Install and then installs any specified ruby versions

## Role Variables

    - ruby_install_version: 0.6.0
    - rubies:
        - ruby 2.3

## Example

    - hosts: app
      vars:
        ruby_install_rubies:
          - ruby: 2.3
      roles:
        ruby-install

## License

MIT
