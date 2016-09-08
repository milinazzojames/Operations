# Operations


class Operations {

    public static void main (String[] args) {
        
        //Explaining order of Operations 
        System.out.println("Order of operations is math that follows a sequence called GEMDAS. Basically what it means is to complete the mathmatical function that comes first out of GEMDAS. GEMDAS stands for Grouping, Exponent, Multiplication, Division, Addition, and Subtraction.");
        
        int result = 1 + 2;
        // Grouping the result is 3
        System.out.println("(1 + 2) = " + result);
        int original_result = result;

        result = result ^ 2;
        // Expontent the result is 9
        System.out.println(original_result + " ^2 = " + result);
        original_result = result;

        result = result * 2;
        // Multiplication the result is 18
        System.out.println(original_result + " * 2 = " + result);
        original_result = result;

        result = result / 6;
        // Division the result is 3
        System.out.println(original_result + " / 6 = " + result);
        original_result = result;

        result = result + 8;
        // Addition the result is 14
        System.out.println(original_result + " + 8 = " + result);
        original_result = result;

        result = result - 7;
        // Subtraction the result is
        System.out.println(original_result + " - 7 = " + result);
    }
}
