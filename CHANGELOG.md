## 6.1.2 (2022-12-07)

### Bug fixes

Automatic tag closing in JSX now works for namespaced and member-expression tag names.

## 6.1.1 (2022-10-24)

### Bug fixes

Make `completionPath` handle `?.` syntax.

## 6.1.0 (2022-09-20)

### New features

The `completionPath` helper can now be used to find the object path to complete at a given position.

`scopeCompletionSource` provides a completion source based on a scope object.

## 6.0.2 (2022-07-21)

### Bug fixes

Fix the `source` field in ESLint diagnostics to properly hold `"eslint"`.

Fix (non-)auto indentation in template strings and comments.

## 6.0.1 (2022-06-29)

### Bug fixes

Avoid completing variables/keywords in property or definition positions.

Fix a bug that broke local variable completion if JavaScript was parsed an overlay in an outer language.

## 6.0.0 (2022-06-08)

### Breaking changes

Update dependencies to 6.0.0

## 0.20.1 (2022-06-01)

### New features

`localCompletionSource` (included in the support extensions returned from `javascript`) now provides a way to complete locally-defined names.

## 0.20.0 (2022-04-20)

### New features

The new `autoCloseTags` extension (included by default in the `javascript` language extension when `jsx` is configured) finishes JSX closing tags when you type a `>` or `/` character.

## 0.19.7 (2022-01-28)

## 0.19.6 (2022-01-11)

### Bug fixes

Remove accidentally released unfinished changes.

## 0.19.5 (2022-01-11)

### Bug fixes

Add the `function` highlight modifier to variables used in tagged template expressions.

## 0.19.4 (2022-01-03)

### Bug fixes

Fix highlighting of TypeScript private/public/protected keywords.

## 0.19.3 (2021-11-12)

### Bug fixes

Add styling for private properties.

## 0.19.2 (2021-09-23)

### New features

Use more specific highlighting tags for JSX attribute names and values.

## 0.19.1 (2021-08-11)

### Bug fixes

Fix incorrect versions for @lezer dependencies.

## 0.19.0 (2021-08-11)

### Breaking changes

Update dependencies to 0.19.0

## 0.18.0 (2021-03-03)

### Bug fixes

Extend `indentOnInput` expression to cover closing JSX tags.

## 0.17.2 (2021-02-15)

### Bug fixes

Improve highlighting tag specificity of defined function and class names. Add indentation information for JSX constructs

Support smart indent for JSX syntax.

## 0.17.1 (2021-01-06)

### New features

The package now also exports a CommonJS module.

## 0.17.0 (2020-12-29)

### Breaking changes

First numbered release.

