<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [ClientTransactionUser](./sip.js.clienttransactionuser.md)

## ClientTransactionUser interface

UAC Core Transaction User.

<b>Signature:</b>

```typescript
export interface ClientTransactionUser extends TransactionUser 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [onRequestTimeout](./sip.js.clienttransactionuser.onrequesttimeout.md) | <code>() =&gt; void</code> | Callback for request timeout error.<!-- -->When a timeout error is received from the transaction layer, it MUST be treated as if a 408 (Request Timeout) status code has been received. https://tools.ietf.org/html/rfc3261\#section-8.1.3.1 TU MUST be informed of a timeout. https://tools.ietf.org/html/rfc3261\#section-17.1.2.2 |
|  [receiveResponse](./sip.js.clienttransactionuser.receiveresponse.md) | <code>(response: IncomingResponseMessage) =&gt; void</code> | Callback for delegation of valid response handling.<!-- -->Valid responses are passed up to the TU from the client transaction. https://tools.ietf.org/html/rfc3261\#section-17.1 |

