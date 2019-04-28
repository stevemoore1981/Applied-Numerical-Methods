Similar to Finite Volume methods, Finite Element methods present a way by which we can solve a PDE in a spatial domain with a much more complex geometrical structure compared to Finite Difference methods.  
The domain is broken up into a collection of cells and  and then a spatial discretization is performed over each cell.  
A key difference in terminology however, is that the cells are usually called \emph{elements} and the vertices of the elements are usually called \emph{nodes}.  
Furthermore, the field variable $\phi$ is defined at the nodes of an element, in contrast to a cell based Finite Volume method where it was defined at the cell centroid.  
The elements used in $1D$ are simply lines, in $2D$ they are commonly triangles or quadrilaterals, and in $3D$, tetrahedra or hexahedra \(Figure \ref{Fig:ElementTypes}\).  
Just as there are higher order interpolation methods available to the Finite Difference and Finite Volume methods, with the Finite Element method we can use higher order elements to obtain a more accurate solution.  
Furthermore, the Finite Element method is also a \emph{local} method in that the discretization within an element will only involve its own nodes.  
Similar to Finite Volume methods, Finite Element methods present a way by which we can solve a PDE in a spatial domain with a much more complex geometrical structure compared to Finite Difference methods.  
The domain is broken up into a collection of cells and  and then a spatial discretization is performed over each cell.  
A key difference in terminology however, is that the cells are usually called \emph{elements} and the vertices of the elements are usually called \emph{nodes}.  
Furthermore, the field variable $\phi$ is defined at the nodes of an element, in contrast to a cell based Finite Volume method where it was defined at the cell centroid.  
The elements used in $1D$ are simply lines, in $2D$ they are commonly triangles or quadrilaterals, and in $3D$, tetrahedra or hexahedra \(Figure \ref{Fig:ElementTypes}\).  
Just as there are higher order interpolation methods available to the Finite Difference and Finite Volume methods, with the Finite Element method we can use higher order elements to obtain a more accurate solution.  
Furthermore, the Finite Element method is also a \emph{local} method in that the discretization within an element will only involve its own nodes.

$$ \frac{d\phi}{dx} = 1- \phi $$

$$\begin{aligned}
\int\limits_{0}^{10}x^2\left(a_{1}(1+x) + a_{2}(2x+x^{2})-1\right)dx &= \left[a_{1}\left(\frac{x^{3}}{3} + \frac{x^{4}}{4}\right) + a_{2}\left(\frac{2x^{4}}{4} + \frac{x^{5}}{5}\right)-\frac{x^{3}}{3} \right]_{0}^{10}	\\
&= 2833a_{1} + 25000a_{2}-333
\end{aligned}$$

