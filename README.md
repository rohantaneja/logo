<div align="center">
	<h1>Portfolio Logo Designing (SVG)</h1>
	<img src="./logo.svg">
	<p align="center"> The repo contains creation of portfolio logo using scalable vector graphic.
	</p>
</div>

### Background
This little project dates back to 2019 when I first explored designing and developing scalable vector graphics (or SVGs). Recently while exploring XML in-depth I have improved my static logo and rewritten it using SVG. You can find the original image as **logo.svg** in this repo.

#### Motivation
SVGs are disruptive 2D image introduced in 2002. Using initials anyone can create amazing personalized logos. The idea is to promote the readers on designing professional presence on online.

### The Code
Enough talking, show me the code.

**Circle (with stroke)**
This is pretty straightforward.
- Define 50 px centre along x and y axis
- Radius is set to 45 px while keeping the stroke width set to 5 px
```svg
<circle
		cx="50"
		cy="50"
		r="45"
		stroke="#00b0ff"
		stroke-width="5"
/>
```
**rt.**
- As defined with respective id the shapes are designed using tag _< path >_
- The font is structured by myself resembling to Google's Roboto.
_Note: Transform is used to place the logo in accord to your preference._
```svg
<g  transform="translate(25.000000, 40.000000)">
	<path  d = "M 10.726 5.25
				L 10.726 8.777
				A 11.369 11.369 0 0 0 8.859 8.634
				Q 5.127 8.634 3.794 11.813
				L 3.794 27.563
				L 0 27.563
				L 0 5.373
				L 3.691 5.373
				L 3.753 7.937
				Q 5.619 4.963 9.044 4.963
				Q 10.151 4.963 10.726 5.25 Z"
			fill="#00b0ff"
			id = 'r'
	/>

	<path  d = "M 15.565 0
				L 19.359 0
				L 19.359 5.373
				L 23.502 5.373
				L 23.502 8.306
				L 19.359 8.306
				L 19.359 22.066
				A 3.073 3.073 0 0 0 19.913 24.066
				A 2.332 2.332 0 0 0 21.8 24.732
				A 9.185 9.185 0 0 0 23.604 24.486
				L 23.604 27.563
				A 10.999 10.999 0 0 1 20.692 27.973
				A 4.725 4.725 0 0 1 16.857 26.435
				Q 15.565 24.896 15.565 22.066
				L 15.565 8.306
				L 11.525 8.306
				L 11.525 5.373
				L 15.565 5.373
				L 15.565 0 Z "

			fill = '#00b0ff'
			id = 't'
	/>

	<path  d = "M 28.014 25.573
				Q 28.014 24.589 28.598 23.933
				A 2.227 2.227 0 0 1 30.352 23.276
				A 2.294 2.294 0 0 1 32.125 23.933
				A 2.328 2.328 0 0 1 32.73 25.573
				A 2.202 2.202 0 0 1 32.125 27.152
				Q 31.521 27.788 30.352 27.788
				Q 29.183 27.788 28.598 27.152
				Q 28.014 26.517 28.014 25.573 Z"
	fill="#00b0ff"
	id = 'dot'
	/>
</g>
```