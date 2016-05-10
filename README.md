# prototype-cjdns-odroidc2

Prototype for cjdns on ODROID-C2 forming a mesh network

This project is similar to the [Raspberry Pi-based prototype](https://github.com/tomeshnet/prototype-cjdns-pi2) for a reference mesh node. We decided to explore the Hardkernel ODROID-C2 because of [encouraging CPU benchmark and Gigabit Ethernet support](http://www.hardkernel.com/main/products/prdt_info.php?g_code=G145457216438). This allows us to test the long-range directional gigabit link set up using a pair of [Ubiquiti LBE‑5AC‑23](https://www.ubnt.com/airmax/litebeam-ac/).

This is a more pricey set up, but will provide validation on a mesh formed by more performant nodes. It will also test [cjdns](https://github.com/hyperboria/cjdns) running on a 64-bit ARM processor. Benchmark results will be compared with the Raspberry Pi 2 and 3.

- [ ] [Install Arch Linux ARM](https://archlinuxarm.org/platforms/armv8/amlogic/odroid-c2) on the ODROID-C2
- [ ] Get cjdns running on the ODROID-C2
- [ ] [Connect a LBE‑5AC‑23](https://help.ubnt.com/hc/en-us/articles/205197750) to the ODROID-C2 gigabit ethernet port, then a second LBE‑5AC‑23 to another gigabit device, configure Ubiquiti AirOS on the LiteBeam to establish a point-to-point link, test for range and data rate
- [ ] Bind cjdns to the long-range point-to-point interface, note data rate at different distances
