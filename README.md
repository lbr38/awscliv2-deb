Automated DEB build for awscliv2 https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Builds are available in the Releases section.

Or install the package from a `deb` repository:

For `Debian 10`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/buster/main_prod buster main" > /etc/apt/sources.list.d/awscliv2.list
```

For `Debian 11`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/bullseye/main_prod bullseye main" > /etc/apt/sources.list.d/awscliv2.list
```

For `Debian 12`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/bookworm/main_prod bookworm main" > /etc/apt/sources.list.d/awscliv2.list
```

For `Ubuntu 20.04`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/focal/main_prod focal main" > /etc/apt/sources.list.d/awscliv2.list
```

For `Ubuntu 21.04`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/hirsute/main_prod hirsute main" > /etc/apt/sources.list.d/awscliv2.list
```

For `Ubuntu 22.04`:

```bash
curl -sS https://packages.bespin.ovh/repo/gpgkeys/packages.bespin.ovh.pub | gpg --dearmor > /etc/apt/trusted.gpg.d/packages.bespin.ovh.gpg
echo "deb https://packages.bespin.ovh/repo/awscliv2/jammy/main_prod jammy main" > /etc/apt/sources.list.d/awscliv2.list
```