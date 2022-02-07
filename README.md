# mql-zmq

ZMQ binding for the MQL language

Hi, it seems original contributors not updating original mql-zmq repo.

Our work depends heavily on this library, but we don't have to add new feature. For original manual please read README_orig.md. thanks to original contributors, it's a great manual.

We will be about to investigate new feature or newer libzmq version (like 4.3.x)

You must at least put https://github.com/kiwi0530/mql4-lib/ in MT4/Include/Mql (just like before) and make sure Mql/Lang folder exist for only for "This" fork to work


Major change from original
* Add header guard
* Move function implementation back to class, so cross compatible for both modern c++ compiler and bcc
* Escape #import so get more syntax compatibility
* Add mql/lang/mql4syntax.mqh so vscode c/c++ intellisense can completely work

We will NOT provide work for these issues
* New feature, excepts our projects need it
* Issue from original repository
* MQL5 related issue (sorry that our primary work only depends on MQL4)
* Build error for specific MT4 version, not latest

If you need these help, please file a issue
* Build error on latest MT4
* License issue ... etc, something not mentioned above
