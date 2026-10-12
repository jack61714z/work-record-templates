# Work-record templates

## Use the implementation

The runnable entry for an agent is [SKILL.md](SKILL.md). It directs the agent to perform the task with existing authorized tools; it is not a daemon or a deterministic classifier. An LLM/agent host capable of reading skill files and using the required tools is needed. No sibling repository is required.

1. Obtain this repository through your normal authorized Git workflow, retaining all package files together. Review the skill and resources before adoption.
2. Install the repository folder as a skill named `work-record-templates` through your host's documented skill installer or skill directory. Do not overwrite an existing customized installation; compare and preserve it first. Hosts without skill discovery can explicitly read `SKILL.md` and its task-relevant resources from the checked-out folder.
3. Invoke it on an actual authorized work item: “Use $work-record-templates to create and deliver the applicable assignment/result/review for this real task, preserving the current host contract.” Supply the original goal, existing work-item/destination reference and permitted effects. Let the agent recover available facts rather than supplying fictitious observations.
4. Inspect the actual output and tool effects. A successful file load or syntax check is not actual-use acceptance. Missing tools/authority must be reported precisely rather than replaced with a simulated success.

Updates replace only this package after review; preserve customization, active obligations and history. Removing its skill folder stops future discovery after the host refreshes, not obligations or pending work already created. Follow the host's documented reload behavior; no current-session activation is promised.

