http://www.ddewey.net/mandelbrot/
  complex number = a set containing a real and imaginary number
  graph them on an XY axis (aka..."complex number plane").  X for real number, Y for imaginary
  mandelbrot set calculation: Z = Z^2 + C
  Important bit is the "magnitude" = distance from 0.  d = (a^2 + b^2)^0.5
  As Z changes, the magnitude will waver, and then eventually eject towards infinity.  Once it does that, it's out of the set.

Tutorial reviews:
  https://progur.com/2017/02/create-mandelbrot-fractal-javascript.html


HTML5 canvas
  https://www.w3schools.com/html/html5_canvas.asp


https://csl.name/post/mandelbrot-rendering/
  z0 = x + iy
  z1 = (x + iy)^2 + (x + iy) = (x^2 - y^2 + x) + i(2xy +y)
  z2 = z1^2 + (x + iy)

  For the Mandelbrot set, it means that if any point lands outside a circle with radius two around origo, the sequence will diverge.

  For the Mandelbrot set, it can be shown that the threshold value is exactly two, i.e. any sequence with a |zn| > 2 will diverge


http://slicker.me/fractals/fractals.htm
  Remember that i^2  = -1
