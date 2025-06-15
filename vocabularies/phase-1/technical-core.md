# Phase 1 - Technical Core Vocabulary (150 words)

**Target**: 150 technical words  
**Timeline**: Months 1-3  
**Daily Goal**: 4 technical words/day  
**Focus**: 기본 개발 및 기술 용어

---

## 📚 Vocabulary Categories

### Data Structures (25 words)

| English | Korean | Definition | Example Sentence | Status |
|---------|--------|------------|------------------|--------|
| array | 배열 | A collection of elements stored at contiguous memory locations | "I stored the user IDs in an array for quick access." | ⭕ |
| stack | 스택 | A linear data structure that follows LIFO principle | "The function calls are managed using a call stack." | ⭕ |
| queue | 큐 | A linear data structure that follows FIFO principle | "We implemented a message queue for async processing." | ⭕ |
| hash table | 해시 테이블 | A data structure that maps keys to values using hash function | "The hash table provides O(1) lookup time on average." | ⭕ |
| linked list | 연결 리스트 | A sequence of nodes where each contains data and reference | "Linked lists are efficient for frequent insertions." | ⭕ |
| binary tree | 이진 트리 | A tree structure where each node has at most two children | "We use binary trees for efficient searching algorithms." | ⭕ |
| graph | 그래프 | A collection of nodes connected by edges | "Social networks can be represented as graphs." | ⭕ |
| heap | 힙 | A complete binary tree with heap property | "The priority queue is implemented using a min-heap." | 🔄 |
| trie | 트라이 | A tree-like data structure for storing strings | "Autocomplete features often use trie data structures." | 🔄 |
| dictionary | 딕셔너리 | A collection of key-value pairs | "Python dictionaries are similar to hash tables." | 🔄 |
| set | 집합 | A collection of unique elements | "Use a set to remove duplicate values from the list." | 🔄 |
| matrix | 행렬 | A rectangular array of numbers or elements | "Image processing often involves matrix operations." | 🔄 |
| tuple | 튜플 | An ordered collection of immutable elements | "Coordinates are often represented as tuples." | 📝 |
| vector | 벡터 | A dynamic array that can resize itself | "Vectors provide efficient random access to elements." | 📝 |
| deque | 덱 | A double-ended queue allowing insertion at both ends | "Deques are useful for sliding window algorithms." | 📝 |
| priority queue | 우선순위 큐 | A queue where elements have priority levels | "Task scheduling uses priority queues for job ordering." | 📝 |
| circular buffer | 순환 버퍼 | A fixed-size buffer with wrap-around behavior | "Audio streaming often uses circular buffers." | 📝 |
| sparse matrix | 희소 행렬 | A matrix with mostly zero elements | "Sparse matrices save memory in scientific computing." | 📝 |
| adjacency list | 인접 리스트 | A way to represent graphs using lists | "Adjacency lists are memory-efficient for sparse graphs." | 📝 |
| binary heap | 이진 힙 | A complete binary tree satisfying heap property | "Binary heaps implement efficient priority queues." | 📝 |
| red-black tree | 레드-블랙 트리 | A self-balancing binary search tree | "Red-black trees maintain O(log n) operations." | 📝 |
| B-tree | B-트리 | A self-balancing tree data structure for databases | "Database indexes often use B-tree structures." | 📝 |
| bloom filter | 블룸 필터 | A probabilistic data structure for set membership | "Bloom filters can quickly test set membership." | 📝 |
| union-find | 유니온-파인드 | A data structure for disjoint set operations | "Union-find is used in Kruskal's spanning tree algorithm." | 📝 |
| segment tree | 세그먼트 트리 | A tree for storing intervals or segments | "Segment trees enable efficient range queries." | 📝 |

### Algorithms (25 words)

