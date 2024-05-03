## Roadmap

---
### Submachine
- [x] **Implement Submachine:** Creation of a substate machine within the larger state machine architecture is complete.
  - [x] **Define Entry Point:** Establish the initialization state where the submachine commences its process.
  - [x] **Institute Exit Point:** Designate the final state that concludes the submachine's execution and handle any necessary state cleanup.

### History Pseudostate
- [ ] **Integrate Shallow History:** Develop a state memory system that recalls the most recent active substate without retaining nested state histories, enabling reentry at the last active state.
- [ ] **Incorporate Deep History:** Implement a comprehensive state memory system that retains complete nested state histories for accurate restoration upon reentry.
### StateMachine Interpreters
- [x] **Implement Async StateMachine Interpreter:** Completed the asynchronous state machine interpreter, facilitating non-blocking state execution.
- [ ] **Develop Multi-Processing StateMachine Interpreter:** Construct an interpreter that utilizes multiple processes for parallel state processing, enhancing performance for computations.
- [ ] **Construct Thread-Based Interpreter:** Build an interpreter that manages state operations via threading, optimizing for concurrent I/O-bound tasks.
- [ ] **Design SequentialStateMachine Interpreter:** Initiate the creation of an interpreter that deals with state transitions in a sequential, ordered manner, designed for straightforward execution flows.
### Unit Tests
- [ ] **Develop Unit Tests:** Write tests for individual state components to evaluate their independent functionalities, ensuring reliability and bug-free operation.

### Documentation
- [x] **Compile Documentation:** Produce detailed documentation outlining the state machine's configuration, including its states, transitions, and state machine protocols, to support maintenance and usage comprehension.

### Interpreter Refactoring
- [ ] **Refactor Interpreter Logic:** Rework the interpreter component to execute a sequence of abstract instructions, rather than direct manipulation of the state tree, for better modularity and maintainability.

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).