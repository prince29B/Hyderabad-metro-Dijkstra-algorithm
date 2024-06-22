#Metro Route Optimizer-Dijkstra-algorithm

INTRODUCTION: This C++ code implements Dijkstra's algorithm to find the shortest path (minimum number of stations) in a metro system with 56 stations. It initializes a graph using an adjacency matrix, where each station is connected to its adjacent stations. The user selects a source station, and the algorithm calculates the shortest distance from this source station to all other stations using a priority queue. Finally, it prints the minimum number of stations required to reach every other station from the source.

COMPLEXITY: The time complexity of Dijkstras algorithm is O(V^2),where V is the number of vertices in the graph.The space complexity of Dijkstras algorithm is O(V)

 STATION CODES
 
    Node number                                       Station Name
    
        0                                              LBnagar
        1                                              Victoria_memorial
        2                                              Chaitanyapuri
        3                                              Dilshukhnagar
        4                                              Moosrambagh
        5                                              New Market
        6                                              Malakpet
        7                                              MG BusStation
        8                                              Osmania_medical
        9                                              GandhiBhavan
        10                                             Assembly
        11                                             Lakdikapool
        12                                             Khairtabad
        13                                             Irrummanzil
        14                                             Panjagutta
        15                                             Ameerpet
        16                                             SRnagar
        17                                             ESIhospital
        18                                             Erragadda
        20                                             Bharatnagar
        21                                             Moosapet
        22                                             DR_BRambedkar
        23                                             Kukatpally
        24                                             KPHBcolony
        25                                             JNTUcollege
        26                                             Miyapur
        27                                             Sultanbazar
        28                                             Narayanguda
        29                                             Chikkadpali
        30                                             RTCxroads
        31                                             Musheerabad
        32                                             Gandhihospital
        33                                             SecundrabadWest
        34                                             Paradeground
        35                                             Nagole
        36                                             Uppal
        37                                             stadium
        38                                             NGRI
        39                                             Habsiguda
        40                                             Tarnaka
        41                                             Mettuguda
        42                                             SecuderabadeEast
        43                                             Paradise
        44                                             Rasoolpura
        45                                             PrakashNagar
        46                                             Begumpet
        47                                             MathuraNagar
        48                                             Yusufguda
        49                                             Jubliehills
        50                                             JH-checkpost
        51                                             Peddamagudi
        52                                             Madhapur
        53                                             Dugamcheruvu
        54                                             Hitechcity
        55                                             Raidurg