| English | Korean | Definition | Example Sentence | Status |
|---------|--------|------------|------------------|--------|
| sorting | 정렬 | Arranging elements in a specific order | "Quick sort is an efficient sorting algorithm." | ⭕ |
| searching | 검색 | Finding a specific element in a collection | "Binary search requires a sorted array." | ⭕ |
| traversal | 순회 | Visiting all nodes in a data structure | "Tree traversal can be done in-order or pre-order." | ⭕ |
| optimization | 최적화 | Making something as effective as possible | "Code optimization improves application performance." | ⭕ |
| recursion | 재귀 | A function calling itself with smaller input | "Factorial calculation uses recursion naturally." | ⭕ |
| dynamic programming | 동적 계획법 | Solving problems by breaking into subproblems | "Dynamic programming optimizes overlapping subproblems." | 🔄 |
| divide and conquer | 분할 정복 | Breaking problem into smaller subproblems | "Merge sort uses divide and conquer strategy." | 🔄 |
| greedy algorithm | 탐욕 알고리즘 | Making locally optimal choices | "Greedy algorithms don't always find global optimum." | 🔄 |
| backtracking | 백트래킹 | Exploring solutions by trial and error | "N-Queens problem is solved using backtracking." | 🔄 |
| breadth-first search | 너비 우선 탐색 | Graph traversal exploring neighbors first | "BFS finds shortest path in unweighted graphs." | 🔄 |
| depth-first search | 깊이 우선 탐색 | Graph traversal going deep before exploring | "DFS is useful for detecting cycles in graphs." | 🔄 |
| binary search | 이진 탐색 | Searching in sorted array by halving | "Binary search has O(log n) time complexity." | 📝 |
| linear search | 선형 탐색 | Searching elements one by one | "Linear search works on unsorted arrays too." | 📝 |
| bubble sort | 버블 정렬 | Simple sorting by swapping adjacent elements | "Bubble sort is inefficient for large datasets." | 📝 |
| merge sort | 병합 정렬 | Divide and conquer sorting algorithm | "Merge sort has stable O(n log n) performance." | 📝 |
| quick sort | 퀵 정렬 | Efficient sorting using pivot partitioning | "Quick sort is often faster than merge sort." | 📝 |
| heap sort | 힙 정렬 | Sorting using heap data structure | "Heap sort has O(n log n) worst-case complexity." | 📝 |
| insertion sort | 삽입 정렬 | Sorting by inserting elements in order | "Insertion sort is efficient for small arrays." | 📝 |
| selection sort | 선택 정렬 | Sorting by selecting minimum element | "Selection sort makes minimum number of swaps." | 📝 |
| radix sort | 기수 정렬 | Non-comparative integer sorting algorithm | "Radix sort can be faster than comparison sorts." | 📝 |
| counting sort | 계수 정렬 | Sorting by counting occurrences | "Counting sort works well for limited range integers." | 📝 |
| topological sort | 위상 정렬 | Ordering vertices in directed acyclic graph | "Topological sort is used in build systems." | 📝 |
| dijkstra | 다익스트라 | Shortest path algorithm for weighted graphs | "Dijkstra's algorithm uses a priority queue." | 📝 |
| floyd-warshall | 플로이드-워셜 | All-pairs shortest path algorithm | "Floyd-Warshall finds paths between all vertices." | 📝 |
| kruskals | 크루스칼 | Minimum spanning tree algorithm | "Kruskal's algorithm uses union-find data structure." | 📝 |

### Development (50 words)

