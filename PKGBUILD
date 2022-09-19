# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-variety-config
pkgver=1
pkgrel=1
pkgdesc="Variety config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('variety')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/variety/"
    install -Dm 644 "variety.conf" "${pkgdir}/etc/skel/.config/variety/variety.conf"
}

