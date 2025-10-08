# Digital Watermarking Service
High-performance service written in `Go` that provides a solution for digital image watermarking using `steganography`. It allows users to invisibly embed a unique trademark, signature, or any secret message within an image. This enables you to later verify your ownership of an image found online, proving it is yours even if it has been distributed without permission.

# How it works
The service employs the `Least Significant Bit (LSB)` steganography technique. This method works by modifying the last bit of each color channel (e.g., Red, Green, Blue) of a specified number of pixels in the image. The service provides a simple API to both encode a message into an image and decode a message from an image to verify its origin.

# Features
- Invisible Watermarking
- REST API
- High Performance(Go service)
