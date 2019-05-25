```ruby
irb(main):001:0> Integer.ancestors
=> [Integer, Numeric, Comparable, Object, Kernel, BasicObject]
irb(main):002:0> String.ancestors
=> [String, Comparable, Object, Kernel, BasicObject]
irb(main):003:0> Array.ancestors
=> [Array, Enumerable, Object, Kernel, BasicObject]
irb(main):004:0> Hash.ancestors
=> [Hash, Enumerable, Object, Kernel, BasicObject]
```

```ruby
irb(main):001:0> Rational.ancestors
=> [Rational, Numeric, Comparable, Object, Kernel, BasicObject]
irb(main):002:0> Complex.ancestors
=> [Complex, Numeric, Comparable, Object, Kernel, BasicObject]
irb(main):003:0> require 'bigdecimal'
=> true
irb(main):004:0> BigDecimal.ancestors
=> [BigDecimal, Numeric, Comparable, Object, Kernel, BasicObject]
irb(main):005:0> require 'matrix'
=> true
irb(main):006:0> Matrix.ancestors
=> [Matrix, Matrix::CoercionHelper, ExceptionForMatrix, Enumerable, Object, Kernel, BasicObject]
```
