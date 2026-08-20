FINAL PUBLICATION FIGURES (2026-07-13)
======================================

Use these files for the revised manuscript:

  core_component_scalability_revised.pdf   final Fig. 3
  onchain_latency_revised.pdf               final Fig. 4
  e2e_latency_dual_panel_final.pdf          final Fig. 5

The older e2e_latency_breakdown.pdf, e2e_latency_dual_panel.pdf,
e2e_latency_dual_panel_95ci.pdf, core_component_scalability.pdf, and
onchain_latency_breakdown.pdf are historical/diagnostic outputs. They must not be
used for final numerical claims.

Final Fig. 5 is the N=30 paired controlled receipt-workflow ablation across three
fresh non-overlapping application contexts on one retained ledger (historical keys
were not erased):
Plain RETF mean 2063.17 ms; PP-RETF mean 2819.85 ms; paired delta +756.69 ms
(95% CI +730.35 to +783.02 ms), mean paired overhead +36.68% (95% CI
+35.40% to +37.95%). This is not the production four-submit P5 overhead.
