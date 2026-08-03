# Maintainer: imitoy<imitoy@imitoy.top>

pkgname=aw88399-acf-firmware
pkgver=20260803
pkgrel=1
pkgdesc="Awinic AW88399 smart amplifier ACF DSP firmware (aw88399_acf.bin)"
arch=('x86_64')
url="https://github.com/imitoy/aw88399_acf-PKGBUILD"
license=('unknown')
depends=()
makedepends=()
source=(
	'https://github.com/imitoy/aw88399_acf.bin/releases/download/20260803/aw88399_acf.bin'
)
sha256sums=(
	'1e927c9bca76d868181c0f81df2bccef3cf19c7d0910219f229360c87babd42c'
)

package() {
  install -Dm644 "$srcdir/aw88399_acf.bin" "$pkgdir/usr/lib/firmware/aw88399_acf.bin"
}
