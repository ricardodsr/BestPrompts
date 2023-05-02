# Prompt to write a new code for new feature and functionality

    Prompt: 

    Act as a [Technology Name] developer. [Write a detailed description]

    Example 1:

    Act as a Python developer. Write code to read and print duplicate records from the provided CSV file.

    Example 2:

    Act as a JavaScript Developer, Write a program that checks the information on a form. Name and email are required, but address and age are not.

    Example 3:

    Act as a JavaScript Developer, Write a program that checks if a string contains a substring.

# Prompt with technology stack and other details
    Prompt:

    Act as: [Enter your profile]

    Technology stack: [Enter your technology stack]

    Functionality: [Enter functionality]

    Mandatory Fields: [Enter Fields]

    Optional fields: [Enter Fields]

    Task: [Write a task description]

    Example 1:

    Act as: Node.js Developer

    Technology stack: Node.js, Express.js, MongoDB, Mongoose

    Functionality: Newsletter

    Mandatory Fields: Email

    Optional fields: name

    Task: Make an API that takes a name and an email address as inputs and sends back a success flag.

    Example 2:

    Act as: PHP Developer

    Technology stack: Laravel 8, MySQL

    Functionality: CAGR Calculation 

    Mandatory Fields: Amount and Years

    Optional fields: NA

    Task: Write a service that calculates CAGR.

    Example 3:

    Act as: PHP Developer

    Technology stack: Laravel 8, MySQL

    Functionality: Cron

    Task: Write a cron that sends portfolio returns every day to users.

# Prompt for fixing errors and bugs
    Prompt :

    Tell me how to debug the code to solve the given error.

    Project: [Project name/description]

    Technology Stack: [Technology Stack]

    Error: [Explain the error]

    Example:

    Tell me how to debug the code to solve the given error.

    Project: eCommerce

    Technology Stack: JavaScript, Node.js, Express.js Stripe, MongoDB

    Error: Orders get placed twice for Indian users. 

    Prompt: I am getting the error: [Insert your error message here] Tell me how to fix it.

    Example: I am getting the error: Cannot get strings. key_one because property key_one is missing in undefined [1]. [1] strings?: [string_key: string]: string. Tell me how to fix this

    Sometimes we get a logical error. We can fix the error by passing our code to ChatGPT. 

    Consider the following scenario: I am calculating CAGR and getting incorrect results. I will use ChatGPT to rectify this issue.

    Prompt: I am working on the [Enter functionality], but my code is giving the wrong answer. Tell me what the error is. Here is my code. [Paste your code here]

    Example:

    I am working on the CAGR calculation functionality, but my code is giving the wrong answer. Tell me what the error is. Here is my code.

    function calculateCAGR(startValue, endValue, years)

    {

    const cagr = (Math.pow(endValue / startValue) - 1) * 100;

    return cagr.toFixed(2);

    }