### Circuit Breaker policy ###

This policy implements the Circuit Breaker pattern by monitoring a configurable number of exceptions or errors returned from the target endpoint.

#### Configuration

The policy configuration contains several input parameters:

+  error_count - number of errors/exceptions upon which the breaker trips
+  wait_time - Ammount of time the breaker will be on until it gets opened again (ms)
+  error message trap MEL Expression - A MEL expression used to trap for errors in the resulting message


