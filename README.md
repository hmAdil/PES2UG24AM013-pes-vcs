# PES-VCS Implementation

## Student Details

* Name: Adil Ahmed
* SRN: PES2UG24AM013

---

## Phase 1: Object Storage

### Description

Implemented content-addressable object storage using SHA-256 hashing. Objects are stored in `.pes/objects` using directory sharding.

### Screenshot 1A

![1A](screenshots/1A.png)

### Screenshot 1B

![1B](screenshots/1B.png)

---

## Phase 2: Tree Objects

### Description

Implemented tree serialization and parsing. Trees represent directory structures and store references to blob objects.

### Screenshot 2A

![2A](screenshots/2A.png)

### Screenshot 2B

![2B](screenshots/2B.png)

---

## Phase 3: Index (Staging Area)

### Description

Implemented staging area using a text-based index file. Supports adding files, saving index atomically, and status checking.

### Screenshot 3A

![3A](screenshots/3A.png)

### Screenshot 3B

![3B](screenshots/3B.png)

---

## Phase 4: Commit Objects

### Description

Implemented commit creation by linking tree objects with commit messages. Commit objects are stored in the object store.

### Screenshot 4A

![4A](screenshots/4A.png)

### Screenshot 4B

![4B](screenshots/4B.png)

### Screenshot 4C

![4C](screenshots/4C.png)

---

## Conclusion

Successfully implemented a simplified version control system with object storage, trees, staging area, and commit functionality.