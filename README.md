#TESSERACT-OCR(JAVA) Netbeans Project
It Converts images of all formats like(jpg,png,gif etc.) into text formats.

#INSTALLATION OF TESSERACT-OCR

Step 1: Copy both zip/folder into same directory and extract it , if you didn't.
Step 2: import both project into Netbeans/eclipse.
Step 3: set tessdata datapath into main.java(tesseracttest/source packages/tesseracttest/Main.java)

		instance.setDatapath("C:\\Users\\mukul\\Desktop\\tessract\\Tess4j\\Tess4J\\tessdata");
		
		This tessdata folder you will find in tess4j folder.
		
Step 4: Now  give any image file path in Main.java 
Step 5: Clean and build the project and run , you will get the output in text format.