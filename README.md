# Subsitute
Subsitute methods
public class smth {
    public static void main(String[] args) {

        String hello = "Hello World!";
        String newString = "";
        int stringUzun = hello.length();
        int index = 0;




        while(index < stringUzun){
            char findChar = hello.charAt(index);
            if(findChar == 'o'){
                newString = newString + 0;

            }else {
                newString = newString + findChar;

            }
                index++;

        }

        System.out.println(newString);
