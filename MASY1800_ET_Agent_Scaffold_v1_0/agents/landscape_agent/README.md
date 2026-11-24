# Assignment 8 | AI maintenance assistant landscape

Run from the scaffold root. Build each case packet with `python tools/build_prompt.py --agent agents/landscape_agent --case agents/landscape_agent/cases/primary.json` and repeat with `contrast_1.json`. Give ChatGPT the packet and the [evidence snapshot](records/evidence_snapshot.md). Save returned JSON and run `python tools/validate_response.py` followed by the response path. Check frozen core with `python tools/check_frozen_core.py`.

- [Primary output report](records/primary_output_report.md)
- [Agent Record](records/agent_record.md)
- [Submission notes](records/submission_notes.md)