Implementation and real-use evidence belong on the [owning work item](https://github.com/jack61714z/work-record-templates/issues/1) and its linked candidate review. Until those observations are saved, actual use remains pending. Explicit invocation does not prove automatic selection or background event coverage.


## Purpose and adoption boundary

These are optional prose prompts for assignments, execution results and reviews. Use only the parts that help the current task. Existing equivalent prose is already acceptable. You may use one template without the others; no companion guide, common schema/runtime, new record type or synchronized version is required.

Templates present information; they do not create policy. They do not require seven-axis drift checks, a retrospective at every closure, task registration, two-person review or any new approval gate. Apply such obligations only where the user's instructions or active policy/host contract already require them. Do not remove existing obligations merely because an optional template omits them.

This repository includes an independently invocable agent skill. The package is not activated merely by publication. It grants no operational authority and proves no behavioral improvement. Use and redistribution are governed by the MIT license in this repository. Current permissions, privacy, required writers, review independence and record/transport semantics remain effective. Progressive Investigation (PI), an investigation method, and an existing Chat–Codex handoff system (C2C) remain independent and unchanged.

## Optional context block

Here PI means Progressive Investigation, an investigation method, and C2C means Chat/Codex communication tooling. The compatibility examples below do not require either tool.

Include the material information needed to understand and act on the record:

- Original intended outcome and this bounded work slice.
- Authoritative requirement/scope source and applicable revision where material.
- Existing task/work-item identity, baseline and current candidate where material.
- Allowed work/effects, dependencies, exclusions, freezes and deferrals.
- Exact authorized exceptions, their conditions/limits and source, or none.
- Evidence needed for this slice's acceptance and unresolved decisions.
- Authorized destination/audience and any persistence gap.

This is not a fixed field count, universal sufficiency checklist or mandatory shared binding object. Add material host metadata; retain unknown values as unknown where supported. Use one authoritative source of goal/scope/acceptance and present its applicable contents to the audience that needs them. A link alone may not communicate those contents. Carried copies should not become competing requirements.

## Assignment: executor audience

Suggested prose:

“Executor: [actual actor]. Deliver [bounded artifact/outcome] by taking [concrete next action] within [allowed effects]. The applicable goal/scope is [material context or contents above]. Return [actual changes and required observations/evidence], including failures, skipped checks and limitations. Relevant uncertainty or allowed probe: [if needed]. Remaining work owned elsewhere: [owner/next action].”

Do not fill in the reviewer's eventual decision. Investigation details come from the existing applicable reasoning method; the template does not redefine PI or add investigation stages.

## Assignment: supervisor/reviewer audience

Suggested prose:

“Responsible supervisor/reviewer: [actual actor and authority]. Dispatch rationale: [why this bounded action is appropriate under current instructions]. Inspect [actual candidate/artifacts and relevant context]. Decision needed: [acceptance, bounded repair or specific evidence/retained decision]. Remaining parent obligations: [owner/next action].”

These two audiences describe responsibilities, not necessarily two people, two models or sequential reviews. The active workflow determines actual responsibility and any independence requirement. A second model's participation does not itself establish independent verification.

## Execution result

Suggested prose:

“Applicable assignment/context: [reference plus material changes]. Actual executor, baseline and candidate: [where relevant]. Actual cumulative work and effects: [what happened]. Checks/probes: [object/revision, method, result and evidence]. Failures, skipped checks and limits: [facts]. Supported delivery/outcome claims: [what evidence establishes]. Unresolved evidence, deviations, deferred work and remaining obligations: [details]. Next owner/action: [concrete next step].”

Use ordinary evidence text to describe a lesson's actual later application if relevant. An intention or assertion is not verified use. Keep delivery, installation, observed behavior and achievement of the original outcome distinct where relevant. Exact evidence standards and policies come from the applicable workflow, not this template.

## Review

Suggested prose:

“Reviewer and authority: [actual actor]. Reviewed assignment/context and candidate/range: [identity/version where material]. Evidence actually inspected: [artifacts/observations]. Evidence only reported, missing or unavailable: [limits]. Applicable review checks and findings: [use the current policy's substance]. Disposition: [accepted slice, bounded repair, specific evidence request, deferral or retained decision], because [evidence-based reason]. Dependent effects and next concrete action: [details]. Parent status and remaining obligations: [facts].”

If the active policy requires seven-axis alignment review, include that substance here or in existing equivalent prose. If it requires closure learning, include its required retrospective and later-verification information at the appropriate closure location. Those policies retain their own authority and maintenance; these optional prompts do not define or activate them. A saved review does not by itself prove a tool effect or runtime outcome.

## Existing-host compatibility and independent updates

A host may call the assignment WORK_ORDER, the result EXECUTION_RESULT and the review CHAT_REVIEW, REVIEW or another supported name. These template headings are human-readable labels, not permission to rename parser fields or alter a protocol. Preserve required names, exact completion requests, binding/version and candidate semantics, actual executor evidence, nullable planning where supported, iteration versus repair-label distinctions, writer restrictions and historical records.

A template describes a record; it does not own that record's authority, retention location, publication responsibility or migration contract. Those remain with the applicable workflow or project deployment. Populate their required preservation and readback references where relevant without treating the template itself as proof of persistence.

Use supported text slots only. Do not transform old records, resend completed work, reset a task, re-pair endpoints or reexecute an operation simply to use a new layout. Existing C2C states, commands, pointer/schema fields, acknowledgment and continuation obligations remain effective; this document does not make an installed C2C package transport-only. A real deployed-contract change requires its own authorized, compatible migration.

Example: use only the executor prompt for a document edit while retaining the team's original review and tracker formats. Updating this wording later needs no synchronized update to those processes. The template is useful only insofar as it presents the information their existing rules require.

Document completeness does not establish installation, compatible loading, actual use or better outcomes. No document-revision experiment or efficacy result is claimed.

Stop using an optional prompt independently by returning to equivalent prose. Preserve the active host's required information, record semantics and saved history; no other prompt or guide needs to change.

## Revision, maintenance and license

Initial public document revision: 2026-10-12. Maintainer: jack61714z. Corrections may be proposed through this repository. Revised independently; sibling versions are not prerequisites. Publication does not activate this guidance, and behavioral efficacy remains unverified.

This document includes adapted policy and record material from [codex-with-chatgpt](https://github.com/jack61714z/codex-with-chatgpt), licensed under MIT, Copyright (c) 2026 codex-with-chatgpt contributors. New contributions are Copyright (c) 2026 jack61714z. See [LICENSE](LICENSE) for the complete MIT terms and preserved notices.

