# images
## Edit rt PWA Extension Plugin File as below 
<img width="1470" alt="Screenshot 2024-02-09 at 10 47 17" src="https://github.com/uk2315/images/assets/158253330/0e881538-acea-4537-afdd-3c0de59fffb8">

```php

add_filter( 'rt_pwa_extensions_app_icon_72_72', 'update_icon_src1' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src1() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-72x72.png';
}
add_filter( 'rt_pwa_extensions_app_icon_96_96', 'update_icon_src2' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src2() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-96x96.png';
}
add_filter( 'rt_pwa_extensions_app_icon_128_128', 'update_icon_src3' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src3() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-128x128.png';
}
add_filter( 'rt_pwa_extensions_app_icon_144_144', 'update_icon_src4' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src4() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-144x144.png';
}
add_filter( 'rt_pwa_extensions_app_icon_152_152', 'update_icon_src5' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src5() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-152x152.png';
}
add_filter( 'rt_pwa_extensions_app_icon_192_192', 'update_icon_src6' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src6() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-192x192.png';
}
add_filter( 'rt_pwa_extensions_app_icon_384_384', 'update_icon_src7' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src7() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-384x384.png';
}

add_filter( 'rt_pwa_extensions_app_icon_512_512', 'update_icon_src8' );
/**
 * Updates icon src.
 *
 * @return string
 */
function update_icon_src8() {
	return 'https://raw.githubusercontent.com/uk2315/images/main/icon-512x512.png';
}
```
