<a name="11.0.0-next.1"></a>
# 1.0.0-alpha.1 | June 13, 1989

---

### Bug Fixes

* **@omniframe/cli:** compute source-mappings for localized strings ([#38645](https://github.com/omniframe/omniframe/issues/38645)) ([7e0b3fd](https://github.com/omniframe/omniframe/commit/7e0b3fd)), closes [#38588](https://github.com/omniframe/omniframe/issues/38588)
* **@omniframe/core:** remove CollectionChangeRecord symbol ([#38668](https://github.com/omniframe/omniframe/issues/38668)) ([fdea180](https://github.com/omniframe/omniframe/commit/fdea180))
* **@omniframe/dev-server:** support lazy loading for empty path named outlets ([#38379](https://github.com/omniframe/omniframe/issues/38379)) ([926ffcd](https://github.com/omniframe/omniframe/commit/926ffcd)), closes [#12842](https://github.com/omniframe/omniframe/issues/12842)


### BREAKING CHANGES

* **core:** CollectionChangeRecord has been removed, use IterableChangeRecord
instead



<a name="10.1.1"></a>
## 10.1.1 (2020-09-09)


### Bug Fixes

* **compiler:** correct confusion between field and property names ([#38685](https://github.com/omniframe/omniframe/issues/38685)) ([a1c34c6](https://github.com/omniframe/omniframe/commit/a1c34c6))
* **compiler-cli:** compute source-mappings for localized strings ([#38747](https://github.com/omniframe/omniframe/issues/38747)) ([b4eb016](https://github.com/omniframe/omniframe/commit/b4eb016)), closes [#38588](https://github.com/omniframe/omniframe/issues/38588)
* **compiler-cli:** ensure that a declaration is available in type-to-value conversion ([#38684](https://github.com/omniframe/omniframe/issues/38684)) ([56d5ff2](https://github.com/omniframe/omniframe/commit/56d5ff2)), closes [#38670](https://github.com/omniframe/omniframe/issues/38670)
* **core:** reset `tView` between tests in Ivy TestBed ([#38659](https://github.com/omniframe/omniframe/issues/38659)) ([efc7606](https://github.com/omniframe/omniframe/commit/efc7606)), closes [#38600](https://github.com/omniframe/omniframe/issues/38600)
* **localize:** do not expose NodeJS typings in $localize runtime code ([#38700](https://github.com/omniframe/omniframe/issues/38700)) ([4de8dc3](https://github.com/omniframe/omniframe/commit/4de8dc3)), closes [#38692](https://github.com/omniframe/omniframe/issues/38692)
* **localize:** enable whitespace preservation marker in XLIFF files ([#38737](https://github.com/omniframe/omniframe/issues/38737)) ([190dca0](https://github.com/omniframe/omniframe/commit/190dca0)), closes [#38679](https://github.com/omniframe/omniframe/issues/38679)
* **localize:** install `[@omniframe](https://github.com/omniframe)/localize` in `devDependencies` by default ([#38680](https://github.com/omniframe/omniframe/issues/38680)) ([dbab744](https://github.com/omniframe/omniframe/commit/dbab744)), closes [#38329](https://github.com/omniframe/omniframe/issues/38329)
* **localize:** render context of translation file parse errors ([#38673](https://github.com/omniframe/omniframe/issues/38673)) ([32f33f0](https://github.com/omniframe/omniframe/commit/32f33f0)), closes [#38377](https://github.com/omniframe/omniframe/issues/38377)
* **localize:** render location in XLIFF 2 even if there is no metadata ([#38713](https://github.com/omniframe/omniframe/issues/38713)) ([ab4f953](https://github.com/omniframe/omniframe/commit/ab4f953)), closes [#38705](https://github.com/omniframe/omniframe/issues/38705)
* **ngcc:** use aliased exported types correctly ([#38666](https://github.com/omniframe/omniframe/issues/38666)) ([6a28675](https://github.com/omniframe/omniframe/commit/6a28675)), closes [#38238](https://github.com/omniframe/omniframe/issues/38238)
* **router:** If users are using the Alt key when clicking the router links, prioritize browser’s default behavior ([#38375](https://github.com/omniframe/omniframe/issues/38375)) ([309709d](https://github.com/omniframe/omniframe/commit/309709d))


### Performance Improvements

* **core:** use `ngDevMode` to tree-shake error messages ([#38612](https://github.com/omniframe/omniframe/issues/38612)) ([b084bff](https://github.com/omniframe/omniframe/commit/b084bff))