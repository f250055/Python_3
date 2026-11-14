# PAI Assignment 3: NumPy, Pandas and Matplotlib

## How to run
1. Install the libraries: `pip install numpy pandas matplotlib`
2. Keep the folder layout as it is, with the notebook next to the `data/` folder.
3. Open `Assignment3_Programming_for_AI.ipynb` in Jupyter or VS Code and choose **Restart and Run All**.
4. The notebook saves `dashboard.png`, `dashboard.pdf` and `wave.gif` in `outputs/`.

## One thing that was hard
Telling views from copies in NumPy. Slicing returns a view, so writing into a slice silently changed the original array (Q1 and Q2d). I fixed it by using `.copy()` and printing the original array after each change.