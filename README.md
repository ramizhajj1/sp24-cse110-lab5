# Lab 5 - Starter    

Link to pages:    https://ramizhajj1.github.io/sp24-cse110-lab5/  
https://ramizhajj1.github.io/sp24-cse110-lab5/expose.html  
https://ramizhajj1.github.io/sp24-cse110-lab5/explore.html  

Explore part 3:    

Partner: Michelle



1) Yes, unit testing is highly recommended for this feature of a messaging application, because it allows you to test each component of the feature in isolation. Unit tests are designed to validate individual units of code to ensure they perform as expected under various conditions. In the context of a messaging feature, this could involve testing the functionality for creating, sending, and receiving messages independently. For example, you could test whether a message object is created correctly with all necessary attributes like sender, recipient, timestamp, and content. Additionally, you would verify that the send function correctly handles the message data, ensures it is routed to the intended recipient, and interacts appropriately with the database or server. Similarly, the process of receiving messages can be tested to confirm that messages are correctly retrieved and displayed to the recipient. By isolating these components in unit tests, developers can quickly identify and fix bugs in the messaging logic, enhancing the reliability and robustness of the application. Finally, unit tests can be automated and run frequently, providing continuous feedback during development and maintenance phases, ensuring that new changes do not break existing functionality.  
2) Yes, using a unit test to test this feature of a messaging application is both appropriate and advantageous. This feature, which limits user inputs to no more than 80 characters, is ideally suited for unit testing because it involves a specific, isolated piece of functionality that can be tested independently of other components. In unit testing, you would simulate input scenarios where text is provided to the message input field, checking that the application correctly enforces the 80-character limit. This might include tests where the input exactly matches the limit, slightly exceeds it, or falls under it. The key is to ensure the application behaves as expected in each scenario, such as preventing additional characters from being entered or providing user feedback when the limit is exceeded. Unit testing this feature helps in early detection of errors, ensuring consistent behavior throughout development, and providing quick feedback to developers. Moreover, these tests can be automated and integrated into a continuous integration pipeline to ensure that subsequent changes to the code do not inadvertently break this functionality.