| English | Korean | Definition | Example Sentence | Status |
|---------|--------|------------|------------------|--------|
| deployment | 배포 | Process of making software available for use | "Automated deployment reduces human errors significantly." | ⭕ |
| debugging | 디버깅 | Finding and fixing errors in code | "Effective debugging requires systematic approach and tools." | ⭕ |
| refactoring | 리팩토링 | Improving code structure without changing behavior | "Regular refactoring keeps codebase maintainable and clean." | ⭕ |
| testing | 테스팅 | Verifying software works as expected | "Unit testing catches bugs early in development." | ⭕ |
| code review | 코드 리뷰 | Examining code for quality and correctness | "Code reviews improve team knowledge sharing." | ⭕ |
| CI/CD | 지속적 통합/배포 | Continuous integration and deployment practices | "CI/CD pipelines automate testing and deployment." | ⭕ |
| version control | 버전 관리 | Tracking changes to code over time | "Git is the most popular version control system." | ⭕ |
| branching | 브랜치 | Creating separate lines of development | "Feature branching isolates new development work." | 🔄 |
| merging | 병합 | Combining changes from different branches | "Merging requires resolving potential conflicts carefully." | 🔄 |
| commit | 커밋 | Saving changes to version control | "Write clear commit messages for future reference." | 🔄 |
| pull request | 풀 리퀘스트 | Proposing changes for review | "Pull requests enable collaborative code development." | 🔄 |
| repository | 저장소 | Storage location for software projects | "The repository contains all project files and history." | 🔄 |
| build | 빌드 | Compiling and packaging software | "The build process converts source code to executable." | 🔄 |
| compilation | 컴파일 | Converting source code to machine code | "Compilation errors must be fixed before running." | 📝 |
| runtime | 런타임 | Environment where program executes | "Runtime errors occur during program execution." | 📝 |
| library | 라이브러리 | Collection of reusable code modules | "External libraries extend application functionality efficiently." | 📝 |
| framework | 프레임워크 | Software platform providing foundation | "React framework simplifies user interface development." | 📝 |
| dependency | 의존성 | External code required by application | "Managing dependencies prevents version conflicts." | 📝 |
| package | 패키지 | Bundled software component | "Package managers handle dependency installation automatically." | 📝 |
| module | 모듈 | Self-contained unit of code | "Modular design improves code organization and reusability." | 📝 |
| interface | 인터페이스 | Contract defining how components interact | "Well-defined interfaces enable loose coupling between modules." | 📝 |
| implementation | 구현 | Actual code that fulfills interface | "Multiple implementations can share same interface." | 📝 |
| abstraction | 추상화 | Hiding complex implementation details | "Abstraction layers simplify complex system interactions." | 📝 |
| encapsulation | 캡슐화 | Bundling data and methods together | "Encapsulation protects object internal state integrity." | 📝 |
| inheritance | 상속 | Creating new classes based on existing ones | "Inheritance promotes code reuse in object-oriented programming." | 📝 |
| polymorphism | 다형성 | Objects behaving differently based on type | "Polymorphism enables flexible and extensible code design." | 📝 |
| method | 메서드 | Function associated with object | "Object methods define what operations are possible." | 📝 |
| function | 함수 | Reusable block of code | "Pure functions have no side effects." | 📝 |
| parameter | 매개변수 | Input value passed to function | "Function parameters define expected input types." | 📝 |
| argument | 인수 | Actual value passed to function | "Arguments must match function parameter types." | 📝 |
| return value | 반환값 | Output produced by function | "Functions should have predictable return values." | 📝 |
| variable | 변수 | Storage location with symbolic name | "Variable names should be descriptive and meaningful." | 📝 |
| constant | 상수 | Value that cannot be changed | "Constants make code more readable and maintainable." | 📝 |
| scope | 스코프 | Visibility region of variables | "Understanding scope prevents variable naming conflicts." | 📝 |
| namespace | 네임스페이스 | Container for grouping related identifiers | "Namespaces prevent naming collisions in large projects." | 📝 |
| syntax | 구문 | Rules governing code structure | "Syntax errors prevent code from compiling successfully." | 📝 |
| semantics | 의미론 | Meaning and behavior of code | "Semantic errors cause incorrect program behavior." | 📝 |
| algorithm | 알고리즘 | Step-by-step problem-solving procedure | "Efficient algorithms improve application performance significantly." | 📝 |
| complexity | 복잡도 | Measure of algorithm efficiency | "Time complexity describes how runtime scales." | 📝 |
| optimization | 최적화 | Improving code performance | "Premature optimization can make code harder to maintain." | 📝 |
| profiling | 프로파일링 | Measuring code performance | "Profiling identifies performance bottlenecks accurately." | 📝 |
| benchmark | 벤치마크 | Performance measurement standard | "Benchmarks help compare different implementation approaches." | 📝 |
| scalability | 확장성 | Ability to handle increased load | "Scalable systems maintain performance under growth." | 📝 |
| maintainability | 유지보수성 | Ease of modifying code | "Clean code improves long-term maintainability significantly." | 📝 |
| readability | 가독성 | How easy code is to understand | "Code readability is more important than cleverness." | 📝 |
| documentation | 문서화 | Written explanation of code | "Good documentation saves future development time." | 📝 |
| annotation | 주석 | Comments explaining code purpose | "Annotations should explain why, not what." | 📝 |
| specification | 명세 | Detailed description of requirements | "Clear specifications prevent misunderstandings during development." | 📝 |
| prototype | 프로토타입 | Early model demonstrating concept | "Prototypes help validate ideas before full implementation." | 📝 |
| iteration | 반복 | Repeated execution of code block | "Iteration is fundamental to many algorithms." | 📝 |

