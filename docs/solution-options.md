**Solutions to Increase Insight-Driven Adoption – Analytics Case Study**

**Problem Recap**
Analytics dashboards are frequently created and viewed, but they do not consistently lead to insight, action, or decision-making. This results in high usage signals with low business impact.

Solution Options Considered

**Option 1: Decision-oriented dashboard templates**
Provide opinionated dashboard templates framed around common business decisions (e.g. “Are we on track?”, “Where are we underperforming?”) rather than raw metric collections.

**Pros**
- Anchors dashboards to decisions
- Reduces cognitive load
- Improves signal-to-noise ratio

**Cons**
- Risk of over-opinionation
- Requires careful framing to preserve flexibility

**Option 2: Insight prompts & annotations**
Introduce lightweight prompts encouraging users to capture intent and interpretation, such as:
- “What decision does this dashboard support?”
- “What action should be taken if this metric changes?”

**Pros**
- Makes intent explicit
- Encourages shared understanding
- Low implementation overhead

**Cons**
- Depends on user discipline
- May be ignored without incentives

**Option 3: Action triggers & follow-ups**
Enable dashboards to directly trigger follow-up actions (alerts, tasks, links) when thresholds are reached.

**Pros**
- Strong link between insight and action
- Reinforces value of analytics

**Cons**
- Risk of alert fatigue
- Configuration complexity

**Prioritisation Decision**

**Primary approach:** Decision-oriented dashboard templates  
**Secondary support:** Lightweight insight prompts

**Rationale**
- Directly addresses the core problem: dashboards without decisions
- Improves clarity without forcing workflow changes
- Scales across teams and personas
- Lower risk than heavy automation or alerts

**Success Measurement**
Success will be evaluated using the adoption metrics defined in `docs/adoption-metrics.md`, with a focus on:
- Dashboards leading to documented actions
- Re-engagement and sustained relevance
- Reduction in unused or abandoned dashboards

**Risks & Mitigations**
- **Risk:** Templates feel too prescriptive  
  **Mitigation:** Make templates optional and customisable
- **Risk:** Prompts are ignored  
  **Mitigation:** Keep prompts lightweight and contextual

**Relationship to Product Metrics**
These solutions are designed to move the outcome-based adoption metrics defined in Issue #2, shifting success from dashboard volume to decision impact.
