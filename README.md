# VectorExpressions

Welcome to **VectorExpressions**! This repository contains a collection of reusable VEX (Vector Expressions) functions for Houdini. These functions are designed to simplify and optimize various tasks in Houdini, making your workflow more efficient.

## Repository Structure

- **vex/include**: This subdirectory contains all the VEX function header files.

## How to Use

1. **Clone the Repository**: Clone this repository into your Houdini user preference directory.

   ```sh
   git clone https://github.com/suhailphotos/vectorExpressions.git $HOUDINI_USER_PREF_DIR/vex
   ```
2.	**Directory Structure**: Ensure the include subdirectory within the cloned repository contains all your VEX header files.
   ```sh
   $HOUDINI_USER_PREF_DIR/vex/include
   ```
3. **Include in Houdini**: In your Houdini scripts, include the VEX functions as needed.
   ```c
   #include "kmeans.h"
   ```

## Available Functions

- **kmeanpointsclustering**: Generalized K-means clustering function for any vector attribute.
- More functions to come...
