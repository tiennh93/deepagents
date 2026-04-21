# Changelog

## [0.5.4](https://github.com/tiennh93/deepagents/compare/deepagents==0.5.3...deepagents==0.5.4) (2026-04-21)


### Features

* **sdk,cli:** add openrouter SDK attribution ([#2205](https://github.com/tiennh93/deepagents/issues/2205)) ([2798e51](https://github.com/tiennh93/deepagents/commit/2798e51fd90128ffd1a2064383db17c699805395))
* **sdk,cli:** add package version metadata to traces ([#2129](https://github.com/tiennh93/deepagents/issues/2129)) ([e4a44b4](https://github.com/tiennh93/deepagents/commit/e4a44b467dee1e284ebe741a0e568f2dc613e068))
* **sdk:** `BASE_AGENT_PROMPT` tweaks ([#2541](https://github.com/tiennh93/deepagents/issues/2541)) ([812eef1](https://github.com/tiennh93/deepagents/commit/812eef185ffda7bc9e6f11425eb5eddc3d3b32e8))
* **sdk:** `ls_agent_type` configurable tag on subagent runs ([#2788](https://github.com/tiennh93/deepagents/issues/2788)) ([3bcc51a](https://github.com/tiennh93/deepagents/commit/3bcc51a95da80094cfc8bc4bcaf25dc1e2ad8f44))
* **sdk:** add `artifacts_root` to `CompositeBackend` and middleware ([#2490](https://github.com/tiennh93/deepagents/issues/2490)) ([753ee56](https://github.com/tiennh93/deepagents/commit/753ee567f1cc4d544dc2afea7b414564fd07d37d))
* **sdk:** add permissions system for filesystem access control ([#2633](https://github.com/tiennh93/deepagents/issues/2633)) ([41dc759](https://github.com/tiennh93/deepagents/commit/41dc7597deb3fc036f1f850e68edc3c0870f27da))
* **sdk:** add static structured output to subagent response ([#2437](https://github.com/tiennh93/deepagents/issues/2437)) ([6e57731](https://github.com/tiennh93/deepagents/commit/6e57731fc6d908ac1ebe131e782696a4776147e9))
* **sdk:** add system prompt snapshot test with sync and async subagents ([#2072](https://github.com/tiennh93/deepagents/issues/2072)) ([98874f5](https://github.com/tiennh93/deepagents/commit/98874f577f80524b47f6031f761870e1547c0645))
* **sdk:** add tau2 airline eval harness ([#1987](https://github.com/tiennh93/deepagents/issues/1987)) ([610b19f](https://github.com/tiennh93/deepagents/commit/610b19fa79d39e32f28464462235406430f65ceb))
* **sdk:** add tau2 LICENSE ([#2025](https://github.com/tiennh93/deepagents/issues/2025)) ([650cedb](https://github.com/tiennh93/deepagents/commit/650cedb21d638a77559f7ac034c8524178460f28))
* **sdk:** add timestamp tracking to `AsyncSubAgentJob` ([#2071](https://github.com/tiennh93/deepagents/issues/2071)) ([93aa3cf](https://github.com/tiennh93/deepagents/commit/93aa3cf16dedeec7d97834d5ea6dcd65cd4c6256))
* **sdk:** deprecate `model=None` in `create_deep_agent` ([#2677](https://github.com/tiennh93/deepagents/issues/2677)) ([149df41](https://github.com/tiennh93/deepagents/commit/149df415d17f3cf3b7eb0bd1e78460112bfa9b04))
* **sdk:** evict large HumanMessages ([#2183](https://github.com/tiennh93/deepagents/issues/2183)) ([4f72c34](https://github.com/tiennh93/deepagents/commit/4f72c34221aea0516738be566de0fffc2c7386ac))
* **sdk:** namespace improvements for deepagents ([#2386](https://github.com/tiennh93/deepagents/issues/2386)) ([66c57e1](https://github.com/tiennh93/deepagents/commit/66c57e1e33e21d5ed0b7ceaa615b0e1c27ac556b))
* **sdk:** port `LangSmithSandbox` from CLI to SDK ([#1983](https://github.com/tiennh93/deepagents/issues/1983)) ([dfff6e7](https://github.com/tiennh93/deepagents/commit/dfff6e7d2f91c269290ab677a9bd7454bc2f4989))
* **sdk:** scope permissions to routes for composite backends with sandbox default ([#2659](https://github.com/tiennh93/deepagents/issues/2659)) ([6dd6122](https://github.com/tiennh93/deepagents/commit/6dd612237a7ee707726c4cafc4b691704e4cdb37))


### Bug Fixes

* **deepagents:** remove old integration tests ([#2728](https://github.com/tiennh93/deepagents/issues/2728)) ([6653197](https://github.com/tiennh93/deepagents/commit/6653197b6cbec6dd1ca23d9f90bc1439ca26e6e5))
* plumb through generics for `create_deep_agent` ([#2383](https://github.com/tiennh93/deepagents/issues/2383)) ([6c28e22](https://github.com/tiennh93/deepagents/commit/6c28e22cc5768a82b27102adcea4dbb4b5ae6213))
* remove legacy subagents API ([#2443](https://github.com/tiennh93/deepagents/issues/2443)) ([56bbfd3](https://github.com/tiennh93/deepagents/commit/56bbfd3a7c9fc993f7ea6c54d5c54fca234c2273))
* **sdk,cli:** align error messages and clean up recent refactors ([#2171](https://github.com/tiennh93/deepagents/issues/2171)) ([e2db737](https://github.com/tiennh93/deepagents/commit/e2db73779926e1effd6d227e14b137b93393461e))
* **sdk:** `last_updated_at` field doesn't account for task status changes ([#2370](https://github.com/tiennh93/deepagents/issues/2370)) ([8e1a2d6](https://github.com/tiennh93/deepagents/commit/8e1a2d671eda3903d9ebacca4a5e4aa7378646c2))
* **sdk:** add new line after HEREDOC for edit inline sandbox ([#2340](https://github.com/tiennh93/deepagents/issues/2340)) ([beb4dbb](https://github.com/tiennh93/deepagents/commit/beb4dbb6c75700c6969f2c3bfe8f7bf6046ef3bb))
* **sdk:** bump recursion limit to 10_000 in deepagents and set agent name ([#2194](https://github.com/tiennh93/deepagents/issues/2194)) ([7dbc251](https://github.com/tiennh93/deepagents/commit/7dbc25180e05261fba4d5ec752d3052fbc826e4c))
* **sdk:** catch `UnicodeDecodeError` in `FilesystemBackend.read` ([#2319](https://github.com/tiennh93/deepagents/issues/2319)) ([9783fe4](https://github.com/tiennh93/deepagents/commit/9783fe43b71ad0fbe30593a263a27f38c6bf8f55))
* **sdk:** catch PermissionError in FilesystemBackend ripgrep ([#2571](https://github.com/tiennh93/deepagents/issues/2571)) ([3d5d673](https://github.com/tiennh93/deepagents/commit/3d5d67349c8e88e33af98137db9634742f018cb0))
* **sdk:** fix offloading for state backend ([#2266](https://github.com/tiennh93/deepagents/issues/2266)) ([92f5507](https://github.com/tiennh93/deepagents/commit/92f55075d978c27a6aa658968a1999754af973fe))
* **sdk:** fix TypeError in async sub-agents ([#2376](https://github.com/tiennh93/deepagents/issues/2376)) ([8be4a2e](https://github.com/tiennh93/deepagents/commit/8be4a2ee3878a3e15c15d56fd64ba8db248a6328))
* **sdk:** implement upload_files for StateBackend ([#2661](https://github.com/tiennh93/deepagents/issues/2661)) ([5798345](https://github.com/tiennh93/deepagents/commit/579834513a4ba1a024a52fc4edf918f526eab5f2))
* **sdk:** improvements in default sandbox.write and sandbox.read implementations ([#2321](https://github.com/tiennh93/deepagents/issues/2321)) ([4a37a46](https://github.com/tiennh93/deepagents/commit/4a37a469ffd8a2d3b515c4de72674673f433082b))
* **sdk:** inherit parent `interrupt_on` for subagents ([#2334](https://github.com/tiennh93/deepagents/issues/2334)) ([acad9bb](https://github.com/tiennh93/deepagents/commit/acad9bb6ceebee7dc74bd75dcffa49faa8697658))
* **sdk:** make created_at and modified_at NotRequired fields on FileData ([#2248](https://github.com/tiennh93/deepagents/issues/2248)) ([9862b5a](https://github.com/tiennh93/deepagents/commit/9862b5ad0e94fa52fde6971ac9c2a0a1875ee451))
* **sdk:** match example_agent_descriptions closing tag in task tool prompt ([#2462](https://github.com/tiennh93/deepagents/issues/2462)) ([c36a41c](https://github.com/tiennh93/deepagents/commit/c36a41ccacd46d54806943821ebf16c606a5bc9f))
* **sdk:** normalize CRLF line endings in `FilesystemBackend.edit()` ([#2256](https://github.com/tiennh93/deepagents/issues/2256)) ([69bd21e](https://github.com/tiennh93/deepagents/commit/69bd21e2b14fa4bfd88d858702aff0e64237d35d))
* **sdk:** normalize Windows backslash paths before PurePosixPath processing ([#1859](https://github.com/tiennh93/deepagents/issues/1859)) ([e1c1d50](https://github.com/tiennh93/deepagents/commit/e1c1d5024729f5205eaa42bf6a9bc1c93a30d043))
* **sdk:** overwrite `write` on LangSmithSandbox ([#2097](https://github.com/tiennh93/deepagents/issues/2097)) ([c492a76](https://github.com/tiennh93/deepagents/commit/c492a7697e390ae760945d06ca4e824c4f47cf92))
* **sdk:** raise `ValueError` for permission paths without leading slash and path traversal ([#2665](https://github.com/tiennh93/deepagents/issues/2665)) ([723d27d](https://github.com/tiennh93/deepagents/commit/723d27dcdce03cc9ffaa757c70533f0134a43a44))
* **sdk:** restore deprecated protocol return types ([#2342](https://github.com/tiennh93/deepagents/issues/2342)) ([845cdf5](https://github.com/tiennh93/deepagents/commit/845cdf52d7f15ab2b260de95f8448c04264c1efc))
* **sdk:** route subagent model resolution to `resolve_model` ([#2208](https://github.com/tiennh93/deepagents/issues/2208)) ([6720e4c](https://github.com/tiennh93/deepagents/commit/6720e4c520295ac1cb24c19cf3d315d2d05ba257))
* **sdk:** skill loading should default to 1000 lines ([#2721](https://github.com/tiennh93/deepagents/issues/2721)) ([badc4d3](https://github.com/tiennh93/deepagents/commit/badc4d3921ae0ede4305f44f85fa7266df9465e7))
* **sdk:** update middleware order ([#2070](https://github.com/tiennh93/deepagents/issues/2070)) ([def526b](https://github.com/tiennh93/deepagents/commit/def526b9621ee3c9e10b723acceb532341395554))
* **sdk:** update recursion limit ([#2273](https://github.com/tiennh93/deepagents/issues/2273)) ([fd91a30](https://github.com/tiennh93/deepagents/commit/fd91a30bf394d4d0ebf8deed9e7835dfc05c9891))
* **sdk:** updates for multimodal ([#2514](https://github.com/tiennh93/deepagents/issues/2514)) ([a2edf3e](https://github.com/tiennh93/deepagents/commit/a2edf3ed80e17a87027c41a46283387031ebd3e5))
* **sdk:** Use configurable directly instead of tracing context for subagent tagging ([#2845](https://github.com/tiennh93/deepagents/issues/2845)) ([bd6ec6b](https://github.com/tiennh93/deepagents/commit/bd6ec6bcebcdcc26f6b79e2c55611074b0e01631))
* **sdk:** use file transfer instead of command strings for sandbox write/edit ([#2117](https://github.com/tiennh93/deepagents/issues/2117)) ([6c2d559](https://github.com/tiennh93/deepagents/commit/6c2d559b574a5a5d9de3adc36d6cf02d6cf93d9d)), closes [#1402](https://github.com/tiennh93/deepagents/issues/1402)


### Performance Improvements

* **sdk:** add cache breakpoint to `MemoryMiddleware` ([#2713](https://github.com/tiennh93/deepagents/issues/2713)) ([1699f3a](https://github.com/tiennh93/deepagents/commit/1699f3aea710985087b16318bb8e6f6e80e02a1b))

## [0.5.3](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.2...deepagents==0.5.3) (2026-04-14)


### Features

* **sdk:** add static structured output to subagent response ([#2437](https://github.com/langchain-ai/deepagents/issues/2437)) ([6e57731](https://github.com/langchain-ai/deepagents/commit/6e57731fc6d908ac1ebe131e782696a4776147e9))
* **sdk:** deprecate `model=None` in `create_deep_agent` ([#2677](https://github.com/langchain-ai/deepagents/issues/2677)) ([149df41](https://github.com/langchain-ai/deepagents/commit/149df415d17f3cf3b7eb0bd1e78460112bfa9b04))


### Bug Fixes

* **sdk:** skill loading should default to 1000 lines ([#2721](https://github.com/langchain-ai/deepagents/issues/2721)) ([badc4d3](https://github.com/langchain-ai/deepagents/commit/badc4d3921ae0ede4305f44f85fa7266df9465e7))

## [0.5.2](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.1...deepagents==0.5.2) (2026-04-10)

### Features

* Permissions system for filesystem access control ([#2633](https://github.com/langchain-ai/deepagents/issues/2633)) ([41dc759](https://github.com/langchain-ai/deepagents/commit/41dc7597deb3fc036f1f850e68edc3c0870f27da))
  * Scope permissions to routes for composite backends with sandbox default ([#2659](https://github.com/langchain-ai/deepagents/issues/2659)) ([6dd6122](https://github.com/langchain-ai/deepagents/commit/6dd612237a7ee707726c4cafc4b691704e4cdb37))
  * Raise `ValueError` for permission paths without leading slash and path traversal ([#2665](https://github.com/langchain-ai/deepagents/issues/2665)) ([723d27d](https://github.com/langchain-ai/deepagents/commit/723d27dcdce03cc9ffaa757c70533f0134a43a44))
* Implement `upload_files` for `StateBackend` ([#2661](https://github.com/langchain-ai/deepagents/issues/2661)) ([5798345](https://github.com/langchain-ai/deepagents/commit/579834513a4ba1a024a52fc4edf918f526eab5f2))

### Bug Fixes

* Catch `PermissionError` in `FilesystemBackend` ripgrep ([#2571](https://github.com/langchain-ai/deepagents/issues/2571)) ([3d5d673](https://github.com/langchain-ai/deepagents/commit/3d5d67349c8e88e33af98137db9634742f018cb0))

## [0.5.1](https://github.com/langchain-ai/deepagents/compare/deepagents==0.5.0...deepagents==0.5.1) (2026-04-07)

### Features

* **sdk:** `BASE_AGENT_PROMPT` tweaks ([#2541](https://github.com/langchain-ai/deepagents/issues/2541)) ([812eef1](https://github.com/langchain-ai/deepagents/commit/812eef185ffda7bc9e6f11425eb5eddc3d3b32e8))
* **sdk:** add `artifacts_root` to `CompositeBackend` and middleware ([#2490](https://github.com/langchain-ai/deepagents/issues/2490)) ([753ee56](https://github.com/langchain-ai/deepagents/commit/753ee567f1cc4d544dc2afea7b414564fd07d37d))

### Bug Fixes

* **sdk:** updates for multimodal ([#2514](https://github.com/langchain-ai/deepagents/issues/2514)) ([a2edf3e](https://github.com/langchain-ai/deepagents/commit/a2edf3ed80e17a87027c41a46283387031ebd3e5))

---

# Prior Releases

Versions prior to 0.5.1 were released without release-please and do not have changelog entries. Refer to the [releases page](https://github.com/langchain-ai/deepagents/releases?q=deepagents) for details on previous versions.
