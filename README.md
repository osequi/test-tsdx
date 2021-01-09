# test-tsdx

Playing with TSDX.

See:

- https://tsdx.io/

## TLDR

- Complicates dev time with too many folders.
- Good for a single package. For monorepo additional setup / hacks is needed.

## Pro

- It works (tests, example)
- Intuitive package structure

## Cons

- Doesn't seem to support monorepo, aka multiple packages. [Radius](https://github.com/rangle/radius/tree/master/packages), the DS where TSDX was found uses two packages: `app` and `ds`. Anything below `ds` is a single package.
- Tests, examples are in a separate folder. Right, they can't be compiled into the package. But extends dev time.