### Architecture (50 words)

| English | Korean | Definition | Example Sentence | Status |
|---------|--------|------------|------------------|--------|
| microservices | 마이크로서비스 | Architecture with small, independent services | "Microservices enable independent team development and deployment." | ⭕ |
| API | API | Interface for software components | "RESTful APIs provide standardized communication between services." | ⭕ |
| REST | REST | Architectural style for web services | "REST APIs use HTTP methods for resource operations." | ⭕ |
| frontend | 프론트엔드 | Client-side part of application | "Frontend development focuses on user experience." | ⭕ |
| backend | 백엔드 | Server-side part of application | "Backend services handle business logic and data." | ⭕ |
| fullstack | 풀스택 | Both frontend and backend development | "Fullstack developers work across entire application stack." | ⭕ |
| database | 데이터베이스 | Organized collection of data | "Database design affects application performance significantly." | ⭕ |
| server | 서버 | Computer providing services to clients | "Load balancers distribute requests across multiple servers." | 🔄 |
| client | 클라이언트 | Software requesting services | "Client applications consume API services." | 🔄 |
| middleware | 미들웨어 | Software connecting different applications | "Authentication middleware validates user requests." | 🔄 |
| load balancer | 로드 밸런서 | Distributes requests across servers | "Load balancers improve application availability and performance." | 🔄 |
| cache | 캐시 | Temporary storage for quick access | "Caching reduces database load and improves response times." | 🔄 |
| CDN | CDN | Content delivery network | "CDNs serve static content from geographically distributed servers." | 🔄 |
| proxy | 프록시 | Intermediate server between client and server | "Reverse proxies can provide SSL termination." | 📝 |
| gateway | 게이트웨이 | Entry point to network or system | "API gateways manage authentication and rate limiting." | 📝 |
| container | 컨테이너 | Lightweight application packaging | "Containers provide consistent deployment environments." | 📝 |
| orchestration | 오케스트레이션 | Automated management of containers | "Kubernetes handles container orchestration at scale." | 📝 |
| deployment | 배포 | Process of releasing software | "Blue-green deployment minimizes downtime during updates." | 📝 |
| scaling | 스케일링 | Adjusting system capacity | "Horizontal scaling adds more servers to handle load." | 📝 |
| monitoring | 모니터링 | Observing system behavior | "Monitoring alerts help detect issues before users." | 📝 |
| logging | 로깅 | Recording system events | "Centralized logging aggregates events from multiple services." | 📝 |
| metrics | 메트릭 | Quantitative measurements | "Performance metrics help identify system bottlenecks." | 📝 |
| alerting | 알림 | Automated notification system | "Alerting systems notify teams of critical issues." | 📝 |
| backup | 백업 | Copy of data for recovery | "Regular backups protect against data loss." | 📝 |
| recovery | 복구 | Restoring system after failure | "Disaster recovery plans minimize business disruption." | 📝 |
| redundancy | 중복성 | Duplication for reliability | "System redundancy prevents single points of failure." | 📝 |
| failover | 페일오버 | Switching to backup system | "Automatic failover ensures high availability." | 📝 |
| cluster | 클러스터 | Group of connected computers | "Database clusters provide high availability and performance." | 📝 |
| node | 노드 | Individual computer in cluster | "Each cluster node can handle portion of workload." | 📝 |
| shard | 샤드 | Partition of database | "Database sharding distributes data across multiple servers." | 📝 |
| replication | 복제 | Creating copies of data | "Database replication improves read performance and availability." | 📝 |
| synchronization | 동기화 | Coordinating data across systems | "Data synchronization ensures consistency across replicas." | 📝 |
| consistency | 일관성 | Data uniformity across system | "Eventually consistent systems allow temporary inconsistencies." | 📝 |
| availability | 가용성 | System uptime percentage | "High availability systems target 99.9% uptime." | 📝 |
| reliability | 신뢰성 | System dependability | "Reliable systems perform consistently under normal conditions." | 📝 |
| durability | 내구성 | Data persistence guarantee | "Database durability ensures committed data survives failures." | 📝 |
| partition tolerance | 분할 내성 | System functioning despite network failures | "CAP theorem involves consistency, availability, and partition tolerance." | 📝 |
| latency | 지연시간 | Time delay in system response | "Low latency is critical for real-time applications." | 📝 |
| throughput | 처리량 | Amount of work done per time | "High throughput systems handle many concurrent requests." | 📝 |
| bandwidth | 대역폭 | Data transmission capacity | "Network bandwidth limits data transfer rates." | 📝 |
| protocol | 프로토콜 | Rules for communication | "HTTP protocol defines web communication standards." | 📝 |
| authentication | 인증 | Verifying user identity | "Multi-factor authentication improves security significantly." | 📝 |
| authorization | 인가 | Granting access permissions | "Role-based authorization controls resource access." | 📝 |
| encryption | 암호화 | Converting data to secure format | "End-to-end encryption protects data in transit." | 📝 |
| SSL/TLS | SSL/TLS | Security protocols for communication | "TLS certificates enable secure HTTPS connections." | 📝 |
| firewall | 방화벽 | Network security system | "Firewalls filter network traffic based on rules." | 📝 |
| VPN | VPN | Virtual private network | "VPNs create secure connections over public networks." | 📝 |
| DNS | DNS | Domain name system | "DNS translates domain names to IP addresses." | 📝 |
| TCP/IP | TCP/IP | Internet protocol suite | "TCP/IP protocols enable internet communication." | 📝 |
| HTTP/HTTPS | HTTP/HTTPS | Web communication protocols | "HTTPS provides secure HTTP communication." | 📝 |
| WebSocket | 웹소켓 | Full-duplex communication protocol | "WebSockets enable real-time bidirectional communication." | 📝 |

