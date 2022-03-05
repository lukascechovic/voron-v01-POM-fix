# voron-v01-POM-fix
Originally used for LDO v0.1 kit rev C Anti Backlash Nut, POM, Tr8X8, fix if you got Z binding-skipping on default Z motor current 0.37A, with good Z axis alignment

**Issue: Z motor is binding/skipping at default 0.37A current with empty bed, with properly aligned parts (Z leadscrewand  POM nut holder)**
[Video](https://youtu.be/tI24zk7298Q )

hm.. increase Z motor amps to 0.5A-0.55A solve this but at the cost of grinding POM plastic part down and potentialy harm other parts of printer (head) as you really dont wanna super strong Z power (imagine Z endstop wont trigger)

**Suspected reason of this happening - spring on POM nut has thick wire, is short, with few "rings" which creating uneven pressure on POM nuts edge, it is creating shear force locking nuts into leadscrew, it kills tolerance you need for other sma,l missalignments which always occurs as there is NO way to have Z pefrectly squared**

**Solution1 - relieve spring tention with 3D printed spacer**

![Picture](pictures/spacer_model.jpg)
![Picture](pictures/POM_with_spacer.jpg) 

**Solution2 - replace spring with one with thinner wire and more rings**

![Picture](pictures/POM_spring_variations.jpg)
![Picture](pictures/POM_with_replacement_spring.jpg)

Do not use brass nuts on ptfe coated LDO kits leadscrew, it grinds the leadscrew down.

**TODO**
upload CAD File
