0.9.5.0
-------

- Drop support for GHCs prior 8.6
- Require libpq >=10.22 (when using pkgconfig).
- Use CApiFFI for some parts of the API
  (we cannot use for all due https://gitlab.haskell.org/ghc/ghc/-/issues/22043)

0.9.4.3
-------

- Support `bytestring-0.11`
- Allow `Win32-2.10.0.0`
- Make `PQconsumeInput` FFI call `safe`

0.9.4.2
-------

- Support GHC-8.6.1
- Add simple smoke test

