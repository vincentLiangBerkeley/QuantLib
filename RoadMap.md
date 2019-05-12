# RoadMap for VincentLiang's perception on QuantLib
The final goal of this personal project is to modify/rewrite a QuantLib in c++ from my own perspective. QuantLib is used as a starting point for basic functionalities. In the process, I will focus on learning modern c++ best practices, design patterns, optimization techniques and aligning with Facebook's workflow. 
## Objective
### A standalone, efficient, easy to use Quantitative Finance Library in C++

## Key Results

### Transforming and understanding the functionality of QuantLib
This is to transform and digest this library into my own knowledge base. 

    - Dev Environment setup (on my own laptop): 
        -Setup Vim environment by installing Vundle, necessary vim plugins, etc;
        -Setup c++ building environment, compiler, Buck, Cmake, etc;
        - Install QuantLib locally;
    - Reading and studying the main functionalities:
        - Read the study materials from QuantLib's webside;
        - Follow some examples to further understand the core functionalities;
    - Benchmark different use cases and find out the performance bottleneck;
        - Summarize main use cases;
        - Design a benchmark framework for testing and find out bottlenecks;
### Re-write the main functionalities with Facebook standards
Knowing the critical paths of core functionalities by benchmarking, try to apply folly's standards and think about optimization opportunities. 
### Migrate the whole project out of boost and apply folly as much as possible
From main functionalities, spread the re-writting effort to attached functionalities and gradually migrate out of boost and into folly. 
### A standalone project providing a superset of functionalities. (Long term goal)
Think about what is lacking from this Lab and try to conpensate/start a new project and hopefully in a better state.
