# Francesco Tinelli

Software engineer based near Bari, Italy. I write C++, mostly on Windows
with Visual Studio; my own projects also build and run on Linux.

**Tools:** C++17, Visual Studio, CMake, CTest, Git, Linux

## SXE Core

[SXE Core](https://github.com/fratinelli09/SXE-Core) is a strategy execution
engine and backtester for crypto futures, written in C++17.

- Strategies are plugins (`.so`) built on a small SDK
- The simulation aims to be faithful to the exchange: price path inside each
  candle, taker and maker fees, slippage, funding, liquidation, limit orders
- A stopped simulation resumes from its saved state
- Tested with CTest against reference results
