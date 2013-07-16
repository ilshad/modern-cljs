# Tutorial 18 - Less is more

In the [previous tutorial][1] we injected the form validators into the
corresponding WUI (Web User Interface) in such a way that the user
will be notified with the corresponding error messages when the she/he
types in invalid values in the form. Although this series of tutorials
is mainly dedicated to CLJS, to be respectful with the progressive
enhancement strategy, we started to inject the form validators into
the server-side code first. 

## Introduction

In this tutorial we're coming back to the client-side code by
injecting the form validators into the CLJS code we implemented in the
[Tutorial 10 - Introducing Ajax ][2].


> NOTE 1: I suggest you to keep track of your work by issuing the
> following commands at the terminal:
>
> ```bash
> $ git clone https://github.com/magomimmo/modern-cljs.git
> $ cd modern-cljs
> $ git checkout tutorial-17
> $ git checkout -b tutorial-18-step-1
> ```

The most direct path towards our
objective of integrating the form validators in the client-side code
is apparantly to refactor the original CLJS code based on the
[Domina][3] library to make room for the validators themselves.


# Next Step - TO BE DONE

TO BE DONE

# License

Copyright © Mimmo Cosenza, 2012-13. Released under the Eclipse Public
License, the same as Clojure.

[1]: https://github.com/magomimmo/modern-cljs/blob/master/doc/tutorial-17.md



[2]: https://github.com/cgrand/enlive
[3]: https://github.com/magomimmo/modern-cljs/blob/master/doc/tutorial-14.md
[4]: https://github.com/magomimmo/modern-cljs/blob/master/doc/tutorial-15.md#break-the-shopping-calculator-again-and-again
[5]: https://raw.github.com/magomimmo/modern-cljs/master/doc/images/ServerNullPointer.png
[6]: http://en.wikipedia.org/wiki/Syntactic_sugar
[7]: http://en.wikipedia.org/wiki/Closure_(computer_science)
[8]: http://en.wikipedia.org/wiki/Higher-order_function
[9]: https://raw.github.com/magomimmo/modern-cljs/master/doc/images/price-error.png
[10]: http://localhost:3000/shopping.html
[11]: https://github.com/weavejester/hiccup
[12]: https://github.com/weavejester
[13]: https://github.com/cemerick/pomegranate
[14]: https://github.com/cemerick
[15]: https://github.com/cgrand
[16]: https://github.com/cgrand/enlive/blob/master/src/net/cgrand/enlive_html.clj#L959
[17]: https://github.com/cgrand/enlive/blob/master/src/net/cgrand/enlive_html.clj#L538
[18]: http://www.clojurebook.com/
[19]: https://github.com/lynaghk/cljx
[20]: https://github.com/swannodette/enlive-tutorial/
[21]: http://localhost:3000/shopping.html
[22]: https://raw.github.com/magomimmo/modern-cljs/master/doc/images/shopping-invalid-values.png
[23]: https://raw.github.com/magomimmo/modern-cljs/master/doc/images/shopping-with-invalid-messages.png
[24]: https://github.com/magomimmo/modern-cljs/blob/master/doc/tutorial-15.md
[25]: https://github.com/rkneufeld
[26]: https://github.com/rkneufeld/lein-try
[27]: https://github.com/rkneufeld/lein-try/issues/3
