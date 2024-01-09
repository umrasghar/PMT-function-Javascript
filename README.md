# PMT-function-Javascript
PMT function implementation in javascript.  A web-based loan calculator application with real-time result updates.


# Loan Calculator App

A simple web-based loan calculator application with a modern and clean interface. This repository provides an example of form handling and real-time result updates using HTML, CSS, and JavaScript.

## PMT Function Implementation

The core functionality of the loan calculator is powered by the PMT (Payment) function implemented in JavaScript. The PMT function calculates the monthly payment for a loan based on the loan amount, interest rate, loan duration, and final term.

### PMT Function Signature

```javascript
function calculatePMT(rate, nperiod, pv, fv, type) {
    // Implementation goes here
}
```

### Parameters

- `rate`: The interest rate for each period.
- `nperiod`: The number of periods.
- `pv`: The present value, or the total amount of the loan.
- `fv`: The future value, or a cash balance you want to attain after the last payment.
- `type`: An optional argument indicating whether payments are due at the beginning (1) or end (0) of the period.

### Usage Example

```javascript
var monthpay = calculatePMT(0.01, 12, -1000, 0, 0);
console.log(monthpay); // Output: -87.91284511099318
```

Feel free to explore and use the PMT function for your own projects or share it with others who may find it useful.
```

