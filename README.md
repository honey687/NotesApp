This task focuses on File Input/Output (I/O) in Java, which is the mechanism for a program to communicate with files on the disk.
 * I/O Streams: Java handles I/O using streams, which are sequences of data flowing into (input) or out of (output) the program.
 * Character Streams: The notes app deals with text, so it uses character streams (like Reader/Writer), which handle text data efficiently by encoding characters.
 * FileWriter: This class is an output stream used to write character data (the note content) to a file. It creates the file if it doesn't exist.
 * FileReader: This class is an input stream used to read character data from a file back into the program.
 * Data Persistence: The core concept is persistence—saving data (notes) so they remain intact even after the program closes, allowing them to be retrieved later.
 * Error Handling: File I/O operations can fail (e.g., file not found, permission issues), so they require try-catch blocks to handle the resulting IOException.
 * Resource Management: It's crucial to close the streams (writer.close(), reader.close()) after use to free system resources and ensure data is fully flushed (written) to the file.
 * BufferedReader (Optional): This class is often used to wrap a FileReader because it provides an efficient readLine() method, simplifying the reading of text line-by-line.
 * Path: The program specifies the file path (e.g., "notes.txt") to connect the Java stream to the actual file location on the system.
 * File: The notes themselves are stored as plain text in a simple file on the hard drive.
