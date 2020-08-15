# Topic: Modularity
## Execise1 : Code division into files

### Summary:
The 25-pair color code, is used to identify wires in telecommunications cables. Different codes are used for wire leads on devices such as transformers or in building wiring. For more details refer to [This Wiki](https://en.wikipedia.org/wiki/25-pair_color_code). 
There are 25 pairs of colors. 
 - Each pair number can be mapped to a pair of colors - a major color and a minor color
 - Each pair of colors can be mapped to the pair number it corresponds to

### Exercise Details:
A feature request arises for which an implementation needs to be added to the class.
The color coding needs to be printed as a reference manual for the concerned telecom personnel.
Provide a ToString() function in the code that would return the mapping which can be printed as a manual.
Also resolve any coding guideline violations.

### Source code details:
 The implementation of this feature provides the above mentioned mapping between the pair number and the color pair. 

 ##### File Details:
| FileName | Description |
| ------ | ------ |
| Program.cs | Provides the functionality of the color coder, also has main method to test the same |

 ##### Class and Method Details:
| Entity | Name | Description |
| ------ | ------ | ------ |
| Class | Program | Contains the implementation of the ColorCoder functionality |
| Class | ColorPair | Helper class for encapsulating themajor and minor color. |
| Method | GetColorFromPairNumber | Given pair number return the 2 colors mapping to the number|
| Method | GetPairNumberFromColor | Given the colors, return the pair number corresponding to them|

