
该解在局部变量中使用 `count`，但是在 `counter` 中直接添加了方法。它们共享同一个外部词法环境，并且可以访问当前 `count`。