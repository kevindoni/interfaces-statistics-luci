# luci-app-interfaces-statistics
Network interfaces statistics for LuCI (OpenWrt webUI).

OpenWrt >= 19.07.

**Installation notes:**

    wget --no-check-certificate -O /tmp/luci-app-interfaces-statistics_0.3-3_all.ipk https://raw.githubusercontent.com/kevindoni/interfaces-statistics-luci/main/packages/19.07/luci-app-interfaces-statistics_0.3-3_all.ipk
    opkg install /tmp/luci-app-interfaces-statistics_0.3-3_all.ipk
    rm /tmp/luci-app-interfaces-statistics_0.3-3_all.ipk
    /etc/init.d/rpcd restart

**i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-interfaces-statistics-ru_0.3-3_all.ipk https://raw.githubusercontent.com/kevindoni/interfaces-statistics-luci/main/packages/19.07/luci-i18n-interfaces-statistics-ru_0.3-3_all.ipk
    opkg install /tmp/luci-i18n-interfaces-statistics-ru_0.3-3_all.ipk
    rm /tmp/luci-i18n-interfaces-statistics-ru_0.3-3_all.ipk

**Screenshots:**

![](https://github.com/kevindoni/interfaces-statistics-luci/blob/main/screenshots/interface.png)
