# Maintainer: Your Name <youremail@domain.com>
pkgname=potato
pkgver=4
pkgrel=1
pkgdesc="A pomodoro timer for the shell"
arch=('any')
url="https://github.com/Bladtman242/potato"
license=('MIT')
depends=('alsa-utils')
source=('potato.sh'
        'LICENSE')
md5sums=('6043a811d91b4c773f13182f9bf4a032'
         '1ddcbd2862764b43d75fb1e484bf8912')

package() {
	install -D $srcdir/potato.sh $pkgdir/usr/bin/$pkgname
	install -D -m644 LICENSE $pkgdir/usr/share/licenses/$pkgname/LICENSE
}
