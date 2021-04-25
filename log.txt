# Warning !

+ Don't add theme package luci-theme-argon-lr 

It will cause an exception
Example above:

```

 * check_data_file_clashes: Package luci-theme-argon-lr wants to install file /workdir/openwrt/build_dir/target-x86_64_musl/root-x86/usr/lib/lua/luci/view/themes/argon/footer.htm
	But that file is already provided by package  * luci-theme-argon
 * check_data_file_clashes: Package luci-theme-argon-lr wants to install file /workdir/openwrt/build_dir/target-x86_64_musl/root-x86/usr/lib/lua/luci/view/themes/argon/header.htm
	But that file is already provided by package  * luci-theme-argon
 * check_data_file_clashes: Package luci-theme-argon-lr wants to install file /workdir/openwrt/build_dir/target-x86_64_musl/root-x86/www/luci-static/argon/favicon.ico
	But that file is already provided by package  * luci-theme-argon
 * check_data_file_clashes: Package luci-theme-argon-lr wants to install file /workdir/openwrt/build_dir/target-x86_64_musl/root-x86/www/luci-static/argon/js/jquery.min.js
	But that file is already provided by package  * luci-theme-argon
 * check_data_file_clashes: Package luci-theme-argon-lr wants to install file /workdir/openwrt/build_dir/target-x86_64_musl/root-x86/www/luci-static/argon/js/script.js
	But that file is already provided by package  * luci-theme-argon
 * opkg_install_cmd: Cannot install package luci-theme-argon-lr.

```
