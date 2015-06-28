Based on code written by Donald Blake from avrfreaks.net.

These modifications provide a register-based interface to I2C (TWI). The previous version of the code exposed the I2C data stream as a byte stream, not a series of read or write operations on registers, which is how I2C is usually described.