n = 5

graph = [
    [0, 2, 0, 6, 0],
    [2, 0, 3, 8, 5],
    [0, 3, 0, 0, 7],
    [6, 8, 0, 0, 9],
    [0, 5, 7, 9, 0]
]

visited = [False] * n


visited[0] = True

print("Edges in Minimum Spanning Tree:")


for _ in range(n - 1):

    minimum = 999
    x = 0
    y = 0

    for i in range(n):
        if visited[i]:
            for j in range(n):
                if not visited[j] and graph[i][j] != 0:
                    if graph[i][j] < minimum:
                        minimum = graph[i][j]
                        x = i
                        y = j

  
    print(x, "--", y, "=", minimum)

    visited[y] = True
