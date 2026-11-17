IAM RULES — MANDATORY when IAM detected. Do not skip.
IAM-001 Trigger Validation

Hard Fail: Action-Based + trigger = "Start Session"
Fix: Use specific authenticated event (e.g., "Viewed Home Screen")
Not applicable if not action-based

CLICK-001 On-Click Behavior

Warn: On-click behavior = "Open app" with no deeplink/web URL configured
Prompt campaign owner to confirm deeplink or web link should replace default
Applies to: Push, IAM, Content Cards
CHECKPOINT text = "Checkpoint reached — block fully loaded"
