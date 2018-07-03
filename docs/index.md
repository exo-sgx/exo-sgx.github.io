# Project: Memory-access pattern secure software systems on Intel SGX

## People

- Faculty: Dr. Yuzhe (Richard) Tang [[webpage](http://ecs.syr.edu/faculty/yuzhe)]
- PhD:
    - Ju Chen [[webpage](http://chenju2k6.github.io/)]
    - Kai Li [[webpage](http://likai1993.github.io/)]
    - Cheng Xu (Visiting PhD) [[webpage](https://xuc.me/)]

## Preliminary Results

- "Scaling Memory Access-Pattern Secure Computations via Dynamic Program Partitioning", Ju Chen, Cheng Xu, Kai Li, Yuzhe (Richard) Tang. [[Tech. report 2018](http://tristartom.github.io/docs/tr18-cmo.pdf)]

    - The work presents a library and runtime system for supporting the security notion of cache-miss obliviousness (CMO). With CMO, the trace of cache-misses in a computation becomes irrelevant to the secret computation data, and it achieves the security under all forms of access-pattern security. This library helps express various computation, in big-data analytics and cryptographic operations. The security comes from the external obliviousness in the computation layer and the cache-miss detection capability provided by Intel TSX. Comparing existing work, CMO library has advantages in performance and data scalability.
- "Strongly Secure and Efficient Data Shuffle on Hardware Enclaves", Ju Chen, Yuzhe (Richard) Tang, Hao Zhou. SysTex 2017 at ACM SOSP (Workshop paper), [[PDF (ACM)](https://dl.acm.org/citation.cfm?doid=3152701.3152708)], [[PDF (Full paper on arXiv)](https://arxiv.org/abs/1711.04243)]
    - The work is to build a data shuffling capability on Intel SGX platform in a unique way that is both strongly secure (or oblivious memory access) and efficient. The key idea to lower performance overhead without sacrificing strong security is the notion of cache-miss obliviousness. Upon implementation, the cache-miss obliviousness is realized by leveraging Intel TSX features. 
- "Towards Building Practical And Secure Multi-Party Databases", Yuzhe Tang, Wenqing Zhuang. IEEE SecDev 2016. [[PDF](http://cybersec-prod.s3.amazonaws.com/secdev/wp-content/uploads/2016/10/05211506/secdev16-final37.pdf)]
    - The work is to build a database system on top of multiple private-data sources. A user can submit a regular SQL query to our database which evaluates the query among data sources while preserving the privacy of each data source. Comparing existing work on applied multi-party computations (MPC), our work is distinct in building real MPC-based systems.

## Broader Impact Activities

- *Public lecture*: "Get Your Head In The Clouds! Cloud Computing's Risks and Rewards", at The Museum of Science and Technology at Syracuse, June 2017, [[link](http://www.cnyo.org/tag/yuzhe-tang-ph-d/)]
- *Public lecture*: "Blockchain: Applications, Security Promises and Internals", at CSIAC, Dec. 2017, [[webinar](https://www.csiac.org/event/blockchain-applications-security-promises-and-internals/)], [[slides](http://tristartom.github.io/docs/csiac17.pdf)]



