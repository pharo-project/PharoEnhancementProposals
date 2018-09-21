# Float literal usage should be discouraged

In general, it is not desirable to use float because a lot of errors happen when doing (even simple) computation involving floats.
Pharo provides `ScaledDecimal` which allows one to store rational numbers as a fraction (without precision loss). 

## Motivation/Rationale

## Proposals
CodeCritic rule with automatic transformation to replace `Float` literal `\d+.\d*` with `ScaledDecimal` literal `\d+.\d*s` (note the trailing `s`).

## Implementation
* link to issue
* link to PR

## Backwards compatibility issues

## Open points
