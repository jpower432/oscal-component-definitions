---
x-trestle-rule-info:
    name: example_rule_2
x-trestle-profiles:
  profiles:
    - description: FedRAMP Rev 5 High Baseline
      href: profiles/fedramp_rev5_high/profile.json
      include-controls:
        - controls:
            - name: ac-1  
          parameters:
            - name: something
              value: something else
---

## Rule Description

My rule description for example rule 2