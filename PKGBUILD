# Maintainer: Philipp Schmitt <philipp@schmitt.co>
# GitHub: https://github.com/pschmitt/aur-python2-socksipychain
pkgname=python2-socksipychain
_pkgname=SocksipyChain
pkgver=2.0.15b
pkgrel=1
pkgdesc='A Python SOCKS/HTTP Proxy module'
arch=('any')
url='http://pagekite.org'
license=('BSD')
depends=('python2')
makedepends=('python2-setuptools')
options=(!emptydirs)
source=("https://pagekite.net/pk/src/$_pkgname-$pkgver.tar.gz")
sha1sums=('646b45a9386aeab534168e251f984089b23261bd')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
