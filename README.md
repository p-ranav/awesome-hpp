<p align="center">
  <img height="70" src="img/logo.png"/>
</p>

<p align="center">
  <b>A curated list of awesome header-only C++ libraries</b>
</p>

<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://github.com/sindresorhus/awesome/blob/main/media/badge.svg">
</p>

## Table of Contents

- [Argument Parsers](#argument-parsers)
- [Audio](#audio)
- [Benchmarking](#benchmarking)
- [Communication](#communication)
- [Compression](#compression)
- [Concurrency](#concurrency)
- [Cryptography and Security](#cryptography-and-security)
- [Databases](#databases)
- [Data Formats](#data-formats)
- [Data Mining, Machine Learning, and Deep Learning](#data-mining-machine-learning-and-deep-learning)
- [Data Formatting and Presentation](#data-formatting-and-presentation)
- [Data Querying](#data-querying)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
- [Debugging](#debugging)
- [Deep Learning](#deep-learning)
- [Event Handling Mechanisms](#event-handling-mechanisms)
- [File System](#file-system)
- [Functional Programming](#functional-programming)
- [Geometry, Graphics Processing, and Game Development](#geometry-graphics-processing-and-game-development)
- [GPU](#gpu)
- [Graph](#graph)
- [GUI](#gui)
- [High-performance Computing](#high-performance-computing)
- [HTTP and the Web](#http-and-the-web)
- [Image Processing](#image-processing)
- [Language Bindings](#language-bindings)
- [Logging](#logging)
- [Mathematics](#mathematics)
- [Memory Management](#memory-management)
- [Mocking](#mocking)
- [Networking](#networking)
- [Optimization](#optimization)
- [Parsing Expression Grammars](#parsing-expression-grammars)
- [Portability Definitions](#portability-definitions)
- [Reflection](#reflection)
- [Regular Expression](#regular-expression)
- [Robotics](#robotics)
- [Serialization](#serialization)
- [SIMD](#simd)
- [Standard/Support Libraries](#standardsupport-libraries)
- [State Machine](#state-machine)
- [Statistics](#statistics)
- [String Utilities](#string-utilities)
- [Templating Engines](#templating-engines)
- [Terminal Utilities](#terminal-utilities)
- [Testing Frameworks](#testing-frameworks)
- [Units](#units)
- [Validation](#validation)
- [Web Frameworks](#web-frameworks)

## Argument Parsers

| Library  | Stars |  Description | License |
|--- | ---| ---|--- |
| [Argh!](https://github.com/adishavit/argh)  | [![GitHub stars](https://img.shields.io/github/stars/adishavit/argh?style=social)](https://github.com/adishavit/argh/stargazers/) | Argh! A minimalist argument handler.  | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [argparse](https://github.com/p-ranav/argparse) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/argparse?style=social)](https://github.com/p-ranav/argparse/stargazers/) | Argument Parser for Modern C++.  | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [args](https://github.com/Taywee/args) | [![GitHub stars](https://img.shields.io/github/stars/Taywee/args?style=social)](https://github.com/Taywee/args/stargazers/)  |  A simple header-only C++ argument parser library.  | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cmd_line_parser](https://github.com/jermp/cmd_line_parser) | [![GitHub stars](https://img.shields.io/github/stars/jermp/cmd_line_parser?style=social)](https://github.com/jermp/cmd_line_parser/stargazers/)  |  Command line parser for C++17.  | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [CLI11](https://github.com/CLIUtils/CLI11) | [![GitHub stars](https://img.shields.io/github/stars/CLIUtils/CLI11?style=social)](https://github.com/CLIUtils/CLI11/stargazers/) | CLI11 is a command line parser for C++11 and beyond. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [clipp](https://github.com/muellan/clipp) | [![GitHub stars](https://img.shields.io/github/stars/muellan/clipp?style=social)](https://github.com/muellan/clipp/stargazers/) | Powerful & Expressive Argument Parsing for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cxxopts](https://github.com/jarro2783/cxxopts) | [![GitHub stars](https://img.shields.io/github/stars/jarro2783/cxxopts?style=social)](https://github.com/jarro2783/cxxopts/stargazers/) | Lightweight C++ GNU style option parser library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [fire-hpp](https://github.com/kongaskristjan/fire-hpp) | [![GitHub stars](https://img.shields.io/github/stars/kongaskristjan/fire-hpp?style=social)](https://github.com/kongaskristjan/fire-hpp/stargazers/) | Create fully functional CLIs using function signatures. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [flags](https://github.com/sailormoon/flags) | [![GitHub stars](https://img.shields.io/github/stars/sailormoon/flags?style=social)](https://github.com/sailormoon/flags/stargazers/) | Simple, extensible, header-only C++17 argument parser. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [structopt](https://github.com/p-ranav/structopt) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/structopt?style=social)](https://github.com/p-ranav/structopt/stargazers/) | Parse command line arguments by defining a struct. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Audio

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [minimp3](https://github.com/lieff/minimp3) | [![GitHub stars](https://img.shields.io/github/stars/lieff/minimp3?style=social)](https://github.com/lieff/minimp3/stargazers/) | Minimalistic MP3 decoder single header library. | [![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/) |

## Benchmarking

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [criterion](https://github.com/p-ranav/criterion) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/criterion?style=social)](https://github.com/p-ranav/criterion/stargazers/) | Microbenchmarking for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [nanobench](https://github.com/martinus/nanobench) | [![GitHub stars](https://img.shields.io/github/stars/martinus/nanobench?style=social)](https://github.com/martinus/nanobench/stargazers/) | Simple, fast, accurate microbenchmarking for C++11. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [picobench](https://github.com/iboB/picobench) | [![GitHub stars](https://img.shields.io/github/stars/iboB/picobench?style=social)](https://github.com/iboB/picobench/stargazers/) | A small microbenchmarking library for C++11. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Communication
| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [comms](https://github.com/commschamp/comms_champion) | [![GitHub stars](https://img.shields.io/github/stars/commschamp/comms_champion?style=social)](https://github.com/commschamp/comms_champion/stargazers/) | Implement binary communication protocols in >=C++11. | [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0) |

## Compression

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [Gzip](https://github.com/mapbox/gzip-hpp) | [![GitHub stars](https://img.shields.io/github/stars/mapbox/gzip-hpp?style=social)](https://github.com/mapbox/gzip-hpp/stargazers/) | Gzip header-only C++ library. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [interpolative_coding](https://github.com/jermp/interpolative_coding) | [![GitHub stars](https://img.shields.io/github/stars/jermp/interpolative_coding?style=social)](https://github.com/jermp/interpolative_coding/stargazers/) | Binary Interpolative Coding algorithm. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [zstr](https://github.com/mateidavid/zstr) | [![GitHub stars](https://img.shields.io/github/stars/mateidavid/zstr?style=social)](https://github.com/mateidavid/zstr/stargazers/) | A C++ header-only ZLib wrapper. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Concurrency

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cs_libguarded](https://github.com/copperspice/cs_libguarded) | [![GitHub stars](https://img.shields.io/github/stars/copperspice/cs_libguarded?style=social)](https://github.com/copperspice/cs_libguarded/stargazers/) | Multithreaded programming. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [mvThreadPool](https://github.com/hoffstadt/mvThreadPool) | [![GitHub stars](https://img.shields.io/github/stars/hoffstadt/mvThreadPool?style=social)](https://github.com/hoffstadt/mvThreadPool/stargazers/) | Simple header-only C++ thread pool library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [taskflow](https://github.com/taskflow/taskflow) | [![GitHub stars](https://img.shields.io/github/stars/taskflow/taskflow?style=social)](https://github.com/taskflow/taskflow/stargazers/) | Modern C++ Parallel Task Programming. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [task_system](https://github.com/p-ranav/task_system) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/task_system?style=social)](https://github.com/p-ranav/task_system/stargazers/) | Better Code: Concurrency - Sean Parent. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [transwarp](https://github.com/bloomen/transwarp) | [![GitHub stars](https://img.shields.io/github/stars/bloomen/transwarp?style=social)](https://github.com/bloomen/transwarp/stargazers/) | A header-only C++ library for task concurrency. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [taskpool](https://github.com/fawdlstty/taskpool) | [![GitHub stars](https://img.shields.io/github/stars/fawdlstty/taskpool?style=social)](https://github.com/fawdlstty/taskpool/stargazers/) | Modern C++ taskpool. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Cryptography and Security

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cppcodec](https://github.com/tplgy/cppcodec) | [![GitHub stars](https://img.shields.io/github/stars/tplgy/cppcodec?style=social)](https://github.com/tplgy/cppcodec/stargazers/) | Encode/decode base64, base64url, base32, etc. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [digestpp](https://github.com/kerukuro/digestpp) | [![GitHub stars](https://img.shields.io/github/stars/kerukuro/digestpp?style=social)](https://github.com/kerukuro/digestpp/stargazers/) &nbsp; &nbsp; | C++11 header-only message digest library. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [PicoSHA2](https://github.com/okdshin/PicoSHA2) | [![GitHub stars](https://img.shields.io/github/stars/okdshin/PicoSHA2?style=social)](https://github.com/okdshin/PicoSHA2/stargazers/) | Header-file-only, SHA256 hash generator in C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [plusaes](https://github.com/kkAyataka/plusaes) | [![GitHub stars](https://img.shields.io/github/stars/kkAyataka/plusaes?style=social)](https://github.com/kkAyataka/plusaes/stargazers/) | Header only C++ AES cipher library. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Databases

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [OTL](http://otl.sourceforge.net/) | | Oracle, ODBC and DB2-CLI Template Library. | OpenBSD |

## Data Formats


| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [bencode](https://github.com/fbdtemme/bencode) | [![GitHub stars](https://img.shields.io/github/stars/fbdtemme/bencode?style=social)](https://github.com/fbdtemme/bencode/stargazers/) | C++20 bencode library. | [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Boost.JSON](https://github.com/CPPAlliance/json) | [![GitHub stars](https://img.shields.io/github/stars/CPPAlliance/json?style=social)](https://github.com/CPPAlliance/json/stargazers/) | JSON parsing, serialization, inspection and modification. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [cpptoml](https://github.com/skystrife/cpptoml) | [![GitHub stars](https://img.shields.io/github/stars/skystrife/cpptoml?style=social)](https://github.com/skystrife/cpptoml/stargazers/) | Header-only library for parsing TOML. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [csv2](https://github.com/p-ranav/csv2) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/csv2?style=social)](https://github.com/p-ranav/csv2/stargazers/) | Fast CSV parser and writer for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [CSV Parser](https://github.com/vincentlaucsb/csv-parser) | [![GitHub stars](https://img.shields.io/github/stars/vincentlaucsb/csv-parser?style=social)](https://github.com/vincentlaucsb/csv-parser/stargazers/) | Reading, writing, and analyzing CSV files. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [daw_json_link](https://github.com/beached/daw_json_link) | [![GitHub stars](https://img.shields.io/github/stars/beached/daw_json_link?style=social)](https://github.com/beached/daw_json_link/stargazers/) | Static JSON parsing in C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Fast C++ CSV Parser](https://github.com/ben-strasser/fast-cpp-csv-parser) | [![GitHub stars](https://img.shields.io/github/stars/ben-strasser/fast-cpp-csv-parser?style=social)](https://github.com/ben-strasser/fast-cpp-csv-parser/stargazers/) | Fast library for reading CSV files. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)  |
| [FlatJSON](https://github.com/nixman/flatjson) | [![GitHub stars](https://img.shields.io/github/stars/nixman/flatjson?style=social)](https://github.com/nixman/flatjson/stargazers/) | Extremely fast just one allocation and zero copy JSON parser. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [inih](https://github.com/jtilly/inih) | [![GitHub stars](https://img.shields.io/github/stars/jtilly/inih?style=social)](https://github.com/jtilly/inih/stargazers/) | This is a header only C++ version of inih. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [nlohmann/json](https://github.com/nlohmann/json) | [![GitHub stars](https://img.shields.io/github/stars/nlohmann/json?style=social)](https://github.com/nlohmann/json/stargazers/) | JSON for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [jsoncons](https://github.com/danielaparker/jsoncons) | [![GitHub stars](https://img.shields.io/github/stars/danielaparker/jsoncons?style=social)](https://github.com/danielaparker/jsoncons/stargazers/) | Construct JSON and JSON-like data formats. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [minicsv](https://github.com/shaovoon/minicsv) | [![GitHub stars](https://img.shields.io/github/stars/shaovoon/minicsv?style=social)](https://github.com/shaovoon/minicsv/stargazers/) | Bare minimal CSV stream based on C++ file streams. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [picojson](https://github.com/kazuho/picojson) | [![GitHub stars](https://img.shields.io/github/stars/kazuho/picojson?style=social)](https://github.com/kazuho/picojson/stargazers/) | a header-file-only, JSON parser serializer in C++. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [rapidcsv](https://github.com/d99kris/rapidcsv) | [![GitHub stars](https://img.shields.io/github/stars/d99kris/rapidcsv?style=social)](https://github.com/d99kris/rapidcsv/stargazers/) | C++ CSV parser library. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [rapidjson](https://github.com/Tencent/rapidjson) | [![GitHub stars](https://img.shields.io/github/stars/Tencent/rapidjson?style=social)](https://github.com/Tencent/rapidjson/stargazers/) | A fast JSON parser/generator for C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [rapidxml](https://github.com/dwd/rapidxml) | [![GitHub stars](https://img.shields.io/github/stars/dwd/rapidxml?style=social)](https://github.com/dwd/rapidxml/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | RapidXML fork; XML namespacing, per-element parsing, etc. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [simdjson](https://github.com/simdjson/simdjson) | [![GitHub stars](https://img.shields.io/github/stars/simdjson/simdjson?style=social)](https://github.com/simdjson/simdjson/stargazers/) | Parsing gigabytes of JSON per second. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [simpleini](https://github.com/brofield/simpleini) | [![GitHub stars](https://img.shields.io/github/stars/brofield/simpleini?style=social)](https://github.com/brofield/simpleini/stargazers/) | Read and write INI-style configuration files. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [taocpp JSON](https://github.com/taocpp/json) | [![GitHub stars](https://img.shields.io/github/stars/taocpp/json?style=social)](https://github.com/taocpp/json/stargazers/) | C++ header-only JSON library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [toml11](https://github.com/ToruNiina/toml11) | [![GitHub stars](https://img.shields.io/github/stars/ToruNiina/toml11?style=social)](https://github.com/ToruNiina/toml11/stargazers/) | TOML for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tomlplusplus](https://github.com/marzer/tomlplusplus) | [![GitHub stars](https://img.shields.io/github/stars/marzer/tomlplusplus?style=social)](https://github.com/marzer/tomlplusplus/stargazers/)  | TOML config file parser and serializer for >=C++17. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tortellini](https://github.com/Qix-/tortellini) | [![GitHub stars](https://img.shields.io/github/stars/Qix-/tortellini?style=social)](https://github.com/Qix-/tortellini/stargazers/) | A really stupid INI file format for C++11. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [valijson](https://github.com/tristanpenman/valijson) | [![GitHub stars](https://img.shields.io/github/stars/tristanpenman/valijson?style=social)](https://github.com/tristanpenman/valijson/stargazers/) | JSON Schema validation. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [xml2json](https://github.com/Cheedoong/xml2json) | [![GitHub stars](https://img.shields.io/github/stars/Cheedoong/xml2json?style=social)](https://github.com/Cheedoong/xml2json/stargazers/) | A header-only C++ library converts XML to JSON. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Data Mining, Machine Learning, and Deep Learning

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [dlib](http://dlib.net/) | [![GitHub stars](https://img.shields.io/github/stars/davisking/dlib?style=social)](https://github.com/davisking/dlib/stargazers/) | A toolkit for real-world machine learning and data analysis. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [frugally deep](https://github.com/Dobiasd/frugally-deep) | [![GitHub stars](https://img.shields.io/github/stars/Dobiasd/frugally-deep?style=social)](https://github.com/Dobiasd/frugally-deep/stargazers/) | Use Keras models in C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [hnswlib](https://github.com/nmslib/hnswlib) | [![GitHub stars](https://img.shields.io/github/stars/nmslib/hnswlib?style=social)](https://github.com/nmslib/hnswlib/stargazers/) | Fast approximate nearest neighbors. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [MiniDNN](https://github.com/yixuan/MiniDNN) | [![GitHub stars](https://img.shields.io/github/stars/yixuan/MiniDNN?style=social)](https://github.com/yixuan/MiniDNN/stargazers/) | A header-only C++ library for deep neural networks. | [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0) |
| [nanoflann](https://github.com/jlblancoc/nanoflann) | [![GitHub stars](https://img.shields.io/github/stars/jlblancoc/nanoflann?style=social)](https://github.com/jlblancoc/nanoflann/stargazers/) | Nearest Neighbor (NN) search with KD-trees. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) | [![GitHub stars](https://img.shields.io/github/stars/tiny-dnn/tiny-dnn?style=social)](https://github.com/tiny-dnn/tiny-dnn/stargazers/) | Dependency-free deep learning framework in C++14. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |

## Data Formatting and Presentation

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [asap](https://github.com/mobius3/asap) | [![GitHub stars](https://img.shields.io/github/stars/mobius3/asap?style=social)](https://github.com/mobius3/asap/stargazers/) | Creating, displaying, iterating and manipulating dates. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cxx prettyprint](https://github.com/louisdx/cxx-prettyprint) | [![GitHub stars](https://img.shields.io/github/stars/louisdx/cxx-prettyprint?style=social)](https://github.com/louisdx/cxx-prettyprint/stargazers/) | Pretty-printing of any container in C++(0x). | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [fmt](https://github.com/fmtlib/fmt) | [![GitHub stars](https://img.shields.io/github/stars/fmtlib/fmt?style=social)](https://github.com/fmtlib/fmt/stargazers/) | A modern formatting library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [pprint](https://github.com/p-ranav/pprint) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/pprint?style=social)](https://github.com/p-ranav/pprint/stargazers/) | Pretty Printer for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [strf](https://github.com/robhz786/strf) | [![GitHub stars](https://img.shields.io/github/stars/robhz786/strf?style=social)](https://github.com/robhz786/strf/stargazers/) | A fast formatting library for C++14. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [tabulate](https://github.com/p-ranav/tabulate) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/tabulate?style=social)](https://github.com/p-ranav/tabulate/stargazers/) | Table Maker for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Data Querying

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [boolinq](https://github.com/k06a/boolinq) | [![GitHub stars](https://img.shields.io/github/stars/louisdx/cxx-prettyprint?style=social)](https://github.com/louisdx/cxx-prettyprint/stargazers/) | Simplest C++ header-only LINQ template library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Data Structures and Algorithms

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [BitMagic](https://github.com/tlk00/BitMagic) | [![GitHub stars](https://img.shields.io/github/stars/tlk00/BitMagic?style=social)](https://github.com/tlk00/BitMagic/stargazers) | Compressed bit-vectors, logical operations, memory compact containers. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [concurrent queue](https://github.com/cameron314/concurrentqueue/) | [![GitHub stars](https://img.shields.io/github/stars/cameron314/concurrentqueue?style=social)](https://github.com/cameron314/concurrentqueue/stargazers/) | Fast multi-producer, multi-consumer lock-free concurrent queue. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [dynamic bitset](https://github.com/pinam45/dynamic_bitset) | [![GitHub stars](https://img.shields.io/github/stars/pinam45/dynamic_bitset?style=social)](https://github.com/pinam45/dynamic_bitset/stargazers/) | The C++17 header-only dynamic bitset. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [frozen](https://github.com/serge-sans-paille/frozen) | [![GitHub stars](https://img.shields.io/github/stars/serge-sans-paille/frozen?style=social)](https://github.com/serge-sans-paille/frozen/stargazers/) | Constexpr alternative to gperf for C++14 users. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [hopscotch map](https://github.com/Tessil/hopscotch-map) | [![GitHub stars](https://img.shields.io/github/stars/Tessil/hopscotch-map?style=social)](https://github.com/Tessil/hopscotch-map/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Fast hash map and hash set using hopscotch hashing. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [immer](https://github.com/arximboldi/immer) | [![GitHub stars](https://img.shields.io/github/stars/arximboldi/immer?style=social)](https://github.com/arximboldi/immer/stargazers/) | Postmodern immutable and persistent data structures. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [MPMCQueue](https://github.com/rigtorp/MPMCQueue) | [![GitHub stars](https://img.shields.io/github/stars/rigtorp/MPMCQueue?style=social)](https://github.com/rigtorp/MPMCQueue/stargazers/) | A bounded multi-producer multi-consumer concurrent queue. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [outcome](https://github.com/ned14/outcome) | [![GitHub stars](https://img.shields.io/github/stars/ned14/outcome?style=social)](https://github.com/ned14/outcome/stargazers/) | Lightweight outcome<T> and result<T>. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [parallel hashmap](https://github.com/greg7mdp/parallel-hashmap) | [![GitHub stars](https://img.shields.io/github/stars/greg7mdp/parallel-hashmap?style=social)](https://github.com/greg7mdp/parallel-hashmap/stargazers/) | Very fast and memory-friendly hashmap and btree containers. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [PGM-index](https://github.com/gvinciguerra/PGM-index) | [![GitHub stars](https://img.shields.io/github/stars/gvinciguerra/PGM-index?style=social)](https://github.com/gvinciguerra/PGM-index/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Blazing fast queries and updates over billions of items using orders of magnitude less memory than other containers. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [robin-hood hashing](https://github.com/martinus/robin-hood-hashing) | [![GitHub stars](https://img.shields.io/github/stars/martinus/robin-hood-hashing?style=social)](https://github.com/martinus/robin-hood-hashing/stargazers/) | Fast & memory efficient hashtable based on robin hood hashing. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [robin-map](https://github.com/Tessil/robin-map) | [![GitHub stars](https://img.shields.io/github/stars/Tessil/robin-map?style=social)](https://github.com/Tessil/robin-map/stargazers/) | Fast hash map and hash set using robin hood hashing. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
|[tries](https://github.com/gutjuri/tries) | [![GitHub stars](https://img.shields.io/github/stars/gutjuri/tries?style=social)](https://github.com/gutjuri/tries/stargazers/) | Fast and highly customisable C++20 trie implementation. | [![License: GPL-2.0](https://img.shields.io/badge/license-GPL%20(%3E%3D%202)-blue)](https://opensource.org/licenses/GPL-2.0)


## Debugging

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [backward-cpp](https://github.com/bombela/backward-cpp) | [![GitHub stars](https://img.shields.io/github/stars/bombela/backward-cpp?style=social)](https://github.com/bombela/backward-cpp/stargazers/) | A beautiful stack trace pretty printer for C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Deep Learning

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [ceras](https://github.com/fengwang/ceras) | [![GitHub stars](https://img.shields.io/github/stars/fengwang/ceras?style=social)](https://github.com/fengwang/ceras/stargazers/) | A deep learning engine in C++20. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |

## Event Handling Mechanisms

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [eventbus](https://github.com/DeveloperPaul123/eventbus) | [![GitHub stars](https://img.shields.io/github/stars/developerpaul123/eventbus?style=social)](https://github.com/developerpaul123/eventbus/stargazers/) | Mediator pattern event bus for C++. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [eventpp](https://github.com/wqking/eventpp) | [![GitHub stars](https://img.shields.io/github/stars/wqking/eventpp?style=social)](https://github.com/wqking/eventpp/stargazers/) | Event Dispatcher and callback list for C++. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [periodic-function](https://github.com/DeveloperPaul123/periodic-function) | [![Github Starts](https://img.shields.io/github/stars/developerpaul123/periodic-function?style=social)](https://github.com/developerpaul123/periodic-function/stargazers/) | Callbacks at a specified time interval. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## File System

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [simplebinstream](https://github.com/shaovoon/simplebinstream) | [![GitHub stars](https://img.shields.io/github/stars/shaovoon/simplebinstream?style=social)](https://github.com/shaovoon/simplebinstream/stargazers/) | C++ Simplistic Binary Stream. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [filesystem](https://github.com/gulrak/filesystem) | [![GitHub stars](https://img.shields.io/github/stars/gulrak/filesystem?style=social)](https://github.com/gulrak/filesystem/stargazers/) | Cross-platform implementation of std::filesystem for C++11/14/17. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [glob](https://github.com/p-ranav/glob) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/glob?style=social)](https://github.com/p-ranav/glob/stargazers/) | Glob for C++17. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [llfio](https://github.com/ned14/llfio) | [![GitHub stars](https://img.shields.io/github/stars/ned14/llfio?style=social)](https://github.com/ned14/llfio/stargazers/) | P1031 low-Level file i/o and filesystem library. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [mio](https://github.com/mandreyel/mio) | [![GitHub stars](https://img.shields.io/github/stars/mandreyel/mio?style=social)](https://github.com/mandreyel/mio/stargazers/) | Cross-platform C++11 memory mapped file IO. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [mm_file](https://github.com/jermp/mm_file) | [![GitHub stars](https://img.shields.io/github/stars/jermp/mm_file?style=social)](https://github.com/jermp/mm_file/stargazers/) | Memory-mapped files for C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tinydir](https://github.com/cxong/tinydir) | [![GitHub stars](https://img.shields.io/github/stars/cxong/tinydir?style=social)](https://github.com/cxong/tinydir/) &nbsp; &nbsp; &nbsp; | Lightweight, portable C directory and file reader. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |

## Functional Programming

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [FunctionalPlus](https://github.com/Dobiasd/FunctionalPlus) | [![GitHub stars](https://img.shields.io/github/stars/Dobiasd/FunctionalPlus?style=social)](https://github.com/Dobiasd/FunctionalPlus/stargazers/) | Functional Programming Library for C++. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [immer](https://github.com/arximboldi/immer) | [![GitHub stars](https://img.shields.io/github/stars/arximboldi/immer?style=social)](https://github.com/arximboldi/immer/stargazers/) | Persistent functional data structures in C++. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [lager](https://github.com/arximboldi/lager) | [![GitHub stars](https://img.shields.io/github/stars/arximboldi/lager?style=social)](https://github.com/arximboldi/lager/stargazers/) | Redux-like unidirectional data-flow for C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [schmutz](https://github.com/arximboldi/schmutz) | [![GitHub stars](https://img.shields.io/github/stars/jeremyong/Selene?style=social)](https://github.com/jeremyong/Selene/stargazers/) | Easy Guile Scheme C++ bindings. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [zug](https://github.com/arximboldi/zug) | [![GitHub stars](https://img.shields.io/github/stars/arximboldi/zug?style=social)](https://github.com/arximboldi/zug/stargazers/) | Transducers (from Clojure) in C++. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Geometry, Graphics Processing, and Game Development

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [arcball_camera](https://github.com/nlguillemot/arcball_camera) | [![GitHub stars](https://img.shields.io/github/stars/nlguillemot/arcball_camera?style=social)](https://github.com/nlguillemot/arcball_camera/stargazers/) | Immediate-mode camera for your graphics demos. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [cinolib](https://github.com/mlivesu/cinolib) | [![GitHub stars](https://img.shields.io/github/stars/mlivesu/cinolib?style=social)](https://github.com/mlivesu/cinolib/stargazers/) | Process polygonal and polyhedral meshes. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cr](https://github.com/fungos/cr) | [![GitHub stars](https://img.shields.io/github/stars/fungos/cr?style=social)](https://github.com/fungos/cr/stargazers/) | A Simple C Hot Reload Header-only Library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [CxxSwizzle](https://github.com/gwiazdorrr/CxxSwizzle) | [![GitHub stars](https://img.shields.io/github/stars/gwiazdorrr/CxxSwizzle?style=social)](https://github.com/gwiazdorrr/CxxSwizzle/stargazers/) | Modern C++ swizzling header-only library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [earcut.hpp](https://github.com/mapbox/earcut.hpp) | [![GitHub stars](https://img.shields.io/github/stars/mapbox/earcut.hpp?style=social)](https://github.com/mapbox/earcut.hpp/stargazers/) | Fast Polygon triangulation. | [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC) |
| [entt](https://github.com/skypjack/entt) | [![GitHub stars](https://img.shields.io/github/stars/skypjack/entt?style=social)](https://github.com/skypjack/entt/stargazers/) | Entity component system (ECS) and much more. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [glm](https://github.com/g-truc/glm) | [![GitHub stars](https://img.shields.io/github/stars/g-truc/glm?style=social)](https://github.com/g-truc/glm/stargazers/) | OpenGL Mathematics (GLM). | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [librg](https://github.com/zpl-c/librg) | [![GitHub stars](https://img.shields.io/github/stars/zpl-c/librg?style=social)](https://github.com/zpl-c/librg/stargazers/) | 🚀 Making multi-player gamedev simpler since 2017. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| [nanort](https://github.com/lighttransport/nanort) | [![GitHub stars](https://img.shields.io/github/stars/lighttransport/nanort?style=social)](https://github.com/lighttransport/nanort/stargazers/) | Modern ray tracing kernel. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [px](https://github.com/pplux/px) | [![GitHub stars](https://img.shields.io/github/stars/pplux/px?style=social)](https://github.com/pplux/px/stargazers/) | Thread Scheduling, Rendering, and so on. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Simple OpenGL Loader](https://github.com/tsherif/simple-opengl-loader) | [![GitHub stars](https://img.shields.io/github/stars/tsherif/simple-opengl-loader?style=social)](https://github.com/tsherif/simple-opengl-loader/stargazers/) | Extensible, cross-platform OpenGL loader. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Sokol](https://github.com/floooh/sokol) | [![GitHub stars](https://img.shields.io/github/stars/floooh/sokol?style=social)](https://github.com/floooh/sokol/stargazers/) | Cross-platform libraries for C and C++. | [![License: Zlib](https://img.shields.io/badge/License-Zlib-lightgrey.svg)](https://opensource.org/licenses/Zlib) |
| [stb](https://github.com/nothings/stb) | [![GitHub stars](https://img.shields.io/github/stars/nothings/stb?style=social)](https://github.com/nothings/stb/stargazers/) | Single-file public domain libraries. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Swarmz](https://github.com/Cultrarius/Swarmz) | [![GitHub stars](https://img.shields.io/github/stars/Cultrarius/Swarmz?style=social)](https://github.com/Cultrarius/Swarmz/stargazers/) | Swarming (flocking) library for real-time applications. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [tiny-differentiable-simulator](https://github.com/google-research/tiny-differentiable-simulator) | [![GitHub stars](https://img.shields.io/github/stars/google-research/tiny-differentiable-simulator?style=social)](https://github.com/google-research/tiny-differentiable-simulator/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Tiny Differentiable Simulator is a header-only C++ physics library with zero dependencies. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [tinygltf](https://github.com/syoyo/tinygltf) | [![GitHub stars](https://img.shields.io/github/stars/syoyo/tinygltf?style=social)](https://github.com/syoyo/tinygltf/stargazers/) | C++11 tiny glTF 2.0 library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tweeny](https://github.com/mobius3/tweeny) | [![GitHub stars](https://img.shields.io/github/stars/mobius3/tweeny?style=social)](https://github.com/mobius3/tweeny/stargazers/) | A modern C++ tweening library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [Vookoo](https://github.com/andy-thomason/Vookoo) | [![GitHub stars](https://img.shields.io/github/stars/andy-thomason/Vookoo?style=social)](https://github.com/andy-thomason/Vookoo/stargazers/) | Take the pain out of Vulkan. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [voxelizer](https://github.com/karimnaaji/voxelizer) | [![GitHub stars](https://img.shields.io/github/stars/karimnaaji/voxelizer?style=social)](https://github.com/karimnaaji/voxelizer/stargazers/) | Header only mesh voxelizer in c99. | |

## GPU

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [thrust](https://github.com/thrust/thrust) | [![GitHub stars](https://img.shields.io/github/stars/thrust/thrust?style=social)](https://github.com/thrust/thrust/stargazers/) | Parallel programming library. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| [vuda](https://github.com/jgbit/vuda) | [![GitHub stars](https://img.shields.io/github/stars/jgbit/vuda?style=social)](https://github.com/jgbit/vuda/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Vulkan-based library that provides a CUDA Runtime API interface for writing GPU-accelerated applications. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Graph

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [CXXGraph](https://github.com/ZigRazor/CXXGraph) | [![GitHub stars](https://img.shields.io/github/stars/ZigRazor/CXXGraph?style=social)](https://github.com/ZigRazor/CXXGraph/stargazers/) &nbsp; &nbsp; &nbsp; | Graph Representation and Algorithms Library >= C++17 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | [![License](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://opensource.org/licenses/AGPL-3.0) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |

## GUI

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [GuiLite](https://github.com/idea4good/GuiLite) | [![GitHub stars](https://img.shields.io/github/stars/idea4good/GuiLite?style=social)](https://github.com/idea4good/GuiLite/stargazers/) | The smallest header-only GUI library(5 KLOC) for all platforms. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) | [![GitHub stars](https://img.shields.io/github/stars/Immediate-Mode-UI/Nuklear?style=social)](https://github.com/Immediate-Mode-UI/Nuklear/stargazers/) | Immediate mode cross-platform GUI library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [WinLamb](https://github.com/rodrigocfd/winlamb) | [![GitHub stars](https://img.shields.io/github/stars/rodrigocfd/winlamb?style=social)](https://github.com/rodrigocfd/winlamb/stargazers/) | C++11 native Win32 GUI library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## High-performance Computing

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [MPL](https://github.com/rabauke/mpl) | [![GitHub stars](https://img.shields.io/github/stars/rabauke/mpl?style=social)](https://github.com/rabauke/mpl/) | A C++11 message passing library based on the [Message Passing Interface](https://www.mpi-forum.org/) standard. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |

## HTTP and the Web

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cinatra](https://github.com/qicosmos/cinatra) | [![GitHub stars](https://img.shields.io/github/stars/qicosmos/cinatra?style=social)](https://github.com/qicosmos/cinatra/stargazers/) | Modern (c++17), Cross-platform Http Framework. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cpp-httplib](https://github.com/yhirose/cpp-httplib) | [![GitHub stars](https://img.shields.io/github/stars/yhirose/cpp-httplib?style=social)](https://github.com/yhirose/cpp-httplib/stargazers/) | A C++11 Cross platform HTTP/HTTPS library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [jwt-cpp](https://github.com/Thalhammer/jwt-cpp) | [![GitHub stars](https://img.shields.io/github/stars/Thalhammer/jwt-cpp?style=social)](https://github.com/Thalhammer/jwt-cpp/stargazers/) | Create and validate JSON web tokens. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [RESTinio](https://github.com/Stiffstream/restinio) | [![GitHub stars](https://img.shields.io/github/stars/Stiffstream/restinio?style=social)](https://github.com/Stiffstream/restinio/stargazers/) | Asynchronous HTTP/WebSocket server C++14 library | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [cuehttp](https://github.com/xcyl/cuehttp) | [![GitHub stars](https://img.shields.io/github/stars/xcyl/cuehttp?style=social)](https://github.com/xcyl/cuehttp/stargazers/) | Modern c++ middleware framework for http(http/https)/websocket(ws/wss). | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |

## Image Processing

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [BitmapPlusPlus](https://github.com/BaderEddineOuaich/BitmapPlusPlus) | [![GitHub stars](https://img.shields.io/github/stars/BaderEddineOuaich/BitmapPlusPlus?style=social)](https://github.com/BaderEddineOuaich/BitmapPlusPlus/stargazers/) | Simple and Fast header only Bitmap (BMP) library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [CImg](https://github.com/dtschump/CImg) | [![GitHub stars](https://img.shields.io/github/stars/dtschump/CImg?style=social)](https://github.com/dtschump/CImg/stargazers/) | Cool Image, one file: full featured image processing. |  [![License: MIT](https://img.shields.io/badge/License-CeCILL-blue.svg)](http://cecill.info/licences/Licence_CeCILL_V2-en.html) |
| [color-util](https://github.com/yuki-koyama/color-util) | [![GitHub stars](https://img.shields.io/github/stars/yuki-koyama/color-util?style=social)](https://github.com/yuki-koyama/color-util/stargazers/) | Colors, Color space converters for RGB, HSL, XYZ, Lab, etc. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [color](https://github.com/dmilos/color) | [![GitHub stars](https://img.shields.io/github/stars/dmilos/color?style=social)](https://github.com/dmilos/color/stargazers/) | Color manipulation/conversion for different types and formats. | [![License: MIT](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [nanopm](https://github.com/unclearness/nanopm) | [![GitHub stars](https://img.shields.io/github/stars/unclearness/nanopm?style=social)](https://github.com/unclearness/nanopm/stargazers/) | NanoPM, single header only PatchMatch. | |

## Language Bindings

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [jni.hpp](https://github.com/mapbox/jni.hpp) | [![GitHub stars](https://img.shields.io/github/stars/mapbox/jni.hpp?style=social)](https://github.com/mapbox/jni.hpp/stargazers/) | A modern, type-safe, C++14 wrapper for JNI. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [pybind11](https://github.com/pybind/pybind11) | [![GitHub stars](https://img.shields.io/github/stars/pybind/pybind11?style=social)](https://github.com/pybind/pybind11/stargazers/) | Seamless operability between C++11 and Python. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [Selene](https://github.com/jeremyong/Selene) | [![GitHub stars](https://img.shields.io/github/stars/jeremyong/Selene?style=social)](https://github.com/jeremyong/Selene/stargazers/) | Simple C++11 friendly bindings to Lua. | [![License: Zlib](https://img.shields.io/badge/License-Zlib-lightgrey.svg)](https://opensource.org/licenses/Zlib) |
| [Sol](https://github.com/ThePhD/sol2) | [![GitHub stars](https://img.shields.io/github/stars/ThePhD/sol2?style=social)](https://github.com/ThePhD/sol2) | Sol3 (sol2 v3.0) - a C++ <-> Lua API wrapper with advanced features and top notch performance. | [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [v8pp](https://github.com/pmed/v8pp) | [![GitHub stars](https://img.shields.io/github/stars/pmed/v8pp?style=social)](https://github.com/pmed/v8pp/stargazers/) | Bind C++ functions and classes into V8 JavaScript engine. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Logging

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [easyloggingpp](https://github.com/amrayn/easyloggingpp) | [![GitHub stars](https://img.shields.io/github/stars/amrayn/easyloggingpp?style=social)](https://github.com/amrayn/easyloggingpp/stargazers/) | Single header C++ logging library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [plog](https://github.com/SergiusTheBest/plog) | [![GitHub stars](https://img.shields.io/github/stars/SergiusTheBest/plog?style=social)](https://github.com/SergiusTheBest/plog/stargazers/) | Portable, simple and extensible C++ logging library. | [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0) |
| [spdlog](https://github.com/gabime/spdlog) | [![GitHub stars](https://img.shields.io/github/stars/gabime/spdlog?style=social)](https://github.com/gabime/spdlog/stargazers/) | Fast C++ logging library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Mathematics

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [amgcl](https://github.com/ddemidov/amgcl) | [![GitHub stars](https://img.shields.io/github/stars/ddemidov/amgcl?style=social)](https://github.com/ddemidov/amgcl/stargazers/) | Solve large sparse linear systems with algebraic multigrid method. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [dj_fft](https://github.com/jdupuy/dj_fft) | [![GitHub stars](https://img.shields.io/github/stars/jdupuy/dj_fft?style=social)](https://github.com/jdupuy/dj_fft/stargazers/) | FFT library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [eigen](https://gitlab.com/libeigen/eigen) | | Template library for linear algebra. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| [exprtk](https://github.com/ArashPartow/exprtk) | [![GitHub stars](https://img.shields.io/github/stars/ArashPartow/exprtk?style=social)](https://github.com/ArashPartow/exprtk/stargazers/) | C++ Mathematical Expression Toolkit. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [fpm](https://github.com/MikeLankamp/fpm) | [![GitHub stars](https://img.shields.io/github/stars/MikeLankamp/fpm?style=social)](https://github.com/MikeLankamp/fpm/stargazers/) | Fixed-point math library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [kfr](https://github.com/kfrlib/kfr) | [![GitHub stars](https://img.shields.io/github/stars/kfrlib/kfr?style=social)](https://github.com/kfrlib/kfr/stargazers/) | Fast DSP framework, FFT, Sample Rate Conversion, etc. | [![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) |
| [libmorton](https://github.com/Forceflow/libmorton) | [![GitHub stars](https://img.shields.io/github/stars/Forceflow/libmorton?style=social)](https://github.com/Forceflow/libmorton/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Methods to efficiently encode/decode Morton codes in/from 2D/3D coordinates. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [linalg](https://github.com/sgorsten/linalg) | [![GitHub stars](https://img.shields.io/github/stars/sgorsten/linalg?style=social)](https://github.com/sgorsten/linalg/stargazers/) | Short vector math library for C++. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [matplotlib-cpp](https://github.com/lava/matplotlib-cpp) | [![GitHub stars](https://img.shields.io/github/stars/lava/matplotlib-cpp?style=social)](https://github.com/lava/matplotlib-cpp/stargazers/) | C++ plotting library built on the popular matplotlib. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [matrix](https://github.com/fengwang/matrix) | [![GitHub stars](https://img.shields.io/github/stars/fengwang/matrix?style=social)](https://github.com/fengwang/matrix/stargazers/) | A 2D matrix lib in C++20. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [NumCpp](https://github.com/dpilger26/NumCpp) | [![GitHub stars](https://img.shields.io/github/stars/dpilger26/NumCpp?style=social)](https://github.com/dpilger26/NumCpp/stargazers/) | C++ implementation of the Python Numpy library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [random](https://github.com/effolkronium/random) | [![GitHub stars](https://img.shields.io/github/stars/effolkronium/random?style=social)](https://github.com/effolkronium/random/stargazers/) | Random for modern C++ with convenient API. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [spectra](https://github.com/yixuan/spectra) | [![GitHub stars](https://img.shields.io/github/stars/yixuan/spectra?style=social)](https://github.com/yixuan/spectra/stargazers/) | A header-only C++ library for large scale eigenvalue problems. | [![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0) |
| [universal](https://github.com/stillwater-sc/universal) | [![GitHub stars](https://img.shields.io/github/stars/stillwater-sc/universal?style=social)](https://github.com/stillwater-sc/universal/stargazers/) | Universal Number Arithmetic. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Memory Management

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [ugc](https://github.com/bullno1/ugc) | [![GitHub stars](https://img.shields.io/github/stars/bullno1/ugc?style=social)](https://github.com/bullno1/ugc/stargazers/) | Incremental garbage collector. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |

## Mocking

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [FakeIt](https://github.com/eranpeer/FakeIt) | [![GitHub stars](https://img.shields.io/github/stars/eranpeer/FakeIt?style=social)](https://github.com/eranpeer/FakeIt/stargazers/) | C++ mocking made easy. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [trompeloeil](https://github.com/rollbear/trompeloeil) | [![GitHub stars](https://img.shields.io/github/stars/rollbear/trompeloeil?style=social)](https://github.com/rollbear/trompeloeil/stargazers/) | C++14 mocking framework. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Networking

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [asio](https://github.com/chriskohlhoff/asio) | [![GitHub stars](https://img.shields.io/github/stars/chriskohlhoff/asio?style=social)](https://github.com/chriskohlhoff/asio/stargazers/) | Asio C++ Library. | |
| [brynet](https://github.com/IronsDu/brynet) | [![GitHub stars](https://img.shields.io/github/stars/IronsDu/brynet?style=social)](https://github.com/IronsDu/brynet/stargazers/) | Cross-platform C++ TCP network library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cppzmq](https://github.com/zeromq/cppzmq) | [![GitHub stars](https://img.shields.io/github/stars/zeromq/cppzmq?style=social)](https://github.com/zeromq/cppzmq/stargazers/) | Header-only C++ binding for libzmq. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [nygma](https://github.com/stackless-goto/nygma) | [![GitHub stars](https://img.shields.io/github/stars/stackless-goto/nygma?style=social)](https://github.com/stackless-goto/nygma/stargazers/) | Network packet processing and indexing. | [![License: BlueOak](https://img.shields.io/badge/License-BlueOak-blue.svg)](https://spdx.org/licenses/BlueOak-1.0.0.html) |
| [uvw](https://github.com/skypjack/uvw) | [![GitHub stars](https://img.shields.io/github/stars/skypjack/uvw?style=social)](https://github.com/skypjack/uvw/stargazers/) | libuv wrapper in modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Optimization

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [ensmallen](https://github.com/mlpack/ensmallen) | [![GitHub stars](https://img.shields.io/github/stars/mlpack/ensmallen?style=social)](https://github.com/mlpack/ensmallen/stargazers/) | C++ library for numerical optimization. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |

## Parsing Expression Grammars

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cpp-peglib](https://github.com/yhirose/cpp-peglib) | [![GitHub stars](https://img.shields.io/github/stars/yhirose/cpp-peglib?style=social)](https://github.com/yhirose/cpp-peglib/stargazers/) | PEG (Parsing Expression Grammars) library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [PEGTL](https://github.com/taocpp/PEGTL) | [![GitHub stars](https://img.shields.io/github/stars/taocpp/PEGTL?style=social)](https://github.com/taocpp/PEGTL/stargazers/) | Parsing Expression Grammar Template Library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Portability Definitions

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [hedley](https://github.com/nemequ/hedley) | [![GitHub stars](https://img.shields.io/github/stars/nemequ/hedley?style=social)](https://github.com/nemequ/hedley/stargazers/) | Move #ifdefs out of your code. | [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/) |

## Reflection

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [better-enums](https://github.com/aantron/better-enums) | [![GitHub stars](https://img.shields.io/github/stars/aantron/better-enums?style=social)](https://github.com/amrayn/aantron/better-enums/) | C++ compile-time enum to string, iteration. | [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause) |
| [magic_enum](https://github.com/Neargye/magic_enum) | [![GitHub stars](https://img.shields.io/github/stars/Neargye/magic_enum?style=social)](https://github.com/Neargye/magic_enum/stargazers/) | Static reflection for enums. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [meta](https://github.com/skypjack/meta) | [![GitHub stars](https://img.shields.io/github/stars/skypjack/meta?style=social)](https://github.com/skypjack/meta/stargazers/) | Macro-free runtime reflection system. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [nameof](https://github.com/Neargye/nameof) | [![GitHub stars](https://img.shields.io/github/stars/Neargye/nameof?style=social)](https://github.com/Neargye/nameof/stargazers/) | Nameof operator for modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [refl-cpp](https://github.com/veselink1/refl-cpp) | [![GitHub stars](https://img.shields.io/github/stars/veselink1/refl-cpp?style=social)](https://github.com/veselink1/refl-cpp/stargazers/) | Compile-time reflection library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [visit_struct](https://github.com/garbageslam/visit_struct) | [![GitHub stars](https://img.shields.io/github/stars/garbageslam/visit_struct?style=social)](https://github.com/garbageslam/visit_struct/stargazers/) | A miniature library for struct-field reflection. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Regular Expression

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [compile-time regular expressions](https://github.com/hanickadot/compile-time-regular-expressions) | [![GitHub stars](https://img.shields.io/github/stars/hanickadot/compile-time-regular-expressions?style=social)](https://github.com/hanickadot/compile-time-regular-expressions/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; | A Compile time regular expression matcher. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |

## Robotics

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [manif](https://github.com/artivis/manif) | [![GitHub stars](https://img.shields.io/github/stars/artivis/manif?style=social)](https://github.com/artivis/manif/stargazers/) | Small library for Lie theory. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Serialization

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cereal](https://github.com/USCiLab/cereal) | [![GitHub stars](https://img.shields.io/github/stars/USCiLab/cereal?style=social)](https://github.com/USCiLab/cereal/stargazers/) | A C++11 library for serialization. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [essentials](https://github.com/jermp/essentials) | [![GitHub stars](https://img.shields.io/github/stars/jermp/essentials?style=social)](https://github.com/jermp/essentials/stargazers/) | Transparent serialization/deserialization. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [fuser](https://github.com/Xeverous/fuser) | [![GitHub stars](https://img.shields.io/github/stars/Xeverous/fuser?style=social)](https://github.com/Xeverous/fuser/stargazers/) | Automatic (de)serialization of C++ types to/from JSON. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [YAS](https://github.com/nixman/yas) | [![GitHub stars](https://img.shields.io/github/stars/niXman/yas?style=social)](https://github.com/niXman/yas/stargazers/) | A C++11 (de)serialization library with support for binary/text/json archives. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## SIMD

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [libsimdpp](https://github.com/p12tic/libsimdpp) | [![GitHub stars](https://img.shields.io/github/stars/p12tic/libsimdpp?style=social)](https://github.com/p12tic/libsimdpp/stargazers/) | Low-level SIMD library. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [simde](https://github.com/simd-everywhere/simde) | [![GitHub stars](https://img.shields.io/github/stars/simd-everywhere/simde?style=social)](https://github.com/simd-everywhere/simde/stargazers/) | Implementations of SIMD instruction sets. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tsimd](https://github.com/ospray/tsimd) | [![GitHub stars](https://img.shields.io/github/stars/ospray/tsimd?style=social)](https://github.com/ospray/tsimd/stargazers/) | Fundamental C++ SIMD types for Intel CPUs. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Standard/Support Libraries

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [bitflags](https://github.com/m-peko/bitflags) | [![GitHub stars](https://img.shields.io/github/stars/m-peko/bitflags?style=social)](https://github.com/m-peko/bitflags/stargazers/) | Easily managing set of flags. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cpp-typelist](https://github.com/dave-hagedorn/cpp-typelist) | [![GitHub stars](https://img.shields.io/github/stars/dave-hagedorn/cpp-typelist?style=social)](https://github.com/dave-hagedorn/cpp-typelist/stargazers/) | Modern typelist for C++20 | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [expected](https://github.com/TartanLlama/expected) | [![GitHub stars](https://img.shields.io/github/stars/TartanLlama/expected?style=social)](https://github.com/TartanLlama/expected/stargazers/) | C++11/14/17 std::expected. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [expected-lite](https://github.com/martinmoene/expected-lite) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/expected-lite?style=social)](https://github.com/martinmoene/expected-lite/stargazers/) | Expected objects in C++11 and later. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [gsl](https://github.com/microsoft/GSL) | [![GitHub stars](https://img.shields.io/github/stars/microsoft/GSL?style=social)](https://github.com/microsoft/GSL/stargazers/) | ISO C++ Guidelines Support Library (GSL) by Microsoft. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [gsl-lite](https://github.com/gsl-lite/gsl-lite) | [![GitHub stars](https://img.shields.io/github/stars/gsl-lite/gsl-lite?style=social)](https://github.com/gsl-lite/gsl-lite/stargazers/) | ISO C++ Guidelines Support Library (GSL). | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [hana](https://github.com/boostorg/hana) | [![GitHub stars](https://img.shields.io/github/stars/boostorg/hana?style=social)](https://github.com/boostorg/hana/stargazers/) | Your standard library for metaprogramming. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [itlib](https://github.com/iboB/itlib) | [![GitHub stars](https://img.shields.io/github/stars/iboB/itlib?style=social)](https://github.com/iboB/itlib/stargazers/) | Standard-library-like containers and extensions. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [leaf](https://github.com/boostorg/leaf) | [![GitHub stars](https://img.shields.io/github/stars/boostorg/leaf?style=social)](https://github.com/boostorg/leaf/stargazers/) | Lightweight Error Augmentation Framework. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [libunifex](https://github.com/facebookexperimental/libunifex) | [![GitHub stars](https://img.shields.io/github/stars/facebookexperimental/libunifex?style=social)](https://github.com/facebookexperimental/libunifex/stargazers/) | Unified Executors | [![License](https://img.shields.io/badge/license-Facebook-blue.svg)](https://github.com/facebookexperimental/libunifex/blob/master/LICENSE.txt) |
| [mp11](https://github.com/boostorg/mp11) | [![GitHub stars](https://img.shields.io/github/stars/boostorg/mp11?style=social)](https://github.com/boostorg/mp11/stargazers/) | C++11 metaprogramming library. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [NanoRange](https://github.com/tcbrindle/NanoRange) | [![GitHub stars](https://img.shields.io/github/stars/tcbrindle/NanoRange?style=social)](https://github.com/tcbrindle/NanoRange/stargazers/) | Range-based goodness for C++17. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [numeric_ranges](https://github.com/tcbrindle/numeric_ranges) | [![GitHub stars](https://img.shields.io/github/stars/tcbrindle/numeric_ranges?style=social)](https://github.com/tcbrindle/numeric_ranges/stargazers/) | Numeric algorithms for C++20 Ranges. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [optional](https://github.com/TartanLlama/optional) | [![GitHub stars](https://img.shields.io/github/stars/TartanLlama/optional?style=social)](https://github.com/TartanLlama/optional/stargazers/) | C++11/14/17 std::optional. | [![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/) |
| [optional-lite](https://github.com/martinmoene/optional-lite) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/optional-lite?style=social)](https://github.com/martinmoene/optional-lite/stargazers/) | A C++17-like optional for C++98/11 and later. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [range-v3](https://github.com/ericniebler/range-v3) | [![GitHub stars](https://img.shields.io/github/stars/ericniebler/range-v3?style=social)](https://github.com/ericniebler/range-v3/stargazers/) | Range library for C++14/17/20. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [rangesnext](https://github.com/cor3ntin/rangesnext) | [![GitHub stars](https://img.shields.io/github/stars/cor3ntin/rangesnext?style=social)](https://github.com/cor3ntin/rangesnext/stargazers/) | Tanges features for c+23 ported to C++20. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [span-lite](https://github.com/martinmoene/span-lite) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/span-lite?style=social)](https://github.com/martinmoene/span-lite/stargazers/) | A C++20-like span for C++98/11 and later. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [string-view-lite](https://github.com/martinmoene/string-view-lite) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/string-view-lite?style=social)](https://github.com/martinmoene/string-view-lite/stargazers/) | A C++17-like string_view for C++98/11 and later. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [uberswitch](https://github.com/falemagn/uberswitch) | [![GitHub stars](https://img.shields.io/github/stars/falemagn/uberswitch?style=social)](https://github.com/falemagn/uberswitch/stargazers/) | Alternative to the C++ switch statement. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [variant-lite](https://github.com/martinmoene/variant-lite) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/variant-lite?style=social)](https://github.com/martinmoene/variant-lite/stargazers/) | A C++17-like variant for C++98/11 and later. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [Windows Implementation Libraries (WIL)](https://github.com/microsoft/wil) | [![GitHub stars](https://img.shields.io/github/stars/microsoft/wil?style=social)](https://github.com/microsoft/wil/stargazers/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Readable type-safe C++ interfaces for common Windows coding patterns. |  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |

## State Machine

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [hfsm2](https://github.com/andrew-gresyk/HFSM2) | [![GitHub stars](https://img.shields.io/github/stars/andrew-gresyk/HFSM2?style=social)](https://github.com/andrew-gresyk/HFSM2/stargazers/) | High-performance hierarchical finite state machine framework. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [hsm](https://github.com/erikzenker/hsm) | [![GitHub stars](https://img.shields.io/github/stars/erikzenker/hsm?style=social)](https://github.com/erikzenker/hsm/stargazers/) | Finite state machine library based on the boost hana. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [tinyfsm](https://github.com/digint/tinyfsm) | [![GitHub stars](https://img.shields.io/github/stars/digint/tinyfsm?style=social)](https://github.com/digint/tinyfsm/stargazers/) | A simple C++ finite state machine library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [SMLite](https://github.com/fawdlstty/SMLite) | [![GitHub stars](https://img.shields.io/github/stars/fawdlstty/SMLite?style=social)](https://github.com/fawdlstty/SMLite/stargazers/) | State machine library for C, C++, C#, Java, JavaScript, Python, `VB.Net`. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [cuestate](https://github.com/xcyl/cuestate) | [![GitHub stars](https://img.shields.io/github/stars/xcyl/cuestate?style=social)](https://github.com/xcyl/cuestate/stargazers/) | C++ template metaprogramming FSM. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |

## Statistics

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [histogram](https://github.com/boostorg/histogram) | [![GitHub stars](https://img.shields.io/github/stars/boostorg/histogram?style=social)](https://github.com/boostorg/histogram/stargazers/) | Multi-dimensional generalized histograms. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [kalman](https://github.com/mherb/kalman) | [![GitHub stars](https://img.shields.io/github/stars/mherb/kalman?style=social)](https://github.com/mherb/kalman/stargazers/) | Kalman Filtering Library (EKF, UKF) based on Eigen3. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [stats](https://github.com/kthohr/stats) | [![GitHub stars](https://img.shields.io/github/stars/kthohr/stats?style=social)](https://github.com/kthohr/stats/stargazers/) | Statistical distribution functions. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |

## String Utilities

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [utf-cpp](https://github.com/ww898/utf-cpp) | [![GitHub stars](https://img.shields.io/github/stars/ww898/utf-cpp?style=social)](https://github.com/ww898/utf-cpp/stargazers/) | UTF-8/16/32 for Windows/Linux/MacOs. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [wildcards](https://github.com/zemasoft/wildcards) | [![GitHub stars](https://img.shields.io/github/stars/zemasoft/wildcards?style=social)](https://github.com/zemasoft/wildcards/stargazers/) | String matching using wildcards. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Templating Engines

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [inja](https://github.com/pantor/inja) | [![GitHub stars](https://img.shields.io/github/stars/pantor/inja?style=social)](https://github.com/pantor/inja/stargazers/) | A Template Engine for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Terminal Utilities

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [indicators](https://github.com/p-ranav/indicators) | [![GitHub stars](https://img.shields.io/github/stars/p-ranav/indicators?style=social)](https://github.com/p-ranav/indicators/stargazers/) | Activity Indicators for Modern C++. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [rang](https://github.com/agauniyal/rang) | [![GitHub stars](https://img.shields.io/github/stars/agauniyal/rang?style=social)](https://github.com/agauniyal/rang/stargazers/) | A Minimal library for terminal goodies 💄✨. | [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/) |
| [termcolor](https://github.com/ikalnytskyi/termcolor) | [![GitHub stars](https://img.shields.io/github/stars/ikalnytskyi/termcolor?style=social)](https://github.com/ikalnytskyi/termcolor/stargazers/) | Print colored messages to the terminal. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |

## Testing Frameworks

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [ApprovalTests.cpp](https://github.com/approvals/ApprovalTests.cpp) | [![GitHub stars](https://img.shields.io/github/stars/approvals/ApprovalTests.cpp?style=social)](https://github.com/approvals/ApprovalTests.cpp/stargazers/) | Native ApprovalTests for C++. | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) |
| [Catch2](https://github.com/catchorg/Catch2) | [![GitHub stars](https://img.shields.io/github/stars/catchorg/Catch2?style=social)](https://github.com/catchorg/Catch2/stargazers/) | Test framework for unit-tests, TDD and BDD. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [doctest](https://github.com/onqtam/doctest) | [![GitHub stars](https://img.shields.io/github/stars/onqtam/doctest?style=social)](https://github.com/onqtam/doctest/stargazers/) | The fastest feature-rich C++11/14/17/20 testing framework. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [iutest](https://github.com/srz-zumix/iutest) | [![GitHub stars](https://img.shields.io/github/stars/srz-zumix/iutest?style=social)](https://github.com/srz-zumix/iutest/stargazers/) | Test framework for unit-tests. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
| [lest](https://github.com/martinmoene/lest) | [![GitHub stars](https://img.shields.io/github/stars/martinmoene/lest?style=social)](https://github.com/martinmoene/lest/stargazers/) | Tiny framework for unit-tests, TDD and BDD. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |
| [ut](https://github.com/boost-ext/ut) | [![GitHub stars](https://img.shields.io/github/stars/boost-ext/ut?style=social)](https://github.com/boost-ext/ut/stargazers/) | UT: C++20 μ(micro)/Unit Testing Framework. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Units

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [mpusz/units](https://github.com/mpusz/units) | [![GitHub stars](https://img.shields.io/github/stars/mpusz/units?style=social)](https://github.com/mpusz/units/stargazers/) | Compile-time dimensional analysis and unit/quantity manipulation. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [nholthaus/units](https://github.com/nholthaus/units) | [![GitHub stars](https://img.shields.io/github/stars/nholthaus/units?style=social)](https://github.com/nholthaus/units/stargazers/) | Dimensional analysis and unit conversion library. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |
| [SI](https://github.com/bernedom/SI) | [![GitHub stars](https://img.shields.io/github/stars/bernedom/SI?style=social)](https://github.com/bernedom/SI/stargazers/) | Type safety and user defined literals for physical units. | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) |

## Validation

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [cpp-validator](https://github.com/evgeniums/cpp-validator) | [![GitHub stars](https://img.shields.io/github/stars/evgeniums/cpp-validator?style=social)](https://github.com/evgeniums/cpp-validator/stargazers/) | C++ library for data validation. | [![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt) |

## Web Frameworks

| Library  | Stars |  Description | License  |
|--- | ---| ---|--- |
| [crow](https://github.com/ipkn/crow) | [![GitHub stars](https://img.shields.io/github/stars/ipkn/crow?style=social)](https://github.com/ipkn/crow/stargazers/) | Micro web framework inspired by Python Flask. | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) |
