# Prophecy Machine Learning

PredictionIO engine basado en [E-Commerce Recommendation(Scala)](https://docs.prediction.io/templates/recommendation/quickstart/)

## Puesta en marcha
```bash
git clone git@github.com:the-four-brainiacs/predictionIO-prophecy.git
cd provisionIO-prophecy
pio app new prophecy
pio build
pio train
pio deploy
```

Nota: No se puede hacer un train si no tenemos ningún dato en el sistema. Podemos usar el script [import_data.rb](https://github.com/the-four-brainiacs/predictionIO-ecommerce-provision) para una carga initial de prueba. 