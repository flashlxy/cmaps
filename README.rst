cmaps
=========

Make it easier to use user defined colormaps in matplotlib.

Users can define a environmental variable CMAP_DIR pointing to the folder containing the self-defined rgb files.


Installation::

    git clone https://github.com/hhuangmeso/cmaps.git
    cd cmaps
    python setup.py install


Usage::

    import matplotlib.pyplot as plt
    import cmaps
    import numpy as np

    a=np.random.rand(100,100)
    plt.pcolormesh(a,cmap=cmaps.BlueDarkOrange18)
    plt.colorbar()
    plt.show()
