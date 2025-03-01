# Checkerboard Pattern Generator
This is a Python project that generates a grayscale checkerboard pattern using Matplotlib.

## Installation
1. **Clone the Repository**  
   Open a terminal and run:
          git clone https://github.com/siewkoon/checkerboard.git
          cd repository-name

2. **Install Dependencies**
   This script requires NumPy and Matplotlib. Install them using:
        pip install numpy matplotlib

3. **Usage**
   To run the script and generate a checkerboard pattern:
        python checkerboard.py
   A window will pop up displaying the checkerboard.

4. **Changing the Colormap**
   To change the colormap, edit checkerboard.py and modify this line:
        plt.imshow(checkerboard, cmap="gray", interpolation="nearest")

   For example, change "gray" to "viridis":
        plt.imshow(checkerboard, cmap="viridis", interpolation="nearest")

   Save the file and run checkerboard.py again to see the new colormap.

5. **Contributing**
   To contribute to this project:
   a. Create a new branch:
        git checkout -b new-feature

   b. Make your changes and commit them:
        git commit -am "Added new feature"

   c. Push your branch and create a pull request.

6. **License**
   This project is open-source and available under the MIT License.