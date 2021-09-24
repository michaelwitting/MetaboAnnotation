# MetaboAnnotation 0.2

## Changes in 0.2.9

- Add support for manually defined adducts to `Mass2MzParam` (issue
  [#41](https://github.com/rformassspectrometry/MetaboAnnotation/issues/41)).

## Changes in 0.2.8

- Add parameter `THRESHFUN_REVERSE` to `MatchForwardReverseParam` to allow
  filtering results on forward **and** reverse score (issue
  [#37](https://github.com/rformassspectrometry/MetaboAnnotation/issues/37)).

## Changes in 0.2.7

- Performance improvement in `matchSpectra` if no precursor m/z filter is used
  (issue
  [#38](https://github.com/rformassspectrometry/MetaboAnnotation/issues/38)).
- Report number of matching peaks in `matchSpectra,MatchForwardReverseParam`
  (issue
  [#36](https://github.com/rformassspectrometry/MetaboAnnotation/issues/36)).

## Changes in 0.2.6

- Fix bug in `matchSpectra` that was wrongly calculating the acceptable m/z
  difference if `tolerance` was > 0 (issue
  [#34](https://github.com/rformassspectrometry/MetaboAnnotation/issues/34)).
  Fix proposed by Hugo Varet (@hvaret).

## Changes in 0.2.5

- Improve performance of `matchMz`.
- Rename `queryColumn` and `targetColumn` to `queryColname` and `targetColname`.

## Changes in 0.2.4

- Support `data.frame`, `DataFrame` and `matrix` in `matchMz`.
- Add `addMatches` and `filterMatches` functions.

## Changes in 0.2.3

- Fixes in `MatchedSpectra`.

## Changes in 0.2.2

- Add `MatchedSummarizedExperiment`.

## Changes in 0.2.1

- Rename `TargetMass2MzParam` to `Mass2MzParam`.

## Changes in 0.2.0

- Add support for matching m/z against m/z and m/z in addition to retention
  times to `matchMz`.

# MetaboAnnotation 0.0

## Changes in 0.0.4

- Fix vignette, documentations and unit tests.