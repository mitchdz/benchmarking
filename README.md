# Benchmarking

for block devices, I am using the gnome disk utility to benchmark, with the default settings and write test.

I.E.
10MiB Sample Size
100 samples

Flashing ubuntu 20.04 with following command:
```
$ sudo dd if=ubuntu-20.04.1-desktop-amd64.iso of=/dev/sda bs=4M;sync
```
## USB devices

| Drive Name | Size | Read (MB/s)| Write (MB/s) | Time to dd Ubuntu20.04 (s) |
| --- | --- | --- | -- | -- |
| Patriot Memory Rage | 64GB | 172.5 | 8.1 | 120 |
| Samsung BAR Plus | 32GB | 85.8 | 34.9 | 137.742 |
| Kingston DTSE9 | 32GB | 42.4 | 9.0 | Not done|
| Corsair Voyager VEGA | 62GB | 95.0 | 13.3 | Not done|
| SanDisk Cruzer Glide (1.00) | 32GB | 21.1 | 5.9 | Not done|
