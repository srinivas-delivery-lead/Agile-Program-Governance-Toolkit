# RAID Log Template

| ID | Type | Description | Impact | Probability | Owner | Mitigation / Action | Due Date | Status |
|---|---|---|---|---|---|---|---|---|
| R-001 | Risk | Example: critical API dependency may slip | High | Medium | Program Manager | Weekly dependency review and fallback plan | YYYY-MM-DD | Open |
| A-001 | Assumption | Example: test environment available before SIT | Medium | Medium | Engineering Lead | Confirm environment-readiness date | YYYY-MM-DD | Open |
| I-001 | Issue | Example: production defect blocking release | High | N/A | QA Lead | Root-cause and hotfix plan | YYYY-MM-DD | In Progress |
| D-001 | Dependency | Example: external security approval required | High | N/A | Security Lead | Track approval in governance meeting | YYYY-MM-DD | Open |

## Recommended status values

- Open
- In Progress
- Mitigated
- Closed
- Accepted

## Risk scoring

A simple model can use:

`Risk Exposure = Probability × Impact`

The exact scoring scale should be agreed with the program governance team.
