## about the requirement dataset : 
- ```net_manager``` : code of regional network manager
- ```Purchase_area```: code of the area where the energy is purchased
- ```street```: Name of the street
- ```zipcode_from``` and ```zipcode_to```: 2 columns for the range of zipcodes covered, 4 numbers and 2 letters
- ```city```: Name of the city
- ```num_connections```: Number of connections in the range of zipcodes
- ```delivery_perc```: percentage of the net consumption of electricity or gas. The lower, the
more energy was given back to the grid (for example if you have solar panels)
- ```perc_of_active_connections```: Percentage of active connections in the zipcode range
- ```type_of_connection```: principal type of connection in the zipcode range. For electricity
is # fuses X # ampère. For gas is G4, G6, G10, G16, G25
- ```type_conn_perc```: percentage of presence of the principal type of connection in the
zipcode range
- ```annual_consume```: Annual consume. Kwh for electricity, m3 for gas
- ```annual_consume_lowtarif_perc```: Percentage of consume during the low tarif hours.
From 10 p.m. to 7 a.m. and during weekends.
- ```smartmeter_perc```: percentage of smartmeters in the zipcode ranges

## Task 1 : database structure 
#### One database with 2 Collection (Gas, Electricity)

![uah image dau r]('C:/TaiLieuHocTap/RMIT\C-2023/BigData/asignment2/As2-EEET574/-_-/collections.png')
