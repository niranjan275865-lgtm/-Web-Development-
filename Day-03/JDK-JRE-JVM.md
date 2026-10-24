# JDK, JRE and JVM

## 1. JVM (Java Virtual Machine)

**Definition:** JVM stands for Java Virtual Machine. It executes Java bytecode.

**Functions:**
- Executes Java bytecode.
- Helps Java programs run on different operating systems when a compatible JVM is available.

## 2. JRE (Java Runtime Environment)

**Definition:** JRE stands for Java Runtime Environment. It provides the environment needed to run Java programs.

**Components:**
- JVM
- Supporting libraries and runtime components

## 3. JDK (Java Development Kit)

**Definition:** JDK stands for Java Development Kit. It provides tools to develop, compile, and run Java programs.

**Components:**
- Java compiler (`javac`)
- Java runtime components
- Other development tools

## 4. Difference Between JDK, JRE and JVM

| JDK | JRE | JVM |
|---|---|---|
| Java Development Kit | Java Runtime Environment | Java Virtual Machine |
| Develops and compiles Java programs | Provides the environment to run Java programs | Executes Java bytecode |
| Includes development tools and runtime components | Includes runtime components | Part of the runtime architecture |

## 5. Java Program Execution

Example: `Demo.java`

```text
Demo.java
    |
    v
JDK Compiler (javac)
    |
    v
Demo.class (Bytecode)
    |
    v
JVM
    |
    v
Output: Hello World
```

**Steps:**
1. Write the program in `Demo.java`.
2. The compiler (`javac`) converts the source code into bytecode.
3. The bytecode is stored in `Demo.class`.
4. The JVM executes the bytecode.
5. The program displays `Hello World`.

**Where is the JRE?**

In the traditional Java architecture, the JRE provides the runtime environment containing the JVM and supporting components.

## 6. Relationship Between JDK, JRE and JVM

- JDK = Development tools + Runtime components
- JRE = JVM + Supporting runtime components (traditional architecture)
- JVM = Executes bytecode

*Note: Modern Java versions do not always provide a separate JRE installation.*

## 7. Memory Trick

- **JDK** — Develop
- **JRE** — Run environment
- **JVM** — Execute bytecode

**Remember:** JDK helps us develop Java programs, JRE provides the runtime environment, and JVM executes Java bytecode.
