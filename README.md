# Impulse Grenade
A simple mod that replaces the stun effect with a velocity boost.

The added Velocity is calculated like this: `-1/radius * pow(len, 2) + radius` where `radius` is the damage radius of the grenade and `len` is the magnitude of the vector from grenade origin to player origin.

![inverse square law example](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Illustration_of_Inverse_Square_Law%2C_extracted_from_Radiation_safety_and_control_manual%2C_June_1%2C_1961.png/640px-Illustration_of_Inverse_Square_Law%2C_extracted_from_Radiation_safety_and_control_manual%2C_June_1%2C_1961.png)

This mod only changes ammo refill, ignite time, deploy time, cook time, damage and velocity calculations. Unexpected behaviour may occur.