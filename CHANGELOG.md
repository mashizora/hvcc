CHANGELOG
=====

0.8.0
-----

* DPF: enumerated parameters
* DPF: special `__hv_dpf_bpm` receiver of transport BPM value
* Pdext: migrate to `pd-lib-builder` and newer `m_pd.h` and add some initial documentation.
* deprecated: Fabric generator - no longer supported
* docs: updates on missing objects and limitations
* bugfix: issues #24, #50, #100, #106

0.7.0
-----

* improvements: add type annotations to all methods; run mypy over the whole library
* DPF: basic UI generation using dpf-widgets (imgui + modgui)
* DPF: basic port groups support
* abstractions: use duplicate of delread4~.pd for vd~.pd
* deprecated: internal Bela implementation (use downstream instead)
* docs: add notes
* docs: fix markdown syntax
* bugfixes: issues #86, #87 and #93

0.6.3
-----

* add polytouchin and polytouchout
* add tests for midi input objects
* bugfixes for midi objects bendin, ctlin, notein, pgmin, pgmout, touchin

0.6.2
-----

* dpf: add CLAP to docs; cleanup templates
* dpf: bugfix -> wrong frame count used for sendMessageToReceiverV()
* general: style fixes
* general: py311 support
* general: un/supported objects

0.6.1
-----

* bugfix: missing parameter in named arguments
* update: json2daisy

0.6.0
-----

* aligned memory and freed patch instance
* js: WASM AudioWorklet
* js: deprecate asm.js
* dpf: configurable subpath
* midi: add stripnote
* deprecate max2hv
* documentation updates
* code cleanup
* tests: refactor and deprecate test_uploader

0.5.0
-----

* c2owl generator
* migrate @owl to @raw
* c2daisy json2daisy integration
* enable control and signal tests
* push f-string usage

0.4.0
-----

* Midi realtime messages
* Host transport to midi-rt
* Midi message scheduling improvements
* Bugfix: minimum midi channel
* Bugfix: windows console_script

0.3.0
-----

* Midi I/O extensions for DPF
* Midi bugfixes for [notein], [pgmin], [touchin], [bendin], [midiin]
* Midi bugfixes for [noteout], [pgmout], [touchout], [bendout], [midiout]
* Midi docs update
* DPF minimal Midi examples

0.2.0
-----

* metadata json for generator config
* add trig attribute type
* Daisy platform support
* DPF cleanup + meta + trig
* documentation update
* DPF makefiles + meaningful values + docs

0.1.2
-----

* bump versions for pypi

0.1.0
-----

* python3 package
* pep8 checks
* update docs
* bundle utils into executable package
* add bool attribute type
* improve pd search paths

0.0.1
-----

* python3 fixes
* replace VST2 with DPF builds

0.0.0
-----

* code dump by enzienaudio
