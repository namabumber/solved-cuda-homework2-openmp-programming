Download Link: https://assignmentchef.com/product/solved-cuda-homework2-openmp-programming
<br>
The purpose of this assignment is to familiarize yourself with OpenMP programming.

Conjugate gradient method is an algorithm for the numerical solution of particular systems of linear equations. It is often used to solve partial differential equations, or applied on some optimization problems. You may get more information on Wikipedia (http://en.wikipedia. org/wiki/Conjugate_gradient_method).

In this assignment, you are asked to parallelize a serial implementation of the conjugate gradient method using OpenMP. The serial implementation can be downloaded on New e3 system. It contains:

<ul>

 <li>c</li>

</ul>

The implementation of the conjugate gradient method.

<ul>

 <li>h</li>

</ul>

Some data definitions. <strong>DO NOT </strong>modify this file.

<ul>

 <li>common directory</li>

</ul>

Directory that contains some functions for time calculation and random numbers. <strong>DO NOT </strong>modify the files in this directory.

<ul>

 <li>bin directory</li>

</ul>

Directory that contains the executable.

<ul>

 <li>Makefile, make.common</li>

</ul>

Makefiles.

<ul>

 <li>README</li>

</ul>

The information of the program.

<h1>2           Requirements</h1>

In this assignment, you have to modify cg.c to improve the performance of this program (i.e., to insert OpenMP pragmas/library routines to parallelize parts of the program). Of course, you may add any other variables or functions if necessary.

<strong>Note:</strong>

<ul>

 <li><strong>DO NOT modify/add any output messages.</strong></li>

 <li><strong>Grading will be made based on the speedup/efficiency that your implementation would yield.</strong></li>

</ul>

1

<h1>3           Evaluation Platform</h1>

Your program should be able to run on UNIX-like OS platforms. <strong>We will test your program on the workstations </strong>dedicated for this course. You can access these workstations by <strong>SSH </strong>with the following information.

<table width="432">

 <tbody>

  <tr>

   <td width="115">IP</td>

   <td width="96">Port</td>

   <td width="95">User Name</td>

   <td width="126">Password</td>

  </tr>

  <tr>

   <td width="115">140.113.215.195</td>

   <td width="96">37031–37034</td>

   <td width="95">[Student ID]</td>

   <td width="126">[Provided by TA]</td>

  </tr>

 </tbody>

</table>