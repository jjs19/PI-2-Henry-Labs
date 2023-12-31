![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# PI-2-Henry-Data-PT02
## Proyecto individual 2
## Scarpeccio Julián Jesús

## Bienvenidos a mi repositorio de GitHub del Proyecto Individual número 2 de la carrera Data Science Part Time 02 de Henry.

En este proyecto, utilizamos Python para conectaron a la API CoinGecko, brindada en el enunciado del proyecto y Power Bi para el posterior analisis de datos y creacion de Dashboards

## Veamos un poco de que se trata el mundo de las Criptomonedas

Las criptomonedas son una forma de dinero digital
Imagina que tienes dinero en tu billetera, pero en lugar de billetes y monedas físicas, es dinero que solo existe en línea. Ese dinero digital es lo que llamamos una criptomoneda. Pero aquí viene lo interesante: en lugar de estar controlada por un banco o un gobierno, como el dinero tradicional, las criptomonedas funcionan de manera diferente.

En lugar de tener un banco que registre todas las transacciones y mantenga el control, las criptomonedas utilizan una tecnología especial llamada "blockchain". Piensa en el blockchain como un gran libro de contabilidad público y digital. Cada vez que alguien hace una transacción con una criptomoneda, como comprar algo o enviar dinero a otra persona, esa transacción se registra en el blockchain.

La razón por la que se llama "blockchain" es porque las transacciones se agrupan en bloques. Y cada bloque está conectado al anterior, formando una cadena de bloques. Esta cadena es lo que hace que las transacciones sean seguras y difíciles de cambiar de manera fraudulenta.

Además, las criptomonedas son descentralizadas, lo que significa que no están controladas por una sola persona o entidad. En cambio, muchas personas en todo el mundo ayudan a verificar y confirmar las transacciones. Esto se llama "minería" y es como resolver rompecabezas matemáticos para asegurarse de que todas las transacciones sean legítimas.

Las criptomonedas se pueden usar para comprar cosas en línea, invertir como si fueran acciones o incluso como una forma de transferir dinero a nivel internacional de manera rápida y relativamente barata.

## Aquí veamos un resumen de las 10 Criptomonedas con las que trabajaremos

Se seleccionaron 10 Monedas como lo piden las consignas del trabajo utilizando el Market Capital Ranking de CoinGecko.

### Resumen de las Monedas seleccionadas:
1. **Bitcoin (BTC):** Fue la primera criptomoneda y es conocida como "oro digital". Fue creada por una persona (o grupo) bajo el seudónimo de Satoshi Nakamoto. Bitcoin se basa en la tecnología blockchain y se utiliza como una forma de dinero digital descentralizado, permitiendo transacciones seguras y transparentes.

2. **Ethereum (ETH):** Es una plataforma blockchain que va más allá de las transacciones de criptomonedas. Permite la ejecución de contratos inteligentes y la creación de aplicaciones descentralizadas (DApps). Ethereum introdujo el concepto de tokens fungibles y no fungibles (NFTs), lo que amplió enormemente las posibilidades de la tecnología blockchain.

3. **Tether (USDT):** Es una criptomoneda conocida como "stablecoin", ya que está respaldada por monedas fiduciarias como el dólar estadounidense en una proporción de 1:1. Se utiliza principalmente como una forma de mantener el valor dentro del espacio de las criptomonedas, ya que su precio tiende a mantenerse cercano al del dólar.

4. **Binance Coin (BNB):** Originalmente creado como una moneda para el exchange Binance, BNB ha evolucionado para convertirse en una criptomoneda utilizada en la red Binance Smart Chain. Se utiliza para pagar tarifas de transacción en la plataforma Binance y para acceder a servicios dentro del ecosistema Binance.

5. **Ripple (XRP):** Ripple es tanto una red de pagos como una criptomoneda. Está diseñada para facilitar transferencias de dinero transfronterizas y pagos en tiempo real. A diferencia de muchas criptomonedas, Ripple se basa en un enfoque más centralizado, trabajando en colaboración con instituciones financieras.

6. **USD Coin (USDC):** Similar a Tether, USD Coin es otra stablecoin respaldada por dólares estadounidenses en una relación de 1:1. Su objetivo principal es ofrecer una forma de transferir valor en el mundo de las criptomonedas sin la volatilidad asociada con otras monedas digitales.

7. **Staked Ether (STETH):** Esta criptomoneda es un token derivado de Ethereum 2.0, la actualización de Ethereum que busca cambiar su algoritmo de consenso a Prueba de Participación. STETH representa los ethers que han sido depositados y "apostados" en la red Ethereum 2.0 para ayudar a asegurar la red.

8. **Cardano (ADA):** Cardano es una plataforma blockchain que se enfoca en la escalabilidad, la sostenibilidad y la seguridad. Al igual que Ethereum, busca admitir contratos inteligentes y aplicaciones descentralizadas, pero con un enfoque en la investigación científica y la revisión formal.

9. **Dogecoin (DOGE):** Inicialmente creado como una broma en torno a la comunidad de criptomonedas, Dogecoin ha ganado cierta popularidad. Se basa en el meme del perro Shiba Inu y ha sido utilizado para propósitos caritativos y propinas en línea.

10. **Solana (SOL):** Solana es una plataforma blockchain de alto rendimiento diseñada para la escalabilidad y la velocidad. Busca abordar los problemas de escalabilidad que enfrentan algunas otras redes, permitiendo aplicaciones descentralizadas y transacciones rápidas a bajo costo.

## Referencias

En el archivo llamado "PI-2 Henry JJS.ipynb" encontrara el proceso que realicé para extraer los datos desde la API mencionada anteriormente, el proceso de ETL y el EDA explicando paso a paso lo que fuí haciendo junto con las conclusiones respectivas. 

El resto de los archivos son CSVs para trabajar en PowerBi. 

## Dashboard de Power BI 

En esta parte del proyecto, la idea es definir KPIs y plasmarlos en el dashboard siendo éste interactivo.
El archivo se puede encontrar en la siguiente carpeta: https://drive.google.com/drive/folders/1IuvGz0840cLTapLrtvIynw5z5QUmActI?usp=share_link

## KPIs
### 1. Relación Precio y 24 HS Volume con Precio del Bitcoin.
### 2. Variacion entre Precio Máximo y Precio Actual con el respectivo % de variación.
### 3. % de Variación de Precios por día.

En este Dashboard se podrá ver en la primer slide la relacion del Precio en USD y el 24 Hs Volumes de las distintas monedas comparadas con una moneda fija, en este caso el Bitcoin, que es la moneda más reconocida actualmente y desde que se inició el mundo de las Criptomonedas.
Aquí llegamos a la conclusión de que las monedas a lo largo del tiempo siguen cierta tendencia similar al BTC, exceptuando las dos ligadas al Dolar que elegí dentro de las 10 (USD Coin y Tether), estas dos sigue una cotizacion similar al dolar por lo que no flutua demasiado su precio.

Por otro lado la relación entre el volumen y el precio es un aspecto clave en el análisis técnico de las criptomonedas. Generalmente se pueden observar algunas tendencias:

**Aumento del volumen con aumento del precio:** Si el volumen de compras y ventas de una criptomoneda aumenta significativamente en un período de tiempo, y el precio también sube, puede interpretarse como un respaldo fuerte y sostenido del aumento del precio. Esto podría indicar un interés creciente de los inversores y la demanda de la criptomoneda.
**Aumento del volumen con disminución del precio:** Si el volumen aumenta considerablemente mientras que el precio de la criptomoneda disminuye, esto podría sugerir una presión de venta. Los inversores podrían estar tratando de vender sus activos antes de que el precio caiga aún más.
**Bajo volumen con aumento del precio:** Un aumento en el precio de la criptomoneda con un bajo volumen puede indicar un interés limitado en el mercado. Los movimientos de precios basados en bajos volúmenes pueden ser menos confiables y más propensos a cambios bruscos debido a la falta de participación general.
**Bajo volumen con disminución del precio:** Si el precio cae con un bajo volumen, esto podría sugerir que la disminución del precio no está siendo impulsada por una gran cantidad de vendedores activos. En algunos casos, esto podría ser una señal de que el mercado está experimentando una consolidación antes de un posible movimiento más significativo.


Tambien se puede observar el Precio Máximo de la moneda que estemos seleccionando para comparar con Bitcoin, junto con el precio Actual para poder ver asi el potencial al que llegó la moneda en su pico máximo y como se encuentra en la actualidad (tomamos como actualidad: 30/6/2023 ya que descargué los datos de CoinGecko hasta esa fecha).

Por otro lado también mostramos una tabla con el % de variación de precios día a día. Lo cual nos sirve para ver en que momentos hubo mas variación porcentual sea esta posotiva o negativa.
De este KPIs podemos resaltar que entre los años 2020 y 2021 fueron los años de más aumento de precios en el mundo de las criptomonedas.

## Recomendaciones finales 

Es fundamental tener en cuenta que las inversiones en criptomonedas exhiben un nivel de volatilidad y riesgo sumamente elevado. Por consiguiente, cualquier determinación en relación a invertir debe ser abordada con mucha precaución y precedida por una investigación minuciosa.

Desde mi perspectiva, la elección de invertir requiere un análisis exhaustivo respaldado por una investigación sólida. Esto debe incluir una evaluación detenida del perfil inversor personal. Además, es recomendable aplicar una estrategia de diversificación del riesgo. Esta estrategia implica adquirir monedas en las que se confíe más y que presenten un riesgo menor. Asimismo, es posible considerar inversiones en monedas con un grado de confianza menor, pero con una posibilidad mayor de rendimientos superiores, aunque esta elección conlleve un riesgo más alto. En cualquier caso, siempre es aconsejable utilizar fondos que no sean necesarios para las necesidades cotidianas.

Es fundamental recordar que el ámbito de las criptomonedas se caracteriza por ser altamente especulativo, lo cual puede resultar en pérdidas de gran envergadura. Si se opta por invertir, es imperativo hacerlo con responsabilidad y manteniendo una plena conciencia de los riesgos inherentes involucrados en esta actividad.
