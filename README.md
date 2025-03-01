# The mrled/cauldron Homebrew tap

## How do I install these formulae?

`brew install mrled/cauldron/<formula>`

Or `brew tap mrled/cauldron` and then `brew install <formula>`.

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
tap "mrled/cauldron"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## Working with this repository

* Submit a PR
* Make sure the PR build is green
* Apply the `pr-pull` label to publish the bottles
* Merge the PR

## Tap contents

### `man-pages-posix`

* [Formula](./man-pages-posix.rb)
* [Upstream repository](https://web.git.kernel.org/pub/scm/docs/man-pages/man-pages-posix.git)
* [Upstream tarballs](https://www.kernel.org/pub/linux/docs/man-pages/man-pages-posix/)
* License:
  [proprietary](https://web.git.kernel.org/pub/scm/docs/man-pages/man-pages-posix.git/tree/man-pages-posix-2017/POSIX-COPYRIGHT)

POSIX manual pages maintained by the Linux kernel project's man-pages team.

Not eligible for `homebrew-core` because of the license.
