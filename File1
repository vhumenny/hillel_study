package Homework13;

import java.util.ArrayList;
import java.util.Collections;
import java.util.Random;

public class Lottery {

    public static void main(String[] args) {

        Random random = new Random();

        int size = 7;

        ArrayList <Integer> first = new ArrayList<>();
        ArrayList <Integer> second = new ArrayList<>();
        for (int i = 0; i < size; i++) {
            first.add(i, random.nextInt(0, 9));
            second.add(i, random.nextInt(0, 9));
        }
        Collections.sort(first);
        Collections.sort(second);

        ArrayList <Integer> numbersGuessed = new ArrayList<>();
        for (int i = 0; i < size; i++) {
            if (first.get(i)==second.get(i)){
                numbersGuessed.add(i);
            }
        }
        System.out.println("Numbers guessed by the company: "+first+"\nNumbers guessed by the player: "+second+
                "\nSequence number of matched numbers: " +numbersGuessed);
    }
}
