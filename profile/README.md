# `into_rust()`

IntoRust is a Github org experimenting with new ways to make learning Rust easier.
Our flagship product is a VSCode extension that supplements the compiler's error messages with AI-based explanations.
We also produce guides with answers to common Rust questions that can be read independently.

## Key repositories

* [VSCode extension](https://github.com/intorust/intorust.vscode)
* Guides:
  * TODO
* [sources](https://github.com/intorust/intorust.com) for [intorust.com](http://intorust.com) -- currently hosts podcasts, likely to be updated

## Our strategy

* Build out quality guides that answer common questions users have about Rust
* Develop extensions for common Rust IDEs that leverage these guides, plus LLM models
* Leverage feedback to make incremental improvements
  * Live teaching + tutorials
  * Automated mechanism where users can submit helpful (or unhelpful) sessions along with comments

## Design axioms

* **Errors are the best time to teach.** Rust has a lot of books, and that's good, but people like to dive in and learn by doing. We aim to give quality advice during that process.
* **Multi-layer strategy.** This whole intorust thing is an experiment. We aim to produce outputs of various kinds that will be useful even if the AI-thing doesn't work out.
* **Positive feedback loop.** We want a solution that improves automatically as people use it.

## Frequently asked questions

### What are other materials for learning Rust?

OMG there are so many good ones. To start, here are materials provided by the Rust organization itself...

* The [official Rust book], of course, but especially [this variant produced by Brown university that includes quizzes and updated material].
* The [Rustlings](https://github.com/rust-lang/rustlings) repo which contains code exercises as well as [Rust by example](https://doc.rust-lang.org/rust-by-example/).

...but there's a lot more out there! Check out the [ctjhoa/rust-learning](https://github.com/ctjhoa/rust-learning) repository for a comprehensive list.

### Can you possibly do better than existing LLMs?

Unclear, let's find out! At worst, we make some quality guides.
