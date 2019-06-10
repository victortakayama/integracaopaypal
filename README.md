# integracaopaypal
PayPal integration by node.js SDK express checkout.
Payment server response completed successfully.

Get Payment Response
"id":"PAYID-LT6JWOQ4KA94846902636437",
"intent":"sale",
"state":"approved",
"cart":"2PS98213TF4823801",
"payer":
"payment_method":"paypal",
"status":"VERIFIED",
"payer_info":{"email":"teste@testemts.com.br",
"first_name":"Teste",
"last_name":"Teste MTS",
"payer_id":"ZM32UQ3PFN5ZJ",
"shipping_address":
"recipient_name":"Teste Teste MTS",
"line1":"1234 Rua Main",
"city":"Rio De Janeiro",
"state":"RJ",
"postal_code":"22021-001",
"country_code":"BR",
"normalization_status":"UNNORMALIZED_USER_PREFERRED"},
"tax_id_type":"BR_CPF",
"tax_id":"30949017787",
"country_code":"BR",
"transactions":
"amount":
"total":"70.00",
"currency":"BRL",
"details":
"payee":
"merchant_id":"5RPJZWYHTDUFS",
"email":"vitor.takayama-buyer@gmail.com"
"description":"Um mousepad muito bom!",
"name":"MousePad",
"sku":"2",
"price":"70.00",
"currency":"BRL",
"quantity":1
"shipping_address":
"recipient_name":"Teste Teste MTS",
"line1":"1234 Rua Main",
"city":"Rio De Janeiro",
"state":"RJ",
"postal_code":"22021-001",
"country_code":"BR",
"normalization_status":"UNNORMALIZED_USER_PREFERRED"
"shipping_options":[null]
"related_resources":
"sale":
"id":"6WF27459UJ481893G",
"state":"completed",
"amount":
"total":"70.00",
"currency":"BRL",
"details":
"subtotal":"70.00"
"payment_mode":"INSTANT_TRANSFER",
"protection_eligibility":"ELIGIBLE",
"protection_eligibility_type":"ITEM_NOT_RECEIVED_ELIGIBLE,UNAUTHORIZED_PAYMENT_ELIGIBLE",
"transaction_fee": "value":"2.78",
"currency":"BRL"
"parent_payment":"PAYID-LT6JWOQ4KA94846902636437",
"create_time":"2019-06-09T05:38:44Z",
"update_time":"2019-06-09T05:38:44Z",
"links": "href":"https://api.sandbox.paypal.com/v1/payments/sale/6WF27459UJ481893G",
"rel":"self",
"method":"GET"
"href":"https://api.sandbox.paypal.com/v1/payments/sale/6WF27459UJ481893G/refund",
"rel":"refund",
"method":"POST"
"href":"https://api.sandbox.paypal.com/v1/payments/payment/PAYID-LT6JWOQ4KA94846902636437",
"rel":"parent_payment",
"method":"GET"
"create_time":"2019-06-09T05:38:44Z",
"links": "href":"https://api.sandbox.paypal.com/v1/payments/payment/PAYID-LT6JWOQ4KA94846902636437",
"rel":"self",
"method":"GET"
"httpStatusCode":200}
