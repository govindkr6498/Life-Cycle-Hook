When component is uploaded then run callback one by one
1. Run "Constructor From Parent"
2. Run "connectedCallback From Parent"
3. Run "renderedCallback From Parent"
4. Run "Constructor From Child"
5. Run "connectedCallback From Child"
6. Run "renderedCallback From Child"
7. Run "renderedCallback From Parent"
8. Run "Disconnected call back from Child"
9. Run "renderedCallback From Parent"

NOTE: You see, Every time "renderedCallback From Parent" is calling when any event is happened.
