# talks_papers_blogs
various interesting talks, papers, blogs, etc

## Concurrency

#### [GopherCon 2018: Rethinking Classical Concurrency Patterns - Bryan C. Mills](https://www.youtube.com/watch?v=5zXAHh5tJqQ)

Very good talk that covers some lesser known concurrency patterns (condition variable, error group).

#### [How to Gracefully Close Channels](https://go101.org/article/channel-closing.html)

A pattern-based approach to how to properly close channels given M producers and N consumers.

## Databases

#### [Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases](https://pages.cs.wisc.edu/~yxy/cs764-f20/papers/aurora-sigmod-17.pdf)

Detailed whitepaper that explains why traditional RDBMS suffers from poor performance when run on a networked file system. Provides an alternate architecture which turns the database "inside out" and optimizes for the network.

## Load Control

#### ["Stop Rate Limiting! Capacity Management Done Right" by Jon Moore](https://www.youtube.com/watch?v=m64SWl9bfvk)

Great talk for discussing the tradeoffs around various load control mechanisms (e.g. quota based rate-limiting vs. health-adaptive load control).

#### [Visualizing algorithms for rate limiting](https://smudge.ai/blog/ratelimit-algorithms)

Cool website which does a great job of comparing various rate limiting approaches. Has an emphasis on surfacing how client traffic is actually impacted by each algorithm and provides enough detail for you to implement the algorithms directly.