---

## 📊 Progress Tracking

### Learning Status Legend
- ⭕ **Mastered**: 완전히 습득하여 자연스럽게 사용 가능
- 🔄 **Learning**: 의미는 알지만 사용에 연습 필요  
- 📝 **New**: 새로 접한 단어, 학습 시작 단계

### Current Progress
- **Mastered**: 30/150 (20%)
- **Learning**: 30/150 (20%)  
- **New**: 90/150 (60%)

### Weekly Goals
- **Week 1-2**: Data Structures (25 words)
- **Week 3-4**: Algorithms (25 words)
- **Week 5-8**: Development (50 words)
- **Week 9-12**: Architecture (50 words)

### Daily Practice
1. **새 단어 4개** - 카테고리별 로테이션
2. **복습 6개** - 이전 학습 단어
3. **예문 작성** - 각 단어별 1문장
4. **발음 연습** - 어려운 단어 집중

---

## 📚 Usage Examples

### In Code Comments
```javascript
// Initialize array to store user preferences
const userPreferences = [];

// Implement binary search for efficient lookup
function binarySearch(arr, target) {
    // Search algorithm implementation
}

// Deploy application using CI/CD pipeline
npm run deploy
```

### In Technical Discussion
- "We need to refactor this module for better maintainability."
- "The algorithm has O(n log n) complexity in the worst case."
- "Our microservices architecture enables independent scaling."
- "The database sharding improves query performance significantly."

### In Documentation
- "This API endpoint returns an array of user objects."
- "The caching layer reduces database load and latency."
- "Implement proper error handling for robust applications."
- "Use version control for collaborative development workflows."

---

**Last Updated**: [Current Date]  
**Phase 1 Progress**: ___/150 words (___%)  
**Target Completion**: Month 3  
**Next Review**: [Date]