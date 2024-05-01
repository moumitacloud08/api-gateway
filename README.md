# api-gateway

currency-exchange API URL:-
http://localhost:8000/currency-exchange/from/EUR/to/INR

currency-conversion API URL:-
http://localhost:8100/currency-converter/from/USD/to/INR/quantity/1000

currency-conversion Feign LoadBalancing URI:- 
http://localhost:8100/currency-converter-feign/from/USD/to/INR/quantity/1000

------------------EUREKA---------------------------
http://localhost:8761/

--------------------APIGATEWAY------------------------

APIGateway URIs:-

- http://localhost:8765/CURRENCY-EXCHANGE-SERVICE/currency-exchange/from/EUR/to/INR

- http://localhost:8765/CURRENCY-CONVERSION-SERVICE/currency-converter/from/USD/to/INR/quantity/1000

- http://localhost:8765/CURRENCY-CONVERSION-SERVICE/currency-converter-feign/from/USD/to/INR/quantity/1000

----lowercase-----

- http://localhost:8765/currency-exchange-service/currency-exchange/from/EUR/to/INR

- http://localhost:8765/currency-conversion-service/currency-converter/from/USD/to/INR/quantity/1000

- http://localhost:8765/currency-conversion-service/currency-converter-feign/from/USD/to/INR/quantity/1000

------CUSTOM ROUTE--------

http://localhost:8765/currency-exchange/from/EUR/to/INR
http://localhost:8765/currency-converter/from/USD/to/INR/quantity/1000
http://localhost:8765/currency-converter-feign/from/USD/to/INR/quantity/1000
http://localhost:8765/currency-converter-new/from/USD/to/INR/quantity/1000

----------Zipkin--------------
http://localhost:9411/zipkin