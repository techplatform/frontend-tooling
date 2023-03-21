<b> Frontend Tooling </b>

<i> 1. Rollup</i>
- What problem is this tool trying to solve?
- - Rollup helps combine smaller pieces of code into a larger library or application.
- How does it solve the problem? AKA, what makes this tool unique?
- - Rollup uses code modules that are included in the ES6 revision of JS. This means that you can import and export functions and allows you to build on top of existing tools without making your project too big.
- When shouldn't you use this tool?
- - You shouldn't use Rollup when you are code-splitting, which is where you are running two bundles simultaneously to each other.
- Name two feature you find interesting/useful and explain why they are helpful.
- 1. Rollup takes out unused functions which helps reduce the file size and runs the application better.
- 2. Rollup can verify source code as well as clean up the code to make it more readable.
- What other information should someone know before using this tool?
- - Rollup also works well with HTML, and CSS which helps beginners get familiar with the tool.

<i> 2. Webpack</i>
- What problem is this tool trying to solve?
- - Webpack helps developers transform their file formats and structures to something that their website can understand.
- How does it solve the problem? AKA, what makes this tool unique?
- - Merging all the files into what the computer understands means that it gives less wait time for the users.
- When shouldn't you use this tool?
- - This tool isn't friendly when you have a bigger project or a more complete set of files.
- Name two feature you find interesting/useful and explain why they are helpful.
- 1. Since webpack only understands JS, loaders in webpack turn the files such as CSS, HTML, SCSS, etc. into modules decreasing the size of your application.
- 2. While the entry gives a clear path to where to look and where to start the dependency graph, the output tells webpack where exactly to put it.
- What other information should someone know before using this tool?
- - Webpack is very powerful and always changing, and it can be frustrating to use but the key thing to remember is to use it on mid-projects. Don't try to use it on bigger and more important projects.

<i> 3. Esbuild</i>
- What problem is this tool trying to solve?
- - Esbuild aims to be the fastest bundler for the web.
- How does it solve the problem? AKA, what makes this tool unique?
- - One of the reasons why Esbuild is fast is because it is written in Go. Which allows for clean shared memory and data as well as allows the code to work side by side.
- When shouldn't you use this tool?
- - When you want to be very thorough with the code checks. Since it does try to get through the code with as less checks as possible, there might be some things that it might have missed.
- Name two feature you find interesting/useful and explain why they are helpful.
- 1. Esbuild is very fast compared to other bundlers because it uses parallelism.
- 2. Esbuild also uses Sourcemap which makes it easier to debug the code and look at the files as individuals and not as big jumbo files.
- What other information should someone know before using this tool?
- Esbuild also uses memory efficiently by making fewer passes through the code looking for the meat of the code. Which in return runs the compiler faster for faster output.

Compare and Contrast 

<i> Rollup </i>
- Uniqueness: Combines smaller chunks of code seamlessly with a larger one.
- Difference: Takes out unused functions - cutting down the file size.
- When to use: When working on modules that are going to be used by other developers it is best to stick with rollup.

<i> Webpack </i>
- Uniqueness: Webpack translates your understanding of your layout of files to something that will be understood by the computer.
- Difference: Very hard to use on a bigger project or bigger set of files.
- When to use: Webpack should be used for applications or when you have a lot of static assets.

<i> Esbuild </i>
- Uniqueness: Extremely fast and uses parallelism which the other two bundlers don't use.
- Difference: Runs through the code only a few times, each time focusing on one problem to solve rather than running through the whole thing for every possible check.
- When to use: Simple projects that you want a fast outcome.
