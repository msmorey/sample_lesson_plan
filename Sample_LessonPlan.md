# 13.3 Big Data Tools

## Overview

Today's class will introduce Hadoop, Spark, and MapReduce to students, teaching them the fundamental differences between dealing with Small Data and Big Data. 

## Learning Objectives
By the end of class, students will be able to:

* **Explain** that Hadoop is both a data storage tool and a data processing tool for use with Big Data.

* **Explain** that Spark was built on top of the Hadoop MapReduce system and that Hadoop and Spark are often used together.
* **Build** simple MapReduce jobs. 

* **Explain** the similarities between Spark dataframes and Pandas dataframes.

* **Use** Google Colab to work together on projects.

* **Use** Spark in Google Colab to import a csv as a dataframe and manipulate it. 

## Instructor Prep

<details>
    <summary><strong>Instructor Notes</strong></summary>

* In this lesson, you will describe the foundational concepts of Big Data processing using Spark and Hadoop as catalysts; this lesson plan has several helpful analogies and explanations, so it is recommended that you read it in full prior to class. 

* The class starts with a slide show introducing Spark and Hadoop, then asks students to research alternatives in groups of 3. Later, the class transitions to technical work in MapReduce and concludes with a group activity importing a CSV using Spark on Google Colab.

* Students will try to make things complicated in this class - look to reinforce that large volumes of data actually require _less_ complicated solutions than they've been used to dealing with in order to preserve computational resources. It's ok if it seems simple!

* Your students will likely be asking many career related questions in this section; feel free to use your own personal background to answer questions, but also remind students that each company they work with will have a completely different data stack. Their most valuable resource is confidence in picking up new tech. 

</details>

_ _ _

# Class Activities

## 1. Introducing Hadoop and Spark


<details>
  <summary><strong>1.1 Instructor Do: Tools of the Trade (0:05)</strong></summary>

* Start by opening up the [slideshow](https://docs.google.com/presentation/d/1w0LO0aZotHb05TYx0s8klPOl8JiI03lz76nk9KU8Lgk/edit?usp=sharing) and step through slides 1-3

    * Emphasize that Hadoop is a fully featured Big Data framework that both stores and processes data while Spark only processes data.

    * Each platform utilizes distributed computing, leveraging many smaller computers to do small pieces of a task.

    * Explain that MapReduce is a process that we will learn about later in this class, but in essence it is a method to perform a simple action on an enormous amount of data.

    * Make sure to connect the dots; Spark was built to enhance the processing power of Hadoop (specifically that of MapReduce), but it does not replace the storage (HDFS). 

    * **ANALOGY:** Spare change can be put into rolls using plastic coin sorters; MapReduce can be thought of as the plastic sorter, and Hadoop Distributed File System (HDFS) can be thought of as the paper rolls the coins get stored in. Simple but effective. Spark can be thought of as an automated coin sorting machine; it accomplishes the same tasks as the plastic sorter _much_ more quickly but still puts the coins into the same rolls (HDFS) at the end.

* After going over the uses for both technology, transition to posing the question "are these the only players in Big Data processing?"

</details>


<details>
  <summary><strong>1.2 Students Do: Scout the Competition (0:10)</strong></summary>

* Introduce the assignment per the [README](Activity_README.md)

</details>

<details>
  <summary><strong>1.3 Everyone: Review (0:05)</strong></summary>

* Briefly go over a few of the alternatives the students found; don't worry if you haven't used them before as the main point is that _it's ok_ if you don't have direct experience with every product.

* Point out how many alternatives there are and how many stories there are about the "aging" nature of Hadoop. 

* Using slide 4, assure your students that Hadoop and Spark are perfectly suited to learning the foundations of Big Data processing, and that those foundations will translate well to whatever environment they end up working in for their career.

* **ANALOGY:** There are a bajilliion models of cell phone on the market - learning how to use one of them will help you understand all of them.

</details>



