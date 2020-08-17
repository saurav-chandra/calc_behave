# Addition

Scenario: Addition of two positive numbers

  Given The calculator is turned on

  When I type in "positive number"
  And I press "plus"
  And I type in "positive number"
  And I press "equals"

  Then I see the "added number" as the result

Scenario: Addition of two negative numbers

Scenario: Addition of fractions

Scenario: Addition of +ve and -ve number

Scenario: Addition of decimals

Scenario: Typing operator more than once

Scenario: Addition of more than 2 numbers

Scenario: Adding numbers where the result goes out of range

Scenario: 6+* is provided as input?

Scenario: Identify operation

Scenario: Converse operation
