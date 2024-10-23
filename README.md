# CS230


    Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room is a client that wanted to take their existing Android game, Draw It or Lose It, and expand it into a web-based version that works smoothly across platforms, including mobile and desktop. The game is team-based, where players guess images, and the requirements were focused on making sure it supports multiple teams, unique names for games and teams, and runs efficiently with just one instance of the game in memory at a time.
    
    What did you do particularly well in developing this documentation?
I think I did a good job of breaking down the design constraints and addressing the technical needs clearly. For example, I explained how the Singleton pattern would help manage the memory by ensuring only one instance of the game runs at a time, which was a key requirement. I also made sure to highlight the importance of cross-platform compatibility, which is a big part of the project.
    
    What about the process of working through a design document did you find helpful when developing the code?
The design document really helped me map out the overall architecture before coding. It was useful seeing how the different components would interactand It gave me a more structured approach. These things made writing the code more straightforward since I knew exactly what the system needed.    
    
    If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
    If I could go back and change one thing, I would enhance the Evaluation section by adding more details on performance across different platforms. I would probably go deeper into the potential issues like mobile performance and network delays in order to ensure the game runs smoothly and efficiently no matter what device it’s on.
    
    How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
    I interpreted the user’s needs by focusing on their main goals: making sure the game worked across multiple platforms, handled teams and players efficiently, and kept things like game and team names unique. I implemented these needs by choosing the right tools and using design patterns like Singleton to keep the game optimized.
It’s important to keep the user’s needs front and center because that’s what makes the software successful. If the design doesn’t meet the client’s expectations, it could lead to poor performance or user frustration, which would lead to poor satisfaction from the customer.

    How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
When designing the software, I kept things simple. I used object-oriented principles and the Singleton pattern for managing memory. Moving forward, I’d focus more castching potential issues quicker, making sure the code is scalable and also make sure testing is donecontinuously across all platforms to avoid any problems later.
