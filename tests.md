# Remaining Jest Test Files

## Standalone Files (9 files)
```
test/esm.test.ts
test/fetch.test.ts
test/guardrails.test.ts
test/main.test.ts
test/onboarding.test.ts
test/providers.test.ts
test/sagemaker.test.ts
test/table.test.ts
test/telemetry.test.ts
```

## test/commands/ (24 files)
```
test/commands/auth.test.ts
test/commands/config.test.ts
test/commands/delete.test.ts
test/commands/eval.test.ts
test/commands/eval/evaluateOptions.test.ts
test/commands/eval/filterFailingBug.test.ts
test/commands/eval/filterProviders.test.ts
test/commands/eval/filterTests.test.ts
test/commands/eval/filterTestsUtil.test.ts
test/commands/eval/redteamWarning.test.ts
test/commands/export.test.ts
test/commands/import.test.ts
test/commands/init.test.ts
test/commands/mcp/lib/base-tool.test.ts
test/commands/mcp/lib/baseTool.test.ts
test/commands/mcp/lib/errors.test.ts
test/commands/mcp/lib/utils.test.ts
test/commands/mcp/tools/getEvaluationDetails.test.ts
test/commands/modelScan.test.ts
test/commands/share.test.ts
test/commands/show.test.ts
test/commands/validate-exit-codes.test.ts
test/commands/validate-provider-tests.test.ts
test/commands/view.test.ts
```

## test/evaluator/ (2 files)
```
test/evaluator/select-best-minimal.integration.test.ts
test/evaluator/trace-integration.test.ts
```

## test/server/ (7 files)
```
test/server/eval.test.ts
test/server/routes-eval.test.ts
test/server/routes/eval.export.test.ts
test/server/routes/eval.filteredMetrics.test.ts
test/server/routes/providers.test.ts
test/server/utils/downloadHelpers.test.ts
test/server/utils/evalTableUtils.test.ts
```

## test/redteam/ (108 files)

### Commands (8)
```
test/redteam/commands/crossSessionLeakGenerate.test.ts
test/redteam/commands/discover.test.ts
test/redteam/commands/generate.test.ts
test/redteam/commands/init.test.ts
test/redteam/commands/poison.test.ts
test/redteam/commands/report.test.ts
test/redteam/commands/run.test.ts
test/redteam/commands/setup.test.ts
```

### Constants (4)
```
test/redteam/constants.test.ts
test/redteam/constants/metadata.test.ts
test/redteam/constants/plugins.test.ts
test/redteam/constants/strategies.test.ts
```

### Extraction (3)
```
test/redteam/extraction/entities.test.ts
test/redteam/extraction/purpose.test.ts
test/redteam/extraction/util.test.ts
```

