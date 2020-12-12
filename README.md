# gha_qmake_gcc_cpp17

Branch   |[GitHub Actions](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17/actions)                                  
---------|-------------------------------------------------------------------------------------------------------------------
`master` |![GitHub Actions](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17/workflows/check/badge.svg?branch=master) 
`develop`|![GitHub Actions](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17/workflows/check/badge.svg?branch=develop)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean GitHub Actions build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:

 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp20.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp20) Use C++20: [gha_qmake_gcc_cpp20](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp20)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_bpp.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_bpp) Add `Bio++`: [gha_qmake_gcc_cpp17_bpp](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_bpp)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_boost.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_boost) Add `Boost`: [gha_qmake_gcc_cpp17_boost](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_boost)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_boost_test.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_boost_test) Add `Boost.Test`: [gha_qmake_gcc_cpp17_boost_test](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_boost_test)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-format.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-format) [gha_qmake_gcc_cpp17_clang-format](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_clang-format)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy) [gha_qmake_gcc_cpp17_clang-tidy](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_codechecker.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_codechecker) Add CodeChecker: [gha_qmake_gcc_cpp17_codechecker](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_codechecker)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_doxygen.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_doxygen) Add Doxygen: [gha_qmake_gcc_cpp17_doxygen](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_doxygen)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_gcov.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_gcov) Add code coverage: [gha_qmake_gcc_cpp17_gcov](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gcov)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy) Add `clang-tidy`: [gha_qmake_gcc_cpp17_clang-tidy](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_clang-tidy)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_cppcheck.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_cppcheck) Add `cppcheck`: [gha_qmake_gcc_cpp17_cppcheck](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_cppcheck)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_fltk.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_fltk) Add `FLTK`: [gha_qmake_gcc_cpp17_fltk](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_fltk)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_gprof.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_gprof) Add `gprof`: [gha_qmake_gcc_cpp17_gprof](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_gprof)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_magic_enum.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_magic_enum) Add `magic_enum`: [gha_qmake_gcc_cpp17_magic_enum](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_magic_enum)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_oclint.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_oclint) Add `OCLint`: [gha_qmake_gcc_cpp17_oclint](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_oclint)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_perf.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_perf) Add `perf`: [gha_qmake_gcc_cpp17_perf](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_perf)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_qt.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_qt) Add `Qt`: [gha_qmake_gcc_cpp17_qt](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_qt)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_r.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_r) Add `R`: [gha_qmake_gcc_cpp17_r](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_r)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_sdl.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_sdl) Add `SDL`: [gha_qmake_gcc_cpp17_sdl](https://github.com/richelbilderbeek/gha_qmake_gcc_cpp17_sdl)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_sfml.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_sfml) Add `SFML`: [gha_qmake_gcc_cpp17_sfml](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_sfml)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_rcpp.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_rcpp) Add `Rcpp`: [gha_qmake_gcc_cpp17_rcpp](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_rcpp)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_urho3d.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_urho3d) Add `Urho3D`: [gha_qmake_gcc_cpp17_urho3d](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_urho3d)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_wt.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_wt) Add `Wt`: [gha_qmake_gcc_cpp17_wt](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_wt)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_xmlpp.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_xmlpp) Add `xml++`: [gha_qmake_gcc_cpp17_xmlpp](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_xmlpp)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_tdc.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_tdc) Travis-dependent compilation: [gha_qmake_gcc_cpp17_tdc](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_tdc)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_tdr.svg?branch=master)](https://travis-ci.org/richelbilderbeek/gha_qmake_gcc_cpp17_tdr) Travis-dependent run: [gha_qmake_gcc_cpp17_tdr](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp17_tdr)

Builds of similar complexity:

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17) Use Travis CI: [travis_qmake_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17)
 * [![pipeline status](https://gitlab.com/richelbilderbeek/gitlab_qmake_gcc_cpp17/badges/master/pipeline.svg)](https://gitlab.com/richelbilderbeek/gitlab_qmake_gcc_cpp17/commits/master) Use GitLab CI: [gitlab_qmake_gcc_cpp17](https://www.gitlab.com/richelbilderbeek/gitlab_qmake_gcc_cpp17)

Less complex builds:

 * Use C++98: [gha_qmake_gcc_cpp98](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp98)
 * Use C++11: [gha_qmake_gcc_cpp11](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp11)
 * Use C++14: [gha_qmake_gcc_cpp14](https://www.github.com/richelbilderbeek/gha_qmake_gcc_cpp14)

