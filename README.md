Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

-The Wolf PAX app was developed to provide small business owners, shop managers, and entrepreneurs with an efficient, 
user-friendly inventory management system. Its main goals include real-time stock tracking, barcode scanning, import/export 
of inventory data, and ensuring data security and accessibility. It addresses the need for a simple, reliable, 
mobile solution for inventory control, especially for users managing small-to-medium scale operations.

What screens and features were necessary to support user needs and produce a user-centered UI for the app?
How did your UI designs keep users in mind? Why were your designs successful?

-The app included the following essential screens and features:
Inventory list screen (data grid with logical labels and headers), Add/Edit item screen, Delete functionality (per item row), 
Barcode scanner interface, CSV import/export controls, Login screen (if implemented)
The UI focused on clarity, minimalism, and fast navigation, using a clean color scheme and iconography (e.g., the wolf pack logo).
The inclusion of visual feedback (like low-stock alerts), simplified data input, and logical layout demonstrated a user-centered 
design philosophy, enhancing usability for non-technical users. The UI was successful because it minimized clutter, supported 
task-based workflows, and reduced friction in frequent actions like searching or updating stock.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

-The coding process followed a modular and structured approach, starting with setting up the UI components, followed by backend 
logic (CRUD with SQLite), and then integrating features like barcode scanning and CSV import/export. Key techniques included:
Using SQLite for secure local storage, Managing permissions based on Android version, Separating UI and logic for maintainability and
Testing features incrementally.
These strategies help build scalable, readable, and efficient apps and can be reused in future projects that involve data handling,
multi-screen navigation, or permission-sensitive features.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

- Testing involved:
Manual testing on emulator and physical devices, Running edge case scenarios (e.g., empty input, invalid barcode)
Verifying file operations across Android SDK versions, and Ensuring UI responsiveness and data persistence
This process is crucial for detecting bugs, improving performance, and ensuring the app behaves consistently across devices.
It revealed the importance of version-specific handling (e.g., scoped storage in Android 13+), and helped verify the barcode
scanner and database operations were robust.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

- A key innovation was handling file storage and permissions across different Android versions. Implementing scoped storage for
Android 13+ while still supporting legacy file access required research and careful coding. Additionally, integrating barcode scanning
in a lightweight and efficient way also posed challenges, which were solved by utilizing open-source libraries compatible with newer SDKs.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

- The SQLite database integration stands out as a strong demonstration of backend knowledge. The ability to add, update, delete, and
 persist inventory items locally, along with CSV file import/export, highlights competence in data management, Android file systems,
and user data control. It shows a solid grasp of app architecture, storage mechanisms, and real-world usability.










