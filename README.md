# Test pull request that branch is forked from a branch not merged yet

    master   A     B
        o
        |
        |
        o
        | \
        |  \ branch A that will be a pull request
        |   \
        |    o branch A
        |    |
        |    |
        |    o
        |    |
        |    |
        |    o
        |    | \
        |    |   \ branch B that will be another pull request, after branch B is merged
        |    |    \
        |    o     o
        |   /      |
        |  /       |
        | /        |
        o merge pull request of branch A
        |          |
        |          o
        |         /
        |        /
        |       /
        |      /
        |     /
        |    /
        |   /
        |  /
        | /
        |/
        o merge pull request of branch B
