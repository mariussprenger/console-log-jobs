# console-log-jobs
This is an npm package that prints the current lemon.markets job descriptions to the console.
It can be embedded into any JavaScript-based web application.

Installation is very simple via npm:

´´´bash
npm install lemon-markets-job-descriptions
´´´

Afterwards, you can easily integrate it into your JavaScript application, e.g. in a React project.

´´´javascript
useEffect(()=>{
        async function printJobs(){
            const jobs_log = require('lemon-markets-job-descriptions');
            console.log(jobs_log)
        }
        printJobs()

                },[])
´´´

This will then print the job description to the console when the respective page is loaded. 
