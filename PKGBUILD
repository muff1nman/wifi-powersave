# Maintainer: Andrew DeMaria <lostonamountain AT gmail DOT com>
pkgname=wlan-powersave
pkgver=1
pkgrel=1
pkgdesc="Provides a simple udev rule to turn on power saving for wlan* adapters"
arch=('any')
url="https://github.com/muff1nman/wifi-powersave"
license=('GPL3')
groups=('powersaver-udev-rules')

package() {
	install -m644 70-wifi-powersave.rules ${pkgdir}/etc/udev/rules.d/70-wifi-powersave.rules
}
