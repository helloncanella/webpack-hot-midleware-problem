#webpack-hot-middleware/client problem

I'm trying to use webpack:typescript package.

For unknown reasons I'm getting 

`
ERROR in multi main
Module not found: Error: Cannot resolve module 'webpack-hot-middleware/client' in /home/hellon/Desktop/ok
 @ multi main
`

After some googles and trials, I didn't get anywhere.

The completed log is 

`
Asset     Size  Chunks       Chunk Names
web.js  22.8 kB       0       main
chunk    {0} web.js (main) 73 bytes [rendered]
    [0] multi main 40 bytes {0} [built] [1 error]
    [1] ./app/learn.ts 33 bytes {0} [built]
`

`
ERROR in multi main
Module not found: Error: Cannot resolve module 'webpack-hot-middleware/client' in /home/hellon/Desktop/ok
 @ multi main`
`
