# Yulia Ignatovich

## Contact: 
**Phone:** +375333205782

**E-mail:** yuliaihnatovich@gmail.com

**Telegram:** @heyjsa

**RS School Discord name:** yuui(@hey_julia_hey)

## About me:
Active and patient listener. 
I always try different and creative approaches to solving problems. 
I'm organized and I like managing my time efficiently by using a planner and making a schedule for the upcoming day.
I don't have any job experience yet, that's why I'm curious and passionate about learning new things and improving my skills everyday.

## Skills:
Knowledge of fundamentals in C++, Java

HTML5

CSS3

JavaScript Basics

Algorithmic skills

IDE: VS Code, Eclipse, IntelliJ IDEA

## Code examples

BFS implementation Java

```
   static void bfs(ArrayDeque<Integer> q, int n, int[][] matrix, int[] visited)
    {
        while (!q.isEmpty())
        {
            int index = q.poll();

            for (int i = 0; i < n; i++)
            {
                if (matrix[index][i] == 1 && visited[i] == 0)
                {
                    q.add(i);
                    visited[i] = visit++;
                }
            }
        }
    }
```
Binary heap implementation Java
```
public class BinaryHeap {
    public static void main(String[] args) {
        long n;

        try {
            Scanner sc = new Scanner(new FileReader("input.txt"));
            FileWriter fw = new FileWriter("output.txt");

            n = sc.nextLong();

            ArrayList<Long> array = new ArrayList<>();

            while (n > 0) {
                array.add(n % 2);
                n /= 2;
            }

            for (int i = 0; i < array.size(); i++) {
                if (array.get(i) == 1)
                    fw.write(i + "\n");
            }

            if(array.size() == 0)
                fw.write(-1 + " ");

            fw.close();
        }
        catch(IOException e) {}
    }
}
```

## Education
I'm a third-year student at the faculty of Applied Maths and Computer Science in the Belarusian State University.
Studied algorithms, collections, data structures, threads, regular expressions, software design patterns in C++, Java.
Self-taught in HTML, CSS and JavaScript by reading books (Head First JavaScript Programming, Coding with JavaScript for dummies) and taking online courses such as
W3Schools Online Web Tutorials, Wes Bos (wesbos.com), freeCodeCamp.

## Languages
- Advanced English level, participated in competitions at school and have practice with native speakers as well
- Native Belarusian
- Russian
