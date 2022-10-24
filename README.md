# UCCS-TKET-workshop-2022

 - Lecture 1 (Tues Nov 1): Quantum circuit construction and running on classical backends 

A quantum circuit forms the unit of computation that we can send off to a quantum co-processor: there is the main program running on the classical host computer which routinely sends off jobs to a quantum computer. We will use Quantinuum’s quantum software development kit called TKET to discuss basic quantum gates, build quantum circuits and perform measurements. Moreover, when working with quantum circuits we may want access to the quantum state prepared by our circuit. This can be helpful if we want to check whether our circuit construction is correct. We will use different classical simulators such as a statevector simulator and a simulator that mimics a perfect quantum computer. 

 

 - Lecture 2 (Th Nov 3): The Quantum compiler flow  

So far, we have already covered enough to be able to design the circuits we want to run, submit them to a simulator backend, and interpret the results in a meaningful way. This is all you need if you want to just try out a quantum computer, run some toy examples and observe some basic results. If you want to run your circuit on a real quantum processor, we need to consider the necessary steps for circuit compilation. The primary goals of compilation are two-fold: solving the constraints of the backend to get from the abstract model to something runnable, and optimizing/simplifying the circuit to make it faster, smaller, and less prone to noise. 

 

 - Lecture 3: (Tues Nov 8): Shor's Algorithm 

In 1994 Peter Shor invented a quantum algorithm that can factor numbers in polynomial time. Why should we care about efficient algorithms for factoring? A very good reason is that such efficient algorithms can be used to break many public key cryptosystems and in particular the public key cryptosystem known as RSA. Hence, Shor’s algorithm remains one of the (or probably the) most important and impressive potential applications of quantum computing. In this lecture, we will discuss Shor’s factoring algorithm and implement it on different backends. While doing this, we will also learn about the quantum Fourier transform, the unitary operator, and quantum phase estimation.