### Plugins (56)
```
test/redteam/plugins/aegis.test.ts
test/redteam/plugins/agentic/memoryPoisoning.test.ts
test/redteam/plugins/asciiSmuggling.test.ts
test/redteam/plugins/base.test.ts
test/redteam/plugins/beavertails.test.ts
test/redteam/plugins/bfla.test.ts
test/redteam/plugins/bias.test.ts
test/redteam/plugins/bola.test.ts
test/redteam/plugins/canGenerateRemote.test.ts
test/redteam/plugins/competitors.test.ts
test/redteam/plugins/contracts.test.ts
test/redteam/plugins/crossSessionLeak.test.ts
test/redteam/plugins/custom.test.ts
test/redteam/plugins/cyberseceval.test.ts
test/redteam/plugins/donotanswer.test.ts
test/redteam/plugins/ecommerceComplianceBypass.test.ts
test/redteam/plugins/ecommerceOrderFraud.test.ts
test/redteam/plugins/ecommercePciDss.test.ts
test/redteam/plugins/ecommercePriceManipulation.test.ts
test/redteam/plugins/ferpa.test.ts
test/redteam/plugins/financial/financialCalculationError.test.ts
test/redteam/plugins/financial/financialComplianceViolation.test.ts
test/redteam/plugins/financial/financialDataLeakage.test.ts
test/redteam/plugins/financial/financialHallucination.test.ts
test/redteam/plugins/financial/financialSycophancy.test.ts
test/redteam/plugins/harmbench.test.ts
test/redteam/plugins/harmful/aligned.test.ts
test/redteam/plugins/harmful/common.test.ts
test/redteam/plugins/harmful/graders.test.ts
test/redteam/plugins/harmful/unaligned.test.ts
test/redteam/plugins/imitation.test.ts
test/redteam/plugins/index.test.ts
test/redteam/plugins/indirectPromptInjection.test.ts
test/redteam/plugins/insurance/coverageDiscrimination.test.ts
test/redteam/plugins/insurance/networkMisinformation.test.ts
test/redteam/plugins/insurance/phiDisclosure.test.ts
test/redteam/plugins/intent.test.ts
test/redteam/plugins/mcp.test.ts
test/redteam/plugins/medical/medicalAnchoringBias.test.ts
test/redteam/plugins/medical/medicalHallucination.test.ts
test/redteam/plugins/medical/medicalIncorrectKnowledge.test.ts
test/redteam/plugins/medical/medicalPrioritizationError.test.ts
test/redteam/plugins/medical/medicalSycophancy.test.ts
test/redteam/plugins/offTopic.test.ts
test/redteam/plugins/overreliance.test.ts
test/redteam/plugins/pharmacy/controlledSubstanceCompliance.test.ts
test/redteam/plugins/pharmacy/dosageCalculation.test.ts
test/redteam/plugins/pharmacy/drugInteraction.test.ts
test/redteam/plugins/pii.test.ts
test/redteam/plugins/pliny.test.ts
test/redteam/plugins/pluginDocumentation.test.ts
test/redteam/plugins/pluginId.test.ts
test/redteam/plugins/policy.test.ts
test/redteam/plugins/rbac.test.ts
test/redteam/plugins/shellInjection.test.ts
test/redteam/plugins/toxicChat.test.ts
test/redteam/plugins/unsafebench.test.ts
test/redteam/plugins/unverifiableClaims.integration.test.ts
test/redteam/plugins/unverifiableClaims.test.ts
test/redteam/plugins/vlguard.test.ts
test/redteam/plugins/wordplay.test.ts
test/redteam/plugins/xstest.test.ts
```

### Providers (13)
```
test/redteam/providers/agentic/memoryPoisoning.test.ts
test/redteam/providers/crescendo/index.test.ts
test/redteam/providers/crescendo/prompts.test.ts
test/redteam/providers/custom/index.test.ts
test/redteam/providers/goat.test.ts
test/redteam/providers/hydra/index.test.ts
test/redteam/providers/iterative.test.ts
test/redteam/providers/iterativeMeta.test.ts
test/redteam/providers/iterativeTree.test.ts
test/redteam/providers/multi-turn-empty-response.test.ts
test/redteam/providers/shared.test.ts
test/redteam/providers/simba.redteamHistory.test.ts
test/redteam/providers/simba.test.ts
```

### Strategies (24)
```
test/redteam/strategies/base64.test.ts
test/redteam/strategies/bestOfN.test.ts
test/redteam/strategies/crescendo.test.ts
test/redteam/strategies/custom.test.ts
test/redteam/strategies/gcg.test.ts
test/redteam/strategies/goat.test.ts
test/redteam/strategies/hex.test.ts
test/redteam/strategies/homoglyph.test.ts
test/redteam/strategies/hydra.test.ts
test/redteam/strategies/index.test.ts
test/redteam/strategies/iterative.test.ts
test/redteam/strategies/layer.test.ts
test/redteam/strategies/leetspeak.test.ts
test/redteam/strategies/likert.test.ts
test/redteam/strategies/mathPrompt.test.ts
test/redteam/strategies/mischievousUser.test.ts
test/redteam/strategies/otherEncodings.test.ts
test/redteam/strategies/promptInjections.test.ts
test/redteam/strategies/retry.test.ts
test/redteam/strategies/rot13.test.ts
test/redteam/strategies/simpleAudio.test.ts
test/redteam/strategies/simpleImage.test.ts
test/redteam/strategies/simpleVideo.test.ts
test/redteam/strategies/strategyId.test.ts
test/redteam/strategies/util.test.ts
```

### Root-level (10)
```
test/redteam/graders.test.ts
test/redteam/index.test.ts
test/redteam/metrics.test.ts
test/redteam/remoteGeneration.test.ts
test/redteam/riskScoring.test.ts
test/redteam/shared.test.ts
test/redteam/sharedFrontend.test.ts
test/redteam/types.test.ts
test/redteam/util.test.ts
test/redteam/validators.test.ts
```
