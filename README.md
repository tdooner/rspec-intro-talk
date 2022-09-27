# RSpec Intro Talk
by Tom Dooner
10-11-2022

# Overview of this "talk"
Here's how this is meant to go.

1. Read the remainder of the README.md as an intro
2. Open this repo in github.dev.
3. We'll go through the example directories together.

# "Testing" - The what and why
Testing allows us to verify that our code behaves as expected, now and in the future.

This is important because nobody can keep a full mental picture of how a codebase should behave.

<details>
<summary>What are some different types of tests?</summary>

You'll hear these general terms that describe the "surface area" that a test covers:
* __Unit Tests__: Tests of individual methods (small surface area, isolated, "units")
* __Integration Tests__: Tests of an integrated system. (large surface area, entangled)

Rails and RSpec have a lot of different "types" of test, dependending on what you're trying to test. Here are some that we use (in order of increasing surface area):
* __Model Specs__: Tests of methods on a given Model.
* __Controller Specs__: Tests of request processing logic in a Controller.
* __System (or Feature) Specs__: Integration tests of a full page render. Sometimes uses a simulated browser to even test JavaScript.

Almost all Rails framework entities (Views, Routes, etc.) can be tested, but teams vary on whether we find those valuable.
</details>

