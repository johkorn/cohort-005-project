# Cadence

An online course platform where people buy courses, learn from them, and can get their money back within a set window.

## Language

### People

**Student**:
A person who takes courses on Cadence. Distinct from Instructors and Admins.
_Avoid_: Learner, user, customer, buyer

### Buying

**Purchase**:
A Student buying one course for themselves, at the price they paid.
_Avoid_: Order, transaction, enrollment

**Team Purchase**:
A team admin buying seats in a course for other people to claim. Not a Purchase, and has no Refund.
_Avoid_: Team licence, bulk purchase

### Refunds

**Refund**:
A Student's request to get back what they paid for one Purchase, together with its outcome. An Approved Refund ends the Student's access to that course.
_Avoid_: Cancellation, reversal, chargeback

**Requested**:
The state of a Refund the Student has sent and nobody has decided on yet.
_Avoid_: Pending, open

**Approved**:
The state of a Refund where Cadence has agreed to send the money back.
_Avoid_: Confirmed, accepted, completed

**Declined**:
The state of a Refund where Cadence has refused to send the money back. The Student keeps the course.
_Avoid_: Rejected, denied
