1. Obtain the elements of the union between two character vectors.
vec1 = c(rownames(mtcars[1:15,]))
vec2 = c(rownames(mtcars[10:32,]))


ANSWER:
> vec1 = c(rownames(mtcars[1:15,]))
> vec2 = c(rownames(mtcars[10:32,]))
> union(vec1, vec2)
 [1] "Mazda RX4"           "Mazda RX4 Wag"       "Datsun 710"         
 [4] "Hornet 4 Drive"      "Hornet Sportabout"   "Valiant"            
 [7] "Duster 360"          "Merc 240D"           "Merc 230"           
[10] "Merc 280"            "Merc 280C"           "Merc 450SE"         
[13] "Merc 450SL"          "Merc 450SLC"         "Cadillac Fleetwood" 
[16] "Lincoln Continental" "Chrysler Imperial"   "Fiat 128"           
[19] "Honda Civic"         "Toyota Corolla"      "Toyota Corona"      
[22] "Dodge Challenger"    "AMC Javelin"         "Camaro Z28"         
[25] "Pontiac Firebird"    "Fiat X1-9"           "Porsche 914-2"      
[28] "Lotus Europa"        "Ford Pantera L"      "Ferrari Dino"       
[31] "Maserati Bora"       "Volvo 142E"   

2. Get those elements that are common to both vectors.
vec1 = c(rownames(mtcars[1:15,]))
vec2 = c(rownames(mtcars[10:32,]))

ANSWER: 
> vec1 = c(rownames(mtcars[1:15,]))
> vec2 = c(rownames(mtcars[10:32,]))
> intersect(vec1, vec2)
[1] "Merc 280"           "Merc 280C"          "Merc 450SE"        
[4] "Merc 450SL"         "Merc 450SLC"        "Cadillac Fleetwood"

3. Get the difference of the elements between two character vectors.
vec1 = c(rownames(mtcars[1:15,]))
vec2 = c(rownames(mtcars[10:32,]))

ANSWER:
> vec1 = c(rownames(mtcars[1:15,]))
> vec2 = c(rownames(mtcars[10:32,]))
> setdiff(vec1, vec2)
[1] "Mazda RX4"         "Mazda RX4 Wag"     "Datsun 710"       
[4] "Hornet 4 Drive"    "Hornet Sportabout" "Valiant"          
[7] "Duster 360"        "Merc 240D"         "Merc 230"  

