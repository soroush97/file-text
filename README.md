# file-text
package qu9;

import java.io.File;
import java.io.FileNotFoundException;
import java.io.PrintStream;

public class QU9 {

    
    public static void main(String[] args) 
            throws FileNotFoundException {
        PrintStream out = new PrintStream(new File("C:\\Users\\mohammad\\Desktop\\message.txt"));
        out.println();
        out.println("Testing,");
        out.println("1, 2, 3.");
        out.println("This is my output file.");
    }
    
}
