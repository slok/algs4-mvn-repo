**These libraries aren't mine, this is only a maven repository.
The copyright of this code belongs to the original authors not me**

Maven repository for algorithms and data structures Coursera course

To add the libs to your project. Add this repository to ``<repositories>`` block:

    <repository>
      <id>org.coursera.algs4</id>
      <name>Algs4 coursera course custom repository</name>
      <url>https://raw.github.com/slok/algs4-mvn-repo/master</url>
    </repository>

And then the dependencies to ``<dependencies>`` block:

    <dependency>
      <groupId>edu.princeton.cs.introcs</groupId>
      <artifactId>algs4-package</artifactId>
      <version>1.0</version>
    </dependency>

    <dependency>
      <groupId>edu.princeton.cs.introcs</groupId>
      <artifactId>stdlib-package</artifactId>
      <version>1.0</version>
    </dependency>

Alternatively to use dependencies without packages use the following dependencies.

	<dependency>
	  <groupId>org.coursera.algs4.algs4</groupId>
	  <artifactId>algs4</artifactId>
	  <version>1.0</version>
	</dependency>
    
	<dependency>
	  <groupId>org.coursera.algs4.stdlib</groupId>
	  <artifactId>stdlib</artifactId>
	  <version>1.0</version>
	</dependency>

In August 2015 the authors have merged stdlib into algs4.jar and moved classes into 'edu.princeton.cs.algs4' package.
To use this variant add the following dependency:

	<dependency>
	  <groupId>edu.princeton.cs.algs4</groupId>
	  <artifactId>algs4</artifactId>
	  <version>1.0</version>
	</dependency>
	





