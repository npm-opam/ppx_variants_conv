## 113.24.00

- The `iter` function generated by ppx\_variants\_conv and ppx\_fields\_conv allowed
  one to give function which returned values of arbitrary types as iter function.
  This feature constraint these functions to return unit.

  N.B. the signature generated by the use of `@@deriving variants` (resp. fields)
  in interface already constrained the type to unit.

- Update to follow `Type_conv` evolution.
