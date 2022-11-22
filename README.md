The implementation supports automatic differentiation for functions defined by many intrinstic operators.

|               | operator |   method |            
| :------------- | :-------------: | -------------: | 
| unary positive  | + | \_\_pos\_\_()  |  
| unary negative  | - | \_\_neg\_\_()  |
| addition        | + | \_\_add\_\_()  | 
| subtraction     | - | \_\_sub\_\_()  |
| multiplication  | * | \_\_mul\_\_()  |
| division        | / | \_\_truediv\_\_()  |
| exponentiation  | **| \_\_pow\_\_()  |
| less than       | < | \_\_lt\_\_()   |
| greater than    | > | \_\_gt\_\_()   |
| less than or equal to     | <= | \_\_le\_\_()  |
| greater than or equal to  | >= | \_\_ge\_\_()  |
| is equal                  | == | \_\_eq\_\_()  |
| is not equal              | != | \_\_ne\_\_()  |



The module Elementary will implement the various elementary functions needed for the project, and for that we will use numpy. Each elementary function will thus call the corresponding function from numpy if there is already an implementation in it, otherwise we will implement it manually. We will also consider different cases for the input (if the input is a dual number, or if it is not a dual number). 

|                            |                |        
| :-------------             | -------------: |
| Trigonometric              | sin, cos, tan, arcsin, arccos, and arctan |
| Hyperbolic Trigonometric   | sinh, cosh, tanh, arcsinh, arccosh, and arctanh | 
| Exponential                | exp, sqrt,ln, $log_2, log_{10}$  |



NumPy Elementary Mathematical Functions
These mathematical functions takes a single array of any dimension as input and returns a new array of the same shape.

Functions	Description
np.cos(), np.sin(), np.tan()	Trigonometric functions.
np.arccos(), np.arcsin(), np.arctan()	Inverse trigonometric functions.
np.cosh(), np.sinh(), np.tanh()	Hyperbolic trigonometric functions.
np.arccosh(), np.arcsinh(), np.arctanh()	Inverse hyperbolic trigonometric unctions.
np.sqrt()	Square root.
np.exp()	Exponential.
np.log(), np.log2(), np.log10()	Logarithms of base e, 2, and 10, respectively.

- sin()
- cos()
- tan()
- log()
- sqrt()
- exp()
- sinh()
- cosh()
- tanh()

