# RTOSKit

**Open source RTOS tools and libraries.**

RTOSKit builds the toolchain pieces you need for embedded and real-time development: a compiler toolchain, a small libc, and debugging support.

---

## Repositories

| Repository | Description | Language | License |
|------------|-------------|----------|---------|
| [rtoskit-gcc](https://github.com/rtoskit-org/rtoskit-gcc) | The RTOSKIT GCC with RTOSKIT Libc | Shell | MPL-2.0 |
| [rtoskit-libc](https://github.com/rtoskit-org/rtoskit-libc) | Small libc implementation for embedded systems | C++ | MPL-2.0 |
| [rtoskit-openocd](https://github.com/rtoskit-org/rtoskit-openocd) | Fork of OpenOCD for on-chip debugging and programming | C | GPL-2.0 (upstream) |

## Getting Started

```bash
# Clone the toolchain and libc
git clone https://github.com/rtoskit-org/rtoskit-gcc.git
git clone https://github.com/rtoskit-org/rtoskit-libc.git
```

See each repository's README for build and usage instructions.

## Contributing

Contributions are welcome.

1. Fork the repository you want to change
2. Create a feature branch (`git checkout -b feature/my-change`)
3. Commit your changes and open a pull request

Please open an issue first for larger changes so we can discuss the approach.

> **Note:** `rtoskit-openocd` is a fork of the read-only OpenOCD mirror. Patches for OpenOCD itself should go upstream at [openocd.org](https://openocd.org).

## License

Unless noted otherwise, RTOSKit projects are released under the [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/). Forked projects keep their upstream licenses.

## Contact

- Browse our repositories: [github.com/rtoskit-org](https://github.com/rtoskit-org)
- Report bugs or ask questions via the Issues tab of the relevant repository
