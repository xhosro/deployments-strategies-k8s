# Kubernetes Deployment Strategies

## 1. Rolling Update
**Description**: Pods are incrementally updated with the new version, ensuring that some instances of the old version remain available during the update process.

**Use Case**: Ideal for scenarios requiring minimal downtime and gradual rollout of new versions.

**Pros**:
- Minimal downtime.
- Allows for easy rollback in case of issues.

**Cons**:
- Complexity in managing stateful applications.

