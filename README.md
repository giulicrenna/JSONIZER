# JSONIZER
 A C++ Library to parse in a simple way JSON files

## Description

The class JSONIZER will be used for serialize and deserialize JSON files, this will be the
class used by the ESP32 firmware to deserialize the config file.
To seriliaze you will have to store the data into a vector an then, pass the vector through
the toJSON function of the class
@giulicrenna