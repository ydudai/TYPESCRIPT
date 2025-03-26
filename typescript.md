1) typescript site
https://www.typescriptlang.org/  

2) nodejs must be installed before typescript installation.
   See https://nodejs.org/en/.
   
   Verify Node.js version:  node –v  
   Verify npm version:      npm -v  
   
3) Download typescript globaly on your computer via npm   
   npm i –g typescript
   
4) Verify tyscript version:   
   tsc -v    
    
5) Create config file: tsconfig.json in working directory    
   tsc --init
   
6) install ts-node globaly for running ts files in one step  
   npm i -g ts-node
   
7) Run typescript file with node with 2 steps  
   a) tsc index.ts (transfer to javascript file: index.js)  
   b) node index.js  
   
8) Run typescript file with ts-node with 1 step  
   a) ts-node index.ts 
   
9) Transfer *.ts file to *.js file     
   - For a single file: tsc index.ts   
   - for all files in project: tsc  

10) Build one or more projects and their dependencies, if out of date  
   tsc -b  

11) Install React + typescript via vite.   
    the same as with javascript.  but select typescript in installation.    
     
12) Run React + typescript  
    the same as with javascript.   
    npm run dev  

13) Run a single typescript [file name].ts file in 
    Use the TypeScript compiler directly:
    
    npx tsx ./src/Employee.ts   
     
    Need to install the following packages: 
    tsx@4.19.3
    Ok to proceed? (y) y     
