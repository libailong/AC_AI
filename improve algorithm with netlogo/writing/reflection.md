# Reflection by Bailong Li

<h2>Explanation<h2/>

 Here is the Reflection after read A* code. In the code, at beginning, we have open and closed. All of the searching area are concluded in open and closed. To be specifics, `open` is the area that has not been searched but it is ready to be searched. It is like frontier. However, `closed` is the area that has been searched and we can call that interior.

In addition, we also learned a equation in the class about A* : `f(x) = g(x) + h(x)` which is means f is total cost(econ major student interpretation) g is the cost that we have been spent and h is what we need to spend in the future. Therefore, we are trying to minimize f in this case.

In order to achieve our goal, find a shortest way to destination, we need search area first. In the code, after we finished the search of one spot we need move it from `open` to `closed` and the first open spot is `source` in this case where is our starting point. we will finish the program when there are no point in the `open`. That means we found the destination.

<h3>Changes<h3/>

I made three changes of this code and each of them improve this program a little bit.

First, I changes the position of the colored annotation. It covered each other in the past. I made all of them clear enough to see.

Second, I changes the color of path that was black so I sometimes mess up it with unknown area. I changed to grey that make path more clear.

third, I changed the outlook of terminal that was too small to see. I resized it and make it better to find information.

<h4>Final<h4/>

All of these changes did not affect the functions of this program so there will not have more information to add under the application in the info.

This program is useful and it could be use by GPS and auto dive car. It may also be used by the astronautics to explore the unkown area with robot.
