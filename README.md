[![LinkedIn][linkedin-shield]][linkedin-url]

# Seeking For RFC
the script `sfrfc` It's just a simple work in a bash script to get a local copy in .txt for any **RFC** (**R**equest **F**or **C**ommentary).

#### According to the The Internet Society (https://www.internetsociety.org/)
The RFC Series (ISSN 2070-1721) contains technical and organizational documents about the Internet, including the specifications and policy documents produced by five streams: the Internet Engineering Task Force (IETF), the Internet Research Task Force (IRTF), the Internet Architecture Board (IAB), Independent Submissions, and Editorial.
Although Many RFCs have Informational or Experimental status and do not represent any kind of standard, they contain information that may be useful or important to retain in this archival document series.

#### How to:
The flow is basically segmented into three parts: a main function, an index wrapper, and an options menu. 

A normal usage description (**help [h]**) is provided as follows:
```
As follows:
	For example, you can indicate the name of a technology or protocol
	as the first search pattern, and accompany it with a second search
	pattern as a description of it,
	such as implementation or the word configuration.

	For example:

	$./sfrfc dns implementation

	If you want, you can use a single search pattern by
	entering only one variable, but specifying the second input to be @ (at).

	Something like this:

	$./sfrfc dns @
```

https://github.com/kjfigueroa/SeekingForRFC/assets/68950531/24567456-b591-4671-bb36-eb80fd03fec5


#### Why? 
Recently in my training studies, I have come across the fact that much of the information received in text documents does not provide a complete explanation of the technologies, which, it's are based on computational morphology (logic or algorithmic) on its technologies functions.

That is where the need comes to me, to delve into more detail that can provide an accurate map of these technologies, to give just one example, only when looking for information related to the concept of DNS, you mainly find only the configuration of said server or service (that is commonly the information that is provided in all courses, manuals, or technical texts), without even touching the information that would actually allow you to understand how the protocol works or its fundamental parts, then, following the previous example, if your desire is to really understand the nomenclature, the algorithms implemented in the protocol, and the logical composition of its parts, it's sensible to approach the source of this data, and a merely sound approach to me is RFCs.

Now, why in a bash script and not just go to a web browser and search? - well, because it's easy, ok, considering that most of the time this engineering sector works on server-oriented architectures and/or systems, we are almost always working from a console, terminal emulator, or on a laptop with LINUX, or other special times from a MAC (whose kernel is based on UNIX), then, it becomes a task that takes up to more than an hour to execute and accommodate, and through a bash script it is a matter of seconds, apart from the fact that I actually like to experiment with these things.

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kjfigueroa
