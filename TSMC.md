# TSMC project 


## Transfer unit 

### Pure Material
|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|
|1500|1700| 800| 600 
- Assambe line L x2 Transfer unit
- Metalwork indu Standard Frame  L
- Metalwork indu Basic  Robotic Arm  L
- Metalwork indu Basic  hydraulics
- Metalwork indu Basic Pipe
- smelter indu Steel product
- smelter indu Silumin product
- basic electrnic indu



```mermaid
flowchart TB

node[Silicon]--test -->node2[Silumin]
node3[aluminium] -->node2
node2-->node4[basic pipe]
node6[steel] --> n7[hydraulics]
node4-->n7

node_v2[Silicon]-->node2_v2[Silumin]
node3_v2[aluminium] -->node2_v2
node2_v2-->node4_v2[basic pipe]

node_v3[Silicon]-->node2_v3[Silumin]
node3_v3[aluminium] -->node2_v3
node_alum_v3["aluminium"] -->node1_v3
nodeiron_v3[iron]-->node1_v3[Al-Fe Alloy]
node1_v3-->node4_v3[basic Component]
node2_v3 --> node_robotic_v3
node4_v3--> node_robotic_v3[Robotic Arm  L]

node_v4[Basic Standard Frame L]--> nodeTransfer
node4_v2[basic pipe] --> nodeTransfer[Transfer Unit]
n7--> nodeTransfer
node_robotic_v3 --> nodeTransfer
 ```
 
 ## container L
|material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|3800|200|800| 1700 
-Assembly line L
## Assembly lines 
### XS 

|material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|15|15|15| 15 

### S

Assembly line XS
 |material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|80|80|80|80
 
### M
Assembly line S
 |material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|400|400|80|100 

### L
Assembly line M
 |material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|2000|2200|250|600 

### XL
Assembly line L

 |material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|12000|12000|1700|4000 

##  Chemical industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon|
|-|-|-|-|-|
|amount|300|500|60|70 

##  Electronics industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon|hydr.|
|-|-|-|-|-|-|
|amount|200|300|60|260|100|

##  Glass Furnace 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|350|300|140|150||

##  Honeycomb Refinery 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|300|500|60|50||
##  Metalwork Industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|300|450|60|70||
##  Smelter Industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|300|350|160|140||

##  Recycler Industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|300|350|160|140||
##  Refiner Industry 

---Assembly line M

|material|Iron|aluminium|Silicon|carbon||
|-|-|-|-|-|-|
|amount|300|450|70|70|

