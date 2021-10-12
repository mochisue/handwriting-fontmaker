# handwriting-fontmaker

An application that creates fonts based on handwritten text.

# Development Record

- I tried to use [tesseract](https://github.com/tesseract-ocr/tesseract) to automatically recognize characters, but it was difficult to recognize handwritten characters, so I gave up.

- I will use [potrace](http://potrace.sourceforge.net/) for tracing. I tried [scipy's curve fitting](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html) and [Simon Cozens's library](https://github.com/simoncozens/beziers.py} , but potrace was by far the best in terms of speed and accuracy.

# Author

[mochisue](https://github.com/mochisue)

# Licence

[MIT](https://github.com/mochisue/pyqt-async-sample/blob/main/LICENSE)
