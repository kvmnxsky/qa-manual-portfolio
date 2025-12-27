# Risk Analysis — Sauce Demo

Format: Risk | Impact | Likelihood | Why it matters | Test focus

## R1 — Users cannot log in
Impact: High
Likelihood: Medium
Why it matters: Blocks the entire purchase flow.
Test focus: Valid/invalid login, error handling, session behavior.

## R2 — Cart items do not persist
Impact: High
Likelihood: Medium
Why it matters: Users lose progress and abandon purchases.
Test focus: Add/remove items, refresh, back navigation, logout/login.

## R3 — Wrong prices or totals
Impact: High
Likelihood: Medium
Why it matters: Incorrect charges and loss of trust.
Test focus: Item prices, totals, tax/shipping display (if any), consistency across pages.

## R4 — Checkout fails or blocks user
Impact: High
Likelihood: Medium
Why it matters: Users can’t complete orders → revenue loss.
Test focus: Required fields, validation, error messages, continue/finish flow.

## R5 — Order confirmation is misleading
Impact: Medium
Likelihood: Low
Why it matters: Users think they ordered when they didn’t.
Test focus: Confirmation page, expected UI state after completion, cart cleared.

## R6 — Session is lost mid-flow
Impact: High
Likelihood: Low/Medium
Why it matters: User loses cart/checkout state.
Test focus: Idle time behavior, refresh, multi-tab behavior, login state consistency.
