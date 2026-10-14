# Phase Manifold Model: Recovery and Correspondence Tests

**Version:** 1.16  
**Source theory:** Phase Manifold Model 3.7.3, Core Revision 3.7.3  
**Author:** Scott Gehring  
**Recovery baseline date:** October 6, 2026  
**Revision date:** October 7, 2026  
**License:** CC BY 4.0

**Purpose:** Test whether the native Phase Manifold Model (PMM) reproduces established physical limits without importing recovery equations into the PMM foundation.

---

# RECOVERY IN ONE PAGE

PMM recovery begins with a frozen source theory.

**Source theory:** PMM 3.7.3, Core Revision 3.7.3

The recovery sequence is:

PMM native input  
→ stated bridge / limiting assumption  
→ established comparison target  
→ derivation  
→ recovery status

A recovery test can support compatibility within its stated domain. It does not convert a comparison equation, bridge, or fitted normalization into a PMM first principle.


## Recovery provenance and freeze rule

Every recovery result in this document carries one of four provenance classes:

**NATIVE CONSEQUENCE** — follows from the frozen PMM source theory without adding a recovery bridge.<br>
**CONDITIONAL RECOVERY** — follows only after one or more named PMM candidates or recovery bridges are supplied.<br>
**COMPATIBILITY RESULT** — shows that PMM variables can be mapped to established physics, but the comparison machinery is imported downstream.<br>
**FAILED BRIDGE** — a specific candidate bridge fails its stated test and is retired from that role.

A recovery is not rerun merely because a new interpretation is proposed. It is rerun only when an upstream native equation, source law, geometric bridge, or comparison domain changes. A result can therefore remain a conditional pass while one of its bridges is still open; later rejection of that bridge changes only the dependent branch rather than erasing unrelated recovery work.

Recovery failures are localized:

**Bridge failure** → reject or revise the bridge; the PMM baseline stays unchanged.  
**Candidate failure** → reject or revise the candidate relation.  
**Core failure** → revise the relevant PMM core relation before claiming recovery in that regime.

This document therefore acts as a firewall between PMM construction and correspondence testing.

---

# 1. Recovery Firewall

The canonical source theory is **PMM 3.7.3, Core Revision 3.7.3**. Recovery work does not silently modify that baseline.

Each recovery must identify:

1. **Native PMM inputs** — equations and definitions already present in the source theory.
2. **Candidate PMM inputs** — relations present in PMM but explicitly classified as candidates.
3. **Recovery bridge** — an added identification or limiting map used only for comparison.
4. **Established target** — the accepted physical relation being tested.
5. **Derivation** — the mathematical chain from PMM input through the bridge to the target.
6. **Status** — the result of the test.
7. **Failure consequence** — which layer changes if the test fails.

## 1.1 Recovery statuses

**PASS** — the stated PMM inputs reproduce the stated target under a bridge already justified within the recovery program.

**CONDITIONAL PASS** — the target is reproduced, but one or more required inputs or bridges remain candidate/open.

**PARTIAL** — one required sector is recovered while another required sector remains open.

**FAIL** — the stated PMM inputs and bridge produce a result incompatible with the comparison target.

**OPEN** — the derivation has not reached a testable comparison.

ALGEBRAIC PASS means that the stated mathematical identity or transformation test succeeds; it does not establish a physical bridge. Letter grades are qualitative research assessments rather than measured confidence levels. The §7 Recovery Ledger is the authoritative current summary; earlier grade comparisons document research history.

A recovery status applies only to the stated test. It does not upgrade CANDIDATE, POSTULATE, or OPEN items inside the source theory.

---

# 2. Recovery Baseline from PMM 3.7.3

The recovery program uses the following native multi-FTU gravity chain:

completed FTU  
→ persistent record Rᴬ  
→ accumulated history Φ  
→ active source extraction 𝒮[Φ] = sᴬ  
→ Clock Flux on the δ network  
→ relational clock potential φ  
→ lineage clock response κ = e⁻ᵠ  
→ relational D-clock gradient

## 2.1 Native clock response

Core 3.7.3 assigns the shared D angular increment to the FTU event and the normalized clock state to the participant lineage.

For event α incident on lineage 𝒫ᵢ:

κ(i|α)
=
[Δθᴰ(α)/Δt(i|α)]
/
[Δθᴰ(α)/Δt₀(i|α)]
=
Δt₀(i|α)/Δt(i|α).

By the Lineage Clock State Postulate, at relational slice n, incident events sampling the same lineage state satisfy:

κ(i|α) = κᵢⁿ.

Define:

φᵢ = −ln κᵢ.

Therefore the gravity recovery uses lineage-local clock potential rather than an FTU-indexed clock object.

For relational edge i↔j:

Γᵢⱼ = (φⱼ − φᵢ)/δᵢⱼ.

The gravitational acceleration readout is:

gᵢⱼ = c²Γᵢⱼ.

Core 3.7.3 also closes the architectural clock-response map: once the active source sᴬ is supplied, discrete Clock Flux determines φ on the δ network and κ follows from κ = e⁻ᵠ. The unresolved native step is the source-extraction map 𝒮[Φ].

## 2.2 Native Clock Flux form

For closed relational region Vᴿ:

∮∂Vᴿ ∇φ · dA = −λ<sub>G</sub> Qᴬ(Vᴿ)

The source coupling λ<sub>G</sub> is OPEN in the source theory.

The minimal scalar source identification is:

Qᴬ = ∑ completed Eᴬ/c²

This source identification is CANDIDATE in PMM 3.7.3.

## 2.3 Discrete origin

The native multi-FTU description is relational and discrete:

Γᵢⱼ = (φⱼ − φᵢ)/δᵢⱼ

and:

∑<sub>i↔j ∈ ∂Vᴿ</sub> A*ᵢⱼ Γᵢⱼ = −λ<sub>G</sub> Qᴬ(Vᴿ)

A continuum representation requires a many-FTU coarse-graining bridge. PMM 3.7.3 leaves that bridge OPEN.

---


# 2A. Local Lorentz / Null-Channel Recovery from PMM 3.7.3, Core Revision 3.7.3

PMM 3.7.3, Core Revision 3.7.3 retains the native reciprocal two-vantage scalar geometry while keeping its Lorentz interpretation behind the Recovery Firewall.

Native PMM input:

ρ₁ = Leʳ

ρ₂ = Le⁻ʳ

ρ₊ᴰ = ½(ρ₁ + ρ₂) = L cosh r

ρ₋ᴰ = ½(ρ₁ − ρ₂) = L sinh r

with:

(ρ₊ᴰ)² − (ρ₋ᴰ)² = L².

This is exactly the 1+1 SO(1,1) hyperbolic form at the scalar-readout level.

The native scale law also gives:

L = (ℏc/Eᴰ)θᴰ.

Define reciprocal recovery-channel energies:

ℰ₊ ≡ ℏcθᴰ/ρ₂ = Eᴰeʳ

ℰ₋ ≡ ℏcθᴰ/ρ₁ = Eᴰe⁻ʳ.

Then:

ℰ₊ℰ₋ = (Eᴰ)².

Recovery bridge (massive sector only):

ℰ₊ ↔ E + pc

ℰ₋ ↔ E − pc.

Therefore:

E = Eᴰ cosh r

pc = Eᴰ sinh r

and:

E² − p²c² = (Eᴰ)².

This physical mass-shell identification applies to massive carriers only. For a photon, E² − p²c² = 0 while the core carrier energy Eᴰ = ℏω is positive; the positive reciprocal-pair construction is not a photon mass-shell bridge.

For the massive PMM sector:

Eᴰ = mc²

so the standard relativistic mass-shell relation is recovered:

E² − p²c² = m²c⁴.

Also:

v/c = pc/E = tanh r

so:

r ↔ artanh(v/c)

under this recovery bridge.

The identification with physical E ± pc and rapidity is RECOVERY content. It does not by itself derive the native c¹/c² grade assignment P0.

## R0 — Local Special-Relativistic Kinematics

### Result

Reciprocal null-channel scaling: **ALGEBRAIC PASS**

Minkowski-type invariant: **ALGEBRAIC PASS**

r as rapidity-form coordinate: **ALGEBRAIC PASS**

L ↔ cτ timelike bridge: **CONSISTENT RECOVERY**

This proper-scale interpretation is massive/timelike only. In the fixed-frequency null readout, L = cΔt and L_cl = λ_wave/2 are frame-dependent while Δτ = 0; positive-pair SO(1,1) algebra does not establish a physical null embedding.

Physical identification of the full V₁/V₂ objects with spacetime null channels: **CANDIDATE**

Full 3+1 Lorentz covariance: **OPEN**

### Grade

**R0 local 1+1 Lorentz recovery: A algebraically / B physically at the recovery-structure level**

The algebraic covariance distinction is constructed in §2B by separating the intrinsic relative rapidity r_int from external observer rapidity η_obs. The remaining physical gap is experimental instantiation of V₁/V₂ and the neutral reference, plus extension beyond the local 1+1 construction.

---

## Impact on Earlier Recoveries

### R1 — Newtonian gravity

**No grade change.**

The Newtonian recovery depends on:

Qᴬ = M

Clock Flux normalization

and the discrete-to-continuum source bridge.

The new null-channel/Lorentz result does not derive any of these.

R1 remains:

**CONDITIONAL PASS / PARTIAL**

### R2 — Weak-field GR

**Local kinematic support improves; overall grade does not yet change.**

The new Lorentz structure gives the single-FTU D geometry a credible local Minkowski/null-coordinate limit.

This strengthens the interpretation that a local D event can admit special-relativistic kinematics.

However, R2's principal open problem is not local flat-space kinematics. It is the native derivation of the weak-field spatial metric, including the γ = 1 response, from the multi-FTU δ network and its coupling to the clock field.

Therefore R2 remains:

**CONDITIONAL PASS / NATIVE SPATIAL GAP**

The improvement is best recorded as:

local tangent-space / SR compatibility: **strengthened**

curved-space spatial recovery: **unchanged**

### R3 — Null / light sector

**This recovery improves materially.**

Previously PMM had:

dθᴰ = ωdt

dL = cdt

dτᴰ = 0

which gave a local null kinematic pass.

The Core Revision 3.7.3 reciprocal-channel geometry, together with the Recovery bridge above, gives an exact 1+1 light-cone Lorentz form and the standard massive energy-momentum invariant.

The null correspondence and the separate reciprocal-pair algebra should therefore be recorded as:

**NULL KINEMATIC CORRESPONDENCE / SEPARATE POSITIVE-PAIR 1+1 ALGEBRA; PHYSICAL BRIDGE CONDITIONAL**

Suggested grade:

**A− for local algebra / physical bridge conditional**

The grade is not A for the whole relativistic light sector because:

full 3+1 Lorentz covariance is not yet derived

and:

curved-space light deflection / Shapiro delay still depend on R2's unresolved spatial metric recovery.

### R4 — Source stability / relativistic source

**No grade change.**

The new kinematics do not derive the physical endpoint-continuation law, completed-record stress, creation/merger rules, or the relativistic source tensor; lineage identity is typed by ∼ᴸ.

R4 remains:

**CANDIDATE / CONDITIONAL STATIONARY + NEWTONIAN TOY SOURCE PASS**

---

## Revised Recovery Ledger

| Test | Target | Revised result | Main unresolved issue |
|---|---|---|---|
| R0 | Local SR / Lorentz structure and covariant closure | **A algebraic / B physical-recovery structure; COMMON-BOOST ALGEBRAIC PASS / PHYSICAL BRIDGE CONDITIONAL** | physical V₁/V₂ + neutral-reference instantiation; full 3+1 extension |
| R1 | Newtonian gravity | **CONDITIONAL PASS / PARTIAL — unchanged** | source extraction and continuum bridge |
| R2 | Weak-field GR | **CONDITIONAL PASS / NATIVE SPATIAL GAP — unchanged overall** | derive γ = 1 spatial response from δ-network geometry |
| R3 | Null / light sector | **NULL KINEMATIC CORRESPONDENCE / SEPARATE POSITIVE-PAIR 1+1 ALGEBRA; PHYSICAL BRIDGE CONDITIONAL** | full 3+1 covariance and curved-space optics |
| R4 | Source stability / relativistic source | **CANDIDATE / CONDITIONAL STATIONARY + NEWTONIAN TOY SOURCE PASS — unchanged** | effective-source extraction and relativistic stress source |

---

## Consequence for the Recovery Program

The algebraic covariance distinction is constructed in §2B:

r_int = r_obs − r_0,obs.

PMM can therefore construct common-boost invariant intrinsic balance while retaining the local 1+1 Lorentz-form algebra. Physical closure covariance remains conditional on the channel/reference and event-progress bridges.

The next recovery work is to justify the physical covariance bridge and to:

1. give V₁/V₂ and the neutral reference an independent physical instantiation;
2. extend the local construction toward full 3+1 covariance;
3. continue the δ-network spatial metric and completed-record source derivations required by R2 and R4.

The local Lorentz result does not replace the need for the δ-network spatial continuum derivation or the completed-record source law.

---

# 2B. Covariant Closure Recovery

The local Lorentz recovery raises a covariance question because PMM closure is expressed internally as:

θᴰ = π ⇒ r = 0

while a standard external null-coordinate boost shifts rapidity additively.

The common-boost algebraic construction at the 1+1 level distinguishes:

r_int = intrinsic PMM event imbalance

η_obs = external observer rapidity.

For an observer O:

r_obs = r_int + η_obs.

For the neutral reference pair of the same invariant scale:

r_0,obs = η_obs.

Therefore:

**r_int = r_obs − r_0,obs**

is invariant under a common external boost.

Equivalently:

r_int
=
½ ln[
(ρ₁,obs/ρ₂,obs)
/
(ρ₁,0,obs/ρ₂,0,obs)
].

Thus intrinsic balance is invariant under a common observer boost:

r_int = 0

iff:

ρ₁,obs/ρ₂,obs
=
ρ₁,0,obs/ρ₂,0,obs.

In the intrinsic D representation the neutral pair is balanced and this reduces to:

ρ₁ = ρ₂ = L.

Closure is fixed by θᴰ = π. Balance identifies terminal closure only for finite r₀ ≠ 0 within 0 < θᴰ ≤ π; for r₀ = 0, balance holds throughout D. The invariant construction below assumes L > 0, signature (+,−), and a neutral reference of the same scale under the same boost. Physical covariance additionally requires an independently justified event-progress variable θᴰ.

## Manifest invariant

Let:

Xᴼ
=
L(
cosh(r_int + η_obs),
sinh(r_int + η_obs)
)

and:

X₀ᴼ
=
L(
cosh η_obs,
sinh η_obs
).

Then:

Xᴼ · X₀ᴼ
=
L² cosh r_int.

Hence:

C_rel
=
(Xᴼ · X₀ᴼ)/L²
=
cosh r_int

is observer invariant.

PMM Closure Spread can therefore be written:

**Σ = 2L(C_rel − 1).**

This gives Σ a covariant recovery interpretation as the relative hyperbolic separation between the current event pair and its neutral reference.

## Result

**1+1 COMMON-BOOST ALGEBRAIC PASS / PHYSICAL CLOSURE BRIDGE CONDITIONAL**

Grade:

**A− algebraic recovery / physical bridge conditional**

Conditions:

- V₁/V₂ physical null-channel instantiation remains candidate.
- The neutral reference pair must have an independent physical meaning in any experiment.
- Full 3+1 covariance remains open.
- This is a recovery construction; it does not derive the PMM harmonic law.

## Effect on R0

R0's recovery-structure assessment changes from:

A algebraic / B− physical

to:

**A algebraic / B physical-recovery structure**

because the reference subtraction cancels a common observer boost algebraically; physical closure covariance remains conditional.

Common-boost cancellation establishes algebraic balance invariance. Physical channel/reference identification and the transformation of event progress remain open.

## Effect on R2 / R3

R2 weak-field GR remains unchanged overall because its main gap is still the multi-FTU spatial metric / δ-network recovery.

R3 retains its constant-frequency null correspondence. Separately, the positive reciprocal-pair construction has Lorentz-form algebra and common-boost balance invariance; its physical spacetime bridge remains conditional.

R3 local grade:

**A− for local algebra / physical bridge conditional**

Curved-space optical recovery remains conditional on R2.


# 3. R1 — Newtonian Gravity

**Question:** Does the PMM clock-gradient gravity chain reproduce Newtonian gravity in the weak, static, continuum regime?

**Current status:** **CONDITIONAL PASS / PARTIAL**

The normalization matches Newtonian gravity. A fully native recovery still depends on the candidate source Qᴬ = M and an open discrete-to-continuum bridge.

## 3.1 Native PMM inputs

PMM supplies:

φ = −ln κ

g = c²∇φ

and:

∮∇φ · dA = −λ<sub>G</sub> Qᴬ

Dimensional requirements give:

[λ<sub>G</sub>] = L/M

while:

[G<sub>N</sub>/c²] = L/M

## 3.2 Candidate source input

For the minimal mass-equivalent recovery test, take:

Qᴬ = M

This is a recovery use of the PMM minimal scalar source candidate. It is not promoted to a derived PMM source law by this test.

## 3.3 Established comparison target

For Newtonian gravity, the Gauss-law form is:

∮g · dA = −4πG<sub>N</sub>M

with local continuum form:

∇·g = −4πG<sub>N</sub>ρ

## 3.4 Recovery derivation

Start with PMM Clock Flux:

∮∇φ · dA = −λ<sub>G</sub>M

Using:

g = c²∇φ

multiply the flux equation by c²:

∮g · dA = −c²λ<sub>G</sub>M

Matching the Newtonian target requires:

c²λ<sub>G</sub> = 4πG<sub>N</sub>

therefore:

λ<sub>G</sub> = 4πG<sub>N</sub>/c²

The PMM flux law then becomes:

∮∇φ · dA = −(4πG<sub>N</sub>/c²)M

and:

∮g · dA = −4πG<sub>N</sub>M

In local continuum form:

∇²φ = −(4πG<sub>N</sub>/c²)ρ

and:

∇·g = −4πG<sub>N</sub>ρ

## 3.5 Potential correspondence

Introduce the conventional Newtonian potential Φ<sub>N</sub> only as a recovery variable, defined by:

g = −∇Φ<sub>N</sub>

Since PMM gives:

g = c²∇φ

comparison gives:

∇Φ<sub>N</sub> = −c²∇φ

therefore, up to an additive constant:

Φ<sub>N</sub> = −c²φ

This relation is a recovery correspondence. Φ<sub>N</sub> is not introduced as a PMM primitive.

## 3.6 What R1 establishes

R1 establishes that the PMM clock-gradient field can be normalized to the Newtonian weak-field law with:

λ<sub>G</sub> = 4πG<sub>N</sub>/c²

and the recovery correspondence:

Φ<sub>N</sub> = −c²φ

The attractive sign convention is consistent:

positive source  
→ κ < 1  
→ φ > 0 near the source  
→ φ decreases outward  
→ ∇φ points inward  
→ g points inward

## 3.7 What R1 does not establish

R1 does not derive λ<sub>G</sub> independently from PMM. Its value is fixed by matching Newtonian gravity.

R1 does not derive Qᴬ = M from the complete A-record architecture. Qᴬ = M is the minimal source candidate used by the test.

R1 also does not derive the many-FTU continuum limit from the discrete δ network.

For those reasons, R1 is a **CONDITIONAL PASS / PARTIAL** recovery rather than a completed native derivation of Newtonian gravity.

## 3.8 Failure consequences

If Qᴬ = M fails in later work, replace the source candidate and rerun R1. The upstream clock-gradient definition can survive that failure.

If the discrete δ-network cannot approach the required continuum flux law, the continuum recovery fails and the coarse-graining bridge must be revised.

If the native relation g = c²∇φ itself cannot reproduce the Newtonian field after a valid continuum limit and source law are supplied, the failure reaches the canonical PMM gravity readout.

---

# 4. R2 — Weak-Field General Relativity

**Question:** Can the same PMM clock response that recovers Newtonian acceleration reproduce the temporal weak-field metric relation of General Relativity, and can the δ network supply the accompanying spatial geometry?

**Current status:** **CONDITIONAL PASS / NATIVE SPATIAL GAP**

The temporal clock sector admits a direct candidate recovery bridge. The spatial weak-field metric and full curvature recovery remain open.

## 4.1 Native PMM inputs

PMM supplies:

κ = (dθᴰ/dt)/(dθᴰ/dt)₀

φ = −lnκ

therefore:

κ = e<sup>−φ</sup>

and:

g = c²∇φ

From R1:

Φ<sub>N</sub> = −c²φ

as a recovery correspondence.

PMM also supplies a relational spatial network through δᵢⱼ, with curvature represented discretely by deficit angles and a stated recovery route:

δ-network  
→ local frame  
→ connection  
→ curvature  
→ R

The detailed continuum bridge is OPEN in PMM 3.7.3.

## 4.2 Established weak-field temporal target

Using the conventional weak-field static metric with signature (−,+,+,+):

g₀₀ ≈ −(1 + 2Φ<sub>N</sub>/c²)

where |Φ<sub>N</sub>|/c² ≪ 1.

This equation is a comparison target from standard General Relativity, not a PMM input.

## 4.3 Candidate lapse bridge

**RECOVERY BRIDGE CANDIDATE R2-B1**

Identify the normalized PMM D angular-rate response with the normalized static lapse / clock-rate factor:

κ ↔ √(−g₀₀)

with the neutral reference normalized to g₀₀ = −1.

Then:

g₀₀ = −κ²

Using κ = e<sup>−φ</sup>:

g₀₀ = −e<sup>−2φ</sup>

For |φ| ≪ 1:

e<sup>−2φ</sup> ≈ 1 − 2φ

therefore:

g₀₀ ≈ −(1 − 2φ)

Using the R1 correspondence:

φ = −Φ<sub>N</sub>/c²

we obtain:

g₀₀ ≈ −(1 + 2Φ<sub>N</sub>/c²)

which matches the standard temporal weak-field relation.

## 4.4 Temporal-sector result

Conditional on bridge R2-B1:

κ = e<sup>−φ</sup> ↔ √(−g₀₀)

and the PMM clock field reproduces the standard weak-field g₀₀ relation to first order.

This is a **CONDITIONAL PASS for the temporal weak-field sector**.

The result is especially direct because the same PMM φ that supplies:

g = c²∇φ

also supplies the weak-field clock factor under R2-B1.

## 4.5 Spatial-sector recovery bridge

Earlier PMM recovery work used the normalized D lapse:

N_D = κ

and the isotropic scalar spatial coframe:

eⁱ = N_D<sup>−α</sup>dxⁱ

To first order:

gᵢⱼ ≈ (1 + 2αφ)δᵢⱼ

A standard linearized Einstein comparison in the locally isotropic / negligible-anisotropic-stress regime sets:

α = 1

so:

eⁱ = κ⁻¹dxⁱ

and:

gᵢⱼ ≈ (1 + 2φ)δᵢⱼ

Using:

φ = −Φ<sub>N</sub>/c²

gives:

gᵢⱼ ≈ (1 − 2Φ<sub>N</sub>/c²)δᵢⱼ

which is the GR weak-field spatial metric with PPN γ = 1.

**RECOVERY BRIDGE CANDIDATE R2-B2**

This bridge establishes weak-field metric compatibility. The value α = 1 is supplied by the Einstein comparison rather than derived from the current PMM δ network.

The native PMM target is therefore narrower:

derive the equivalent γ = 1 spatial response from C₂[Φ,δ,Σ] and the many-FTU δ-network continuum limit.

## 4.6 R2 test conditions

R2 now has a conditional first-order metric correspondence through R2-B1 and R2-B2.

The stronger native target requires:

**Temporal sector:** the κ ↔ lapse bridge to remain consistent beyond the first-order clock comparison.

**Spatial sector:** the δ-network continuum limit to derive the γ = 1 response without taking that value from the Einstein comparison.

The resulting combined metric must preserve the PMM null-sector behavior and yield the accepted weak-field relativistic observables within the stated limit.

## 4.7 Failure consequences

If κ cannot consistently map to the normalized lapse, reject bridge R2-B1. The PMM clock field itself is unchanged until a test reaches a native relation.

If the temporal bridge works while the δ-network spatial limit fails, R2 stays partial and the relational-to-continuum geometry bridge must be revised.

If a valid spatial continuum bridge exists but its curvature is incompatible with the temporal field generated by φ, the coupling between PMM clock response and relational geometry requires revision.

---

# 5. R3 — Null / Light Sector

**Question:** Does the PMM null sector reproduce local null kinematics, and can it recover weak-field gravitational optics?

**Current status:** **NULL KINEMATIC CORRESPONDENCE / SEPARATE POSITIVE-PAIR 1+1 ALGEBRA; PHYSICAL BRIDGE CONDITIONAL; GR OPTICS CONDITIONAL**

## 5.1 Native PMM inputs

For a null carrier with fixed positive Eγ and constant ω in the specified coordinate-time frame:

Eγ = ℏω

ℓ<sub>E</sub> = c/ω

Lγ = (c/ω)θᴰ

dθᴰ = ωdt

therefore:

dLγ/dt = c

and:

dτᴰ = 0

## 5.2 Local null result

The native PMM relations reproduce local propagation at c and zero proper-time accumulation.

This is a direct kinematic correspondence.

## 5.3 Gravitational optics

Light deflection and Shapiro delay require the spatial weak-field metric as well as the clock sector.

Using the R2 lapse bridge together with the recovery-level spatial bridge:

eⁱ = κ⁻¹dxⁱ

gives the first-order GR metric with PPN γ = 1.

Under that recovery metric, the standard null-geodesic equations supply the accepted weak-field light propagation.

## 5.4 R3 result

Local null kinematics: **CORRESPONDENCE under the stated null-sector definitions and constant-frequency assumption**

Local positive-pair SO(1,1) structure and reference-subtracted balance: **ALGEBRAIC PASS / PHYSICAL BRIDGE CONDITIONAL**

Curved-space light propagation: **CONDITIONAL ON R2**

The open elements are full 3+1 covariance and the PMM-native derivation of the spatial metric from the δ network.

---

# 6. R4 — Source Stability and Relativistic Completion

**Question:** Can persistent completed-event history supply a stable macroscopic gravity source without repeated counting, and can the same source become relativistic?

**Current status:** **CANDIDATE / CONDITIONAL STATIONARY + NEWTONIAN TOY SOURCE PASS; RELATIVISTIC OPEN**

## 6.1 Current source candidate

PMM proposes:

Qᴬ = ∑ completed Eᴬ/c²

while persistent history obeys:

Φⁿ⁺¹ = Append(Φⁿ,Rᴬⁿ)

## 6.2 Stationary-source test

A stationary macroscopic source should generate a stationary exterior field.

Introduce the research-level extraction map:

Qᴬ(V,n) = 𝒬[Φ;V,n]

A viable map must satisfy macroscopic idempotence for repeated equivalent records from an unchanged source:

𝒬[Append(Φ,R_repeat);V,n+1]
=
𝒬[Φ;V,n]

This preserves historical accumulation in Φ while preventing repeated event transcription from acting as repeated source mass.

## 6.3 Relativistic completion

The scalar source is adequate for the Newtonian recovery only after Qᴬ → M.

A full relativistic source also requires pressure, anisotropic stress, and the completed D deformation response.

PMM 3.7.3 already identifies the native D interaction-energy functional as open.

## 6.4 Latest-Record Source Projection

The relational event lattice supplies temporal lineage:

𝒫ᵢⁿ → 𝒫ᵢⁿ⁺¹

while Φᵢⁿ carries accumulated history.

For relational region V at slice n, let 𝓘(V,n) contain the extant participant lineages defined by ∼ᴸ.

For this conditional toy projection, suppose each lineage has an independently specified effective latest-source energy, with each source contribution assigned once. It must not copy a shared FTU energy into both participant lineages. Deriving these effective entries from completed records remains open:

Eᴬᵢ,* = ℏωᴬᵢ,*

Define:

Qᴬ_LRSP(V,n)
=
∑ᵢ∈𝓘(V,n) Eᴬᵢ,*/c²

For a stationary source with unchanged lineages and energies:

Qᴬ_LRSP(V,n+1)
=
Qᴬ_LRSP(V,n)

For the toy massive-source test, additionally assume each independent effective entry obeys:

Eᴬᵢ,* = mᵢc²

therefore:

Qᴬ_LRSP
=
∑ᵢmᵢ
=
M

Thus the toy LRSP sum is stationary for fixed independent entries and reproduces R1's scalar source when Eᴬᵢ,* = mᵢc² is supplied. It does not derive source allocation.

The discrete source may be assigned as:

sᴬᵢ(n) = Eᴬᵢ,*(n)/c²

on the node or dual cell.

**LRSP STATUS: CANDIDATE**

Lineage identity is now typed by the Core 3.7.3 Lineage Continuity Principle. The remaining source work is to derive the active source-extraction map 𝒮[Φ], prevent double counting of shared event history, and extend the scalar source to the relativistic stress sector.

## 6.5 R4 result

The conditional toy projection passes the fixed-lineage, fixed-energy stationary and Newtonian sum tests; it does not establish a native extraction or conservation law.

Relativistic source completion and the native active source-extraction law remain open.

R4 should be developed before stronger gravity or cosmology claims are promoted.

---

# 6A. R10 — A-Side Relativistic Source Reconstruction

**Question:** Can the existing PMM A-record, δ-network, lineage continuity, and lineage clock structure reconstruct the kinematic source content required for a relativistic stress-energy description without adding a new spatial primitive or silently importing a complete T<sub>μν</sub> into the core?

**Current status:** **CONDITIONAL PASS / PARTIAL RELATIVISTIC SOURCE RECONSTRUCTION**

R10 is a recovery test only. It does not modify P0 and does not adopt or assume an alternate c-order assignment as an input. Any c-order implication is assessed only after the reconstruction tests are completed.

## 6A.1 Native PMM inputs

PMM 3.7.3 supplies:

ωᴰ = Eᴰ/ℏ

κ(i|α) = Δt₀(i|α)/Δt(i|α)

𝒫ᵢⁿ → 𝒫ᵢⁿ⁺¹

𝓜ⁿ = {δᵢⱼⁿ, Φᵢⁿ, κᵢⁿ}

and the relational geometry statement that direction can be reconstructed after the δ-distance network is embedded. Four suitably independent participant lineages can define a relational three-dimensional cell.

The source theory also supplies:

Eᴬ = Eᴰ

and, for the massive rest-energy sector:

Eᴰ = mc².

For the null sector:

Eγ = ℏω

L = (ℏc/Eγ)θᴰ

xᴰ = Leᵃ

yᴰ = Le⁻ᵃ

zᴰ = L.

Therefore:

xᴰyᴰzᴰ = L³.

## 6A.2 R10a — Lineage Interval Bridge

The current source theory defines a neutral-reference comparison interval Δt₀ but does not independently specify its magnitude between relational slices. Intrinsic massive Tᴰ=τ does not fix this comparison interval without a neutral clock/synchronization bridge.

**RECOVERY BRIDGE CANDIDATE R10a-B1**

For a fixed event angular increment Δθᴰ(α), identify the neutral endpoint interval with the inverse D phase rate:

Δt₀(α)
=
Δθᴰ(α)/ωᴰ(α)
=
ℏΔθᴰ(α)/Eᴰ(α).

Using the native clock-response definition:

κ(i|α) = Δt₀(i|α)/Δt(i|α)

gives:

Δt(i|α)
=
ℏΔθᴰ(α)/[κᵢEᴰ(α)].

This relation introduces no new dimensional constant or clock variable. It identifies the already-defined neutral reference interval with the phase interval implied by E = ℏω.

### Null-sector check

For the PMM null sector:

dθᴰ = ωdt.

Therefore, in the neutral case κ = 1:

Δt₀ = Δθᴰ/ω = Δt.

So R10a-B1 agrees exactly with the existing null-sector coordinate-time relation.

**Null check: PASS under the existing null definitions.**

### Massive-sector check

R0 already contains the recovery-level timelike bridge:

L ↔ cτ.

For fixed Eᴰ, the native scale law gives:

dL = (ℏc/Eᴰ)dθᴰ.

Under the R0 timelike bridge:

dτ = dL/c = (ℏ/Eᴰ)dθᴰ.

Thus the neutral interval proposed by R10a-B1 has the same form as the recovered proper-time increment in the massive/timelike sector.

This agreement is conditional on the existing R0 timelike bridge; it is not a new core derivation of proper time.

**Massive check: CONDITIONAL PASS.**

### Clock-response check

R2-B1 uses the recovery correspondence:

κ ↔ √(−g₀₀).

For a fixed local phase increment, κ < 1 means a larger reference-coordinate interval is required to accumulate that phase. The R10a relation:

Δt = Δt₀/κ

has the same direction of clock slowing used by the existing gravity recovery.

**Clock consistency: PASS conditional on R2-B1.**

### Concurrency rule

Concurrent FTUs sampling one lineage clock state do not represent multiple successive elapsed-time increments. R10a therefore advances a lineage interval only along causally/continuationally ordered lineage segments. Concurrent incident events at the same relational slice share κᵢⁿ and must not be summed as duplicate time passage.

### R10a result

**LINEAGE INTERVAL BRIDGE: CONDITIONAL PASS**

The null limit is direct. The massive interpretation remains conditional on the existing timelike recovery bridge. A physical rule for synchronizing neighboring lineage intervals into one local comparison frame remains recovery content.

## 6A.3 R10b — Relational Direction, Displacement, and Massive Dust

The δ-network supplies distances but no primitive global direction vector. PMM states that direction can be reconstructed after embedding the relational distance network.

**RECOVERY BRIDGE CANDIDATE R10b-B1**

Embed a nondegenerate local δ-cell at relational slice n into a local Euclidean/tangent recovery frame and use the δ-network connection to compare that frame with the neighboring slice n+1.

For lineage i, let the recovered local position be Xᵢⁿ. Then:

ΔXᵢⁿ = Xᵢⁿ⁺¹ − Xᵢⁿ.

Choose one physically specified local reference clock or boundary clock to supply the slice interval Δtⁿ from R10a. Then define the recovered local velocity:

vᵢⁿ = ΔXᵢⁿ/Δtⁿ.

Translation and rotation of the embedding are frame gauge choices; only frame-related relative velocities enter the recovery.

This construction uses existing δ geometry, lineage identity, and clock information. It adds no new spatial primitive.

### Causality condition

A viable continuum recovery must satisfy:

|v| < c for massive lineages

and the existing null sector must approach:

|v| = c.

R10 does not derive these inequalities from arbitrary δ-network updates. They are consistency conditions on the allowed continuum/kinematic bridge.

### Massive dust target

For noninteracting massive matter, define the recovered proper mass density ρ₀ from deduplicated massive lineage content, with:

m = Eᴬ/c².

Using the recovered local four-velocity Uᵐ, the established dust target is:

T<sup>μν</sup><sub>dust</sub> = ρ₀ U<sup>μ</sup>U<sup>ν</sup>.

In the local rest frame:

U<sup>μ</sup> = (c,0,0,0)

so:

T<sup>00</sup> = ρ₀c²

T<sup>0i</sup> = 0

T<sup>ij</sup> = 0.

The source therefore has:

p = 0

for free dust.

Integrating the rest-mass density gives:

M = ∑ Eᴬ/c²,

which is the same scalar source used in R1 and R4.

### R10b result

Relational direction from δ geometry: **STRUCTURAL PASS**

Lineage displacement: **CONDITIONAL PASS**

Velocity reconstruction: **CONDITIONAL ON R10a + adjacent-slice frame comparison**

Free massive dust limit: **CONDITIONAL PASS**

Static Newtonian reduction to Qᴬ = M: **PASS under the existing R1 source candidate**

## 6A.4 R10c — Null / Radiation Equation-of-State Test

R10 tests two routes to the radiation source behavior.

### Route 1 — Isotropic null-direction recovery

Once the δ-network supplies a local frame, a null carrier can be assigned a recovered unit propagation direction n̂. For an isotropic distribution of null directions:

⟨nᵢnⱼ⟩ = δᵢⱼ/3.

The standard null-stream stress-energy average then gives:

p = u/3.

This route is a standard recovery construction; it does not derive isotropy from PMM.

### Route 2 — PMM scale-law deformation check

The native null scale law is:

L = (ℏc/Eγ)θᴰ.

For a fixed angular state θᴰ:

Eγ = ℏcθᴰ/L.

The native D geometry gives:

Vᴰ = xᴰyᴰzᴰ = L³.

Therefore, under an isotropic quasistatic scale variation at fixed θᴰ:

Eγ ∝ L⁻¹ ∝ (Vᴰ)⁻¹/³.

**RECOVERY BRIDGE CANDIDATE R10c-B1**

Interpret that fixed-θᴰ isotropic variation as the recovery analogue of an adiabatic volume variation for a freely propagating null contribution.

Then:

p = −dEγ/dVᴰ

=
Eγ/(3Vᴰ).

With:

u = Eγ/Vᴰ

this gives:

p = u/3.

The factor 1/3 is therefore reproduced by the PMM null scale law plus the D volume relation under R10c-B1.

This is not a native thermodynamic derivation unless the quasistatic fixed-θᴰ variation is independently justified as a physical deformation law.

### Massive comparison

For a free massive rest-energy contribution:

E = mc²

is independent of an isotropic recovery volume change when m is fixed. Therefore:

p = −dE/dV = 0.

This matches the free-dust result of R10b.

### R10c result

Isotropic null-direction route: **CONDITIONAL RECOVERY PASS**

PMM scale-law route to p = u/3: **ALGEBRAIC PASS / PHYSICAL DEFORMATION BRIDGE CONDITIONAL**

Massive free-dust comparison p = 0: **PASS under fixed rest mass**

The two routes are mutually consistent but are not independent native derivations of a radiation fluid.

## 6A.5 Interacting and anisotropic stresses

R10 does not close the full material source problem.

The current D geometry supplies only two independent spatial deformation combinations through ln L and a, while r is an internal c-grade imbalance rather than an established spatial pressure coordinate.

Therefore a generic interacting or anisotropic material source still requires an independently specified native D interaction-energy functional or an equivalent microscopic many-FTU dynamics.

The open target remains schematically:

Eᴰ = Eᴰ(L,a,r,θᴰ,carrier data,...)

with stress readouts derived from its physical deformation response rather than inserted by definition.

R10 therefore separates two problems:

free dust / radiation kinematic source reconstruction
→ partially recoverable from existing PMM structure

interacting / anisotropic material stress
→ still OPEN

## 6A.6 R10 result

R10 establishes the following conditional reconstruction chain:

A-record energy + event identity
→ Φ / lineage persistence
→ δ-network embedding
→ local direction and frame
→ R10a lineage interval
→ recovered motion / momentum flow
→ dust or null-source stress-energy in the corresponding limits.

The result is:

**R10 OVERALL: CONDITIONAL PASS / PARTIAL RELATIVISTIC SOURCE RECONSTRUCTION**

What passes:

- no new primitive spatial direction is required;
- the null sector supplies an exact neutral phase-time check for R10a;
- the massive/timelike interval has the correct form under the existing R0 bridge;
- free massive matter reduces to the R1/R4 scalar mass source in its rest limit;
- the null scale law reproduces p = u/3 under the stated deformation bridge.

What remains open:

- a native synchronization / adjacent-slice comparison law beyond the recovery gauge;
- proof that arbitrary δ-network evolution respects the required causal speed sector;
- active source extraction 𝒮[Φ] without double counting;
- interacting/composite D energy dynamics;
- generic anisotropic stress;
- full covariant continuum T<sub>μν</sub> construction.

### c-order conclusion after the c⁴ audit

R10–R12 do not require a change to the canonical c-order architecture.

The canonical assignment remains:

B = (c⁰)ₘₚ  
D = (c¹,c²)c  
A = (c³)k<sub>B</sub>

The earlier c⁴-as-A proposal is **RETIRED / NOT ADOPTED**. The appearance of G<sub>N</sub>/c⁴ in the standard stress-energy-to-curvature coupling is representation-dependent source bookkeeping and does not by itself select an FTU event grade.

A narrower downstream observation remains worth testing:

c⁴/G<sub>N</sub>

is the standard Planck-force scale. Under the existing gravitational-crease candidate L<sub>cl</sub>² = ℓₚ² and the PMM scale law L = (ℏc/E)θ, the normalized closure force readout:

F*<sub>cl</sub> ≡ E<sub>cl</sub>/(θ<sub>cl</sub>L<sub>cl</sub>)

gives:

F*<sub>cl</sub> = ℏc/L<sub>cl</sub>² = c⁴/G<sub>N</sub>.

This is a **RECOVERY-LEVEL / CONDITIONAL FORCE-RESPONSE CANDIDATE**, not a new c-order grade and not a replacement for the c³ A anchor.

---

# 6B. R11 — Multi-FTU Gate Audit: Causality, Lineage Momentum, and Source State

**Question:** Can the two hardest R10 blockers be reduced by recovering the invariant content of older PMM causal-flow and momentum-exchange laws, while preserving the current separation between FTU events, persistent lineages, A/Φ records, and relational δ geometry?

**Current status:** **CONDITIONAL PASS / TWO BLOCKERS NARROWED**

R11 is a recovery and architecture audit only. It does not restore an older PMM version wholesale and does not modify the frozen Core 3.7.3 baseline. Historical PMM equations are used only as candidate guidance and must be retyped into the current architecture before they can count as a present result.

## 6B.1 Historical structures being retested

Earlier PMM versions used a D causal-gauge norm of the form:

꜀² = v² + c<sub>C</sub>²

with ꜀ = c, giving:

χ² = 1 − v²/c²

and:

c²dτ² = c²dt² − dℓ².

Earlier versions also used a local momentum-exchange balance:

q₁ + q₂ + p<sub>carrier</sub> = 0.

These equations are not imported as current-core axioms. R11 asks whether their invariant content can be represented more cleanly by the variables that now exist in PMM 3.7.3.

## 6B.2 R11a — Causal Lineage Admissibility

The current R10 reconstruction supplies an adjacent-slice lineage displacement ΔXᵢ and a comparison interval Δt. Arbitrary δ-network updates were shown not to enforce a speed limit by themselves.

**RECOVERY BRIDGE CANDIDATE R11a-B1 — Lineage Lorentz Embedding**

For one adjacent continuation step of a massive lineage define the recovered interval:

Lᴸᵢ² = c²Δt² − ‖ΔXᵢ‖².

A massive/timelike continuation is admissible only when:

Lᴸᵢ² > 0.

A null continuation satisfies:

Lᴸᵢ² = 0.

A spacelike update with:

Lᴸᵢ² < 0

is rejected by the recovery bridge.

For the timelike sector introduce no new primitive rapidity. Define the **derived lineage rapidity readout** ηᵢᴸ by:

cosh ηᵢᴸ = cΔt/Lᴸᵢ

sinh ηᵢᴸ = ‖ΔXᵢ‖/Lᴸᵢ.

Then:

tanh ηᵢᴸ = ‖ΔXᵢ‖/(cΔt) = vᵢ/c.

This is the same SO(1,1) form already recovered in R0, but ηᵢᴸ belongs to the **lineage continuation step** and is not identified with the event-local native imbalance r.

### Explicit causal test

Take Δt = 1 s and ‖ΔX‖ = 0.6 light-second. Then:

Lᴸ = 0.8 light-second

and:

ηᴸ = artanh(0.6) ≈ 0.693.

The step is timelike and admissible.

Take instead ‖ΔX‖ = 1.5 light-seconds in the same Δt. Then:

Lᴸ² = (1 light-second)² − (1.5 light-seconds)² < 0.

No real timelike Lᴸ exists; the step is rejected.

For the null sector, the native PMM relation dLγ/dt = c already supplies the equality limit.

### R11a result

Massive causal ceiling: **CONDITIONAL PASS**

Null c limit: **PASS within the existing null-sector definitions**

Use of event-local r as a lineage velocity variable: **REJECTED**

Remaining dependency: the physical adjacent-slice embedding and synchronization bridge must establish that ΔXᵢ and Δt describe one continuing lineage step.

## 6B.3 R11b — Lineage Four-Momentum Continuity

R4 showed that summing completed event energies directly from Φ cannot by itself define the active source without a double-counting rule. The older PMM momentum-exchange law suggests a cleaner current formulation.

**RECOVERY / EXTENSION CANDIDATE R11b-B1 — Lineage Four-Momentum State**

Assign each extant lineage one current recovered four-momentum state at relational slice n:

Pᵢ<sup>μ</sup>(n) = (Eᵢ(n)/c, p⃗ᵢ(n)).

This is a lineage quantity, not an FTU-event quantity. For a realized pair event α = {i,j}, write the pre-event and post-event lineage states as Pᵢ⁻, Pⱼ⁻ and Pᵢ⁺, Pⱼ⁺.

The local continuity target is:

Pᵢ⁻ + Pⱼ⁻ + ∑P<sub>in,carrier</sub>
=
Pᵢ⁺ + Pⱼ⁺ + ∑P<sub>out,carrier</sub>.

For a closed two-lineage interaction with no external carrier:

Pᵢ⁻ + Pⱼ⁻ = Pᵢ⁺ + Pⱼ⁺.

Equivalently define signed endpoint transfers:

ΔPᵢ|α = Pᵢ⁺ − Pᵢ⁻

ΔPⱼ|α = Pⱼ⁺ − Pⱼ⁻

so that for the closed pair:

ΔPᵢ|α + ΔPⱼ|α = 0.

This is the current-architecture analogue of the older q₁ + q₂ + p<sub>carrier</sub> = 0 law.

### Record versus current state

R11 distinguishes:

A/Φ → completed transaction history

Pᵢ<sup>μ</sup>(n) → current carried energy-momentum state of lineage i.

Therefore repeated persistence of one completed FTU does not create repeated source energy. The current state can be reconstructed from an initial lineage state plus signed event transfers:

Pᵢ<sup>μ</sup>(n)
=
Pᵢ<sup>μ</sup>(n₀) + ∑<sub>α∈𝒫ᵢ,n₀→n</sub> ΔPᵢ|α<sup>μ</sup>.

The same shared event α may be referenced in both participant histories, but its endpoint transfers carry opposite or otherwise conservation-balanced signs. The event is therefore not counted twice as two independent source energies.

### Compatibility with the current A-side record

The minimal record Rᴬ = {ωᴬ,a<sub>cl</sub>,Iᴬ} is not by itself sufficient to reconstruct a generic vector transfer ΔPᵢ|α<sup>μ</sup>. However, Core §26 already permits C₃ to transcribe completed energy-and-response content into the richer A-side response record 𝓡ᴬ<sub>μν,α</sub>.

R11 therefore does **not** require the minimal informational record Rᴬ to carry all momentum data. It requires either:

1. a derivation showing that the necessary signed transfer is reconstructible from existing completed response content; or
2. a minimal C₃ extension of that response record.

This remains the native derivation target.

### R11b result

Local four-momentum balance: **STRUCTURALLY CONSISTENT / CANDIDATE**

Stationary-source double counting: **RESOLVED at the state-accounting level**

Native derivation of transfer ΔP from D dynamics: **OPEN**

Reconstruction from the minimal Rᴬ alone: **FAIL**

Reconstruction from richer C₃ energy-response content: **CANDIDATE**

## 6B.4 R11c — Active Source Extraction from Current Lineage State

If R11b succeeds, the active gravitational source should not be defined as a raw sum over all historical event energies. Instead, Φ provides the ordered transaction history from which the current lineage states are reconstructed.

Define the recovery-level current-state extraction:

𝒮<sub>P</sub>[Φ; {Pᵢ(n₀)}]
→
{Pᵢ(n)}.

The scalar Newtonian projection in a region V is then:

Qᴬ(V,n)
=
∑<sub>i∈𝓘(V,n)</sub> Eᵢ(n)/c²

in the slow/static massive limit.

For a stationary isolated source with unchanged current lineage states:

Qᴬ(V,n+1) = Qᴬ(V,n)

even though Φ continues to retain the already-completed history.

Thus history persistence and active source content are separated:

Φ = ledger

𝒮<sub>P</sub>[Φ] = current state reconstruction

Qᴬ = source projection of the current state.

**R11c STATUS: CONDITIONAL PASS at the accounting level / NATIVE TRANSFER LAW OPEN**

The unresolved issue is no longer generic "double counting." It is specifically the derivation of event-to-lineage four-momentum transfer and the completeness of the A-side response record needed to reconstruct it.

## 6B.5 R11d — Free-Lineage Kinetic Stress-Energy

Once a local frame, current lineage four-momenta, and a relational averaging volume V* are supplied, a free-lineage kinetic source can be written at recovery level as:

T<sup>μν</sup><sub>kin</sub>(V,n)
=
(c/V*) ∑<sub>i∈V</sub>
[Pᵢ<sup>μ</sup>Pᵢ<sup>ν</sup>/Pᵢ<sup>0</sup>].

For a massive lineage at rest:

P<sup>μ</sup> = (mc,0,0,0)

so:

T<sup>00</sup> = mc²/V*

and the free-particle spatial stress vanishes.

For null lineages with P<sup>0</sup> = E/c and |p⃗| = E/c, isotropic directional averaging gives the standard free-radiation relation p = u/3, consistent with R10c.

This construction supplies energy density, momentum density, and kinetic stress for free lineages without requiring a general material interaction-energy functional. Binding energy, constitutive stress, and generic interacting/composite stress remain OPEN.

**R11d STATUS: CONDITIONAL KINETIC-SOURCE PASS / INTERACTING STRESS OPEN**

## 6B.6 R11e — Null-Calibrated Spatial Response Candidate

R2 currently obtains the weak-field spatial coframe:

eⁱ = κ<sup>−1</sup>dxⁱ

only after setting the free exponent α = 1 by Einstein comparison. R11 tests whether the PMM null sector can instead fix this exponent operationally.

**RECOVERY BRIDGE CANDIDATE R11e-B1 — Null-Calibrated Relational Distance**

In a locally isotropic recovery cell, define the physical scale of an infinitesimal relational edge by a null round-trip measurement. Since the native null sector gives local propagation at c, the measured edge scale is proportional to its local light-travel interval. Relative to the neutral reference edge:

δ/δ₀ = ΔT<sub>light</sub>/ΔT<sub>light,0</sub>.

Using the lineage clock definition:

κ = Δt₀/Δt

gives:

δ/δ₀ = κ<sup>−1</sup> = e<sup>φ</sup>.

Therefore the isotropic recovery coframe is selected as:

eⁱ = κ<sup>−1</sup>dxⁱ

under an additional distance-clock identification. This is a recovery candidate, not a consequence of intrinsic Tᴰ = τ or of the rate-based κ alone. To first order:

gᵢⱼ = κ<sup>−2</sup>δᵢⱼ
≈
(1 + 2φ)δᵢⱼ.

With the existing R1 correspondence φ = −Φ<sub>N</sub>/c², this yields the weak-field γ = 1 spatial response.

**R11e STATUS: PROMISING CONDITIONAL PASS**

The bridge is not native until δ is operationally connected to null-calibrated relational distance. Circular use of a pre-assumed GR spatial metric would invalidate the derivation.

### Prospective higher-order discriminator

If R11e-B1 is later promoted and if the same scalar φ controls the all-orders static isotropic sector, the natural candidate metric becomes:

ds² = −e<sup>−2φ</sup>c²dt² + e<sup>2φ</sup>d𝐱².

This agrees with the existing weak-field temporal and spatial relations at first order. It is **not yet a PMM prediction**. A strong-field φ equation and a native δ↔null-distance bridge are required before comparing its higher-order coefficients with GR.

## 6B.7 Gate results after R11

Gate 1 — causal discrete kinematics:
**FAIL in unconstrained R10 δ evolution → CONDITIONAL PASS under R11a**

Gate 2 — active source extraction:
**FAIL as raw historical energy sum → CONDITIONAL ACCOUNTING PASS under R11b/R11c; native transfer law OPEN**

Gate 3 — relativistic T<sub>μν</sub>:
**PARTIAL → CONDITIONAL PASS for free kinetic massive/null sources; interacting/composite stress OPEN**

Gate 4 — native weak-field spatial response:
**OPEN → PROMISING CONDITIONAL PASS under R11e; δ operational bridge OPEN**

Gate 5 — novel falsifiable consequence:
**NOT YET PASSED.** R11e exposes a possible higher-order discriminator, but it cannot be promoted until the all-orders spatial bridge and φ dynamics are derived independently.

## 6B.8 R11 overall result

R11 shows that the two hardest blockers do not currently require a new single-FTU foundation. The older causal-flow and momentum-exchange structures can be compressed into two cleaner multi-FTU candidates:

1. **Causal Lineage Admissibility** — adjacent lineage continuation must possess a real timelike/null interval.
2. **Lineage Four-Momentum Continuity** — pair events update current lineage states by locally conserved four-momentum transfer.

The first is largely a re-expression of already recovered Lorentz structure. The second introduces real multi-FTU dynamical content unless it can be derived from D interaction dynamics and the existing C₃ energy-response transcription.

**R11 OVERALL: CONDITIONAL PASS / ONE GENUINELY OPEN DYNAMICAL LAW REMAINS**

The main remaining law-level blocker is therefore narrower:

**derive the event-to-lineage four-momentum transfer ΔP from native D dynamics, or state Lineage Four-Momentum Continuity explicitly as a multi-FTU postulate.**

---


# 6C. R12 — Event-to-Lineage Transfer Audit

**Question:** Once causal lineage motion and four-momentum continuity are imposed, do the current PMM D variables uniquely determine the signed endpoint transfer ΔPᵢ|α for a realized pair event, or does PMM still require an interaction law that selects one outcome from the conservation-allowed family?

**Current status:** **PARTIAL / KINEMATIC CONSERVATION PASS / DYNAMICAL ALLOCATION FAIL**

R12 preserves the Core 3.7.3 baseline. It does not promote the R11 lineage four-momentum state into the PMM foundation. Its purpose is to distinguish a conservation constraint from a genuine event dynamics.

## 6C.1 R12a — Closed two-lineage elastic event

Consider one realized pair event:

α = {i,j}.

Supply incoming massive lineage states:

Pᵢ⁻, Pⱼ⁻

and fixed rest masses mᵢ, mⱼ. Require the R11 balance law:

Pᵢ⁻ + Pⱼ⁻ = Pᵢ⁺ + Pⱼ⁺

with the outgoing mass-shell conditions:

Pᵢ⁺·Pᵢ⁺ = mᵢ²c²

Pⱼ⁺·Pⱼ⁺ = mⱼ²c².

These conditions restrict the outgoing states but do not generally determine them uniquely.

### Explicit equal-mass center-of-momentum test

For two equal massive lineages in their center-of-momentum frame, let:

Pᵢ⁻ = (E/c, +p êₓ)

Pⱼ⁻ = (E/c, −p êₓ).

For any unit spatial direction n̂, the outgoing states:

Pᵢ⁺ = (E/c, +p n̂)

Pⱼ⁺ = (E/c, −p n̂)

satisfy the same total four-momentum and the same mass shells.

Therefore conservation fixes the total and, in this elastic center-of-momentum example, the outgoing momentum magnitude, but leaves the scattering direction free. In three spatial dimensions this is a continuous angular family of allowed outcomes.

For unequal masses the invariant total energy and the two mass shells likewise fix the center-of-momentum momentum magnitudes once the channel is specified, while the outgoing direction still requires an interaction law.

### Can current PMM event variables select n̂?

The present variables do not supply a demonstrated participant-level selection rule:

- Eᴰ supplies an event energy readout, not a participant scattering angle;
- L and θᴰ supply the event scale/progression law;
- r is an internal c¹/c² D-vantage imbalance, not a participant momentum direction, and r → 0 at closure;
- a is a planar shape coordinate, with no current bridge identifying a_cl with an outgoing lineage scattering direction;
- δ supplies relational geometry and a local frame, but a frame does not by itself select an impulse within that frame;
- C₂ has the correct architectural role as path constraint, but no current C₂ interaction functional maps the incoming lineage states to a unique outgoing channel;
- C₃ can record the completed response after the event, but recording an outcome does not derive which outcome occurs.

**R12a RESULT:**

Four-momentum conservation: **PASS as a constraint**

Mass-shell consistency: **PASS as a constraint**

Unique outgoing ΔPᵢ|α from current PMM variables: **FAIL**

Failure type: **missing interaction dynamics, not conservation failure**

## 6C.2 R12b — Carrier-emission event

Now allow an outgoing null carrier with four-momentum K:

Pᵢ⁻ + Pⱼ⁻ = Pᵢ⁺ + Pⱼ⁺ + K

with:

K·K = 0

and positive carrier energy.

The PMM null sector supplies the local relation:

|p⃗γ| = Eγ/c

and local propagation at c. These conditions correctly type an emitted null carrier but do not determine Eγ or its propagation direction n̂γ.

Even after fixing the incoming total four-momentum, conservation admits a family of massive outgoing states plus carrier energies/directions unless an interaction or transition law selects one channel.

**R12b RESULT:**

Null carrier kinematics: **PASS / already recovered**

Total four-momentum balance: **PASS as a constraint**

Emission energy and direction from current PMM D dynamics: **FAIL / UNDERDETERMINED**

## 6C.3 R12c — Sequential lineage accounting

Suppose the signed endpoint transfers are supplied by a future valid interaction law. Then the R11 current-state recursion is exact:

Pᵢ(n)
=
Pᵢ(n₀) + ∑α ΔPᵢ|α.

For a sequence of closed pair events, local balance makes internal transfers telescope across the participating lineages. A completed event may be referenced in both participant histories without becoming two independent source-energy copies because the endpoint transfers are signed and balance at the event.

Therefore the current-state / history separation survives the explicit event-chain test:

A/Φ = persistent transaction ledger

{Pᵢ(n)} = current carried lineage state.

Repeated retention of one A record changes the historical ledger but does not by itself change the current source state.

**R12c RESULT:** **ACCOUNTING PASS CONDITIONAL ON A VALID ΔP LAW**

The double-counting problem remains closed at the accounting level. Predictive evolution remains open because ΔP is not yet derived.

## 6C.4 R12d — Why the present D action does not select the transfer

Core 3.7.3 defines:

dSᴰ = ℏdθᴰ

therefore:

Sᴰ(θᴰ) = ℏθᴰ

and with θᴰ_cl = π:

Sᴰ,cl = πℏ.

The core explicitly treats this action as the common phase-action ruler / ledger rather than as the dynamical generator of realization or transcription.

For fixed closure θᴰ = π, the completed D action readout is the same πℏ for every conservation-allowed scattering direction in the R12a family. It therefore contains no demonstrated directional dependence capable of selecting n̂.

Consequently, varying the present Sᴰ = ℏθᴰ alone cannot distinguish one elastic scattering angle from another. A transfer law requires additional interaction-dependent structure.

**R12d RESULT:** **CURRENT D ACTION INSUFFICIENT AS AN INTERACTION GENERATOR**

This is not a failure of the action readout. It is a scope result: the present action was not defined to perform this dynamical task.

## 6C.5 R12e — Historical PMM interaction machinery

Earlier PMM versions contained a broader D-phase field-action template with a matter sector and a reserved interaction term, schematically:

𝒜ᴰ_field = ∫ d⁴x √(−gᴰ) 𝓛ᴰ

with an interaction sector such as:

𝓛_int[Φ,δ]

left for coupling dynamics.

Those versions also contained the momentum-exchange conservation equation later compressed into R11.

However, the historical interaction term was reserved rather than physically specified. It therefore cannot be imported as an already-derived solution to R12. The older work correctly anticipated the need for an interaction generator but did not provide the law that fixes ΔP.

**R12e RESULT:** **USEFUL HISTORICAL POINTER / NO RECOVERABLE COMPLETED TRANSFER LAW**

## 6C.6 R12f — Minimal missing dynamical object

R12 reduces the remaining transfer problem to one of two mathematically equivalent research routes.

### Route A — D interaction action / generator

Supply an independently motivated interaction contribution that depends on the relevant incoming states and relational geometry. Variation must produce the event equations and signed endpoint impulses rather than merely enforce the final conservation identity.

Schematic target:

Sᴰ_total = Sᴰ_phase + Sᴰ_int

with:

Sᴰ_phase = ℏθᴰ

and Sᴰ_int not yet derived.

The resulting event equations must determine or probabilistically weight ΔPᵢ|α while preserving local four-momentum conservation and the current event/lineage typing.

### Route B — C₂ outcome / transition kernel

Alternatively, C₂ may supply a normalized conditional outcome law over the conservation-admissible outgoing channels:

𝒦α(outgoing channel | incoming lineage state, Φ, δ, event data).

C₁ selects which pair contact actualizes. A future C₂ interaction law would then determine or weight what happens during that realized contact. C₃ would record the completed outcome.

The kernel must not identify c¹/c² D-vantage slots with permanent participant identities and must reduce to the existing free massive/null recovery limits when interaction is absent.

R12 does not choose between Route A and Route B. A deterministic interaction action and a probabilistic transition kernel are alternative formulations until a deeper PMM derivation selects one.

## 6C.7 Consequence for the relativistic source program

Given supplied current lineage momenta, the R11 kinetic source remains valid as a recovery construction:

T^{μν}_kin
=
(c/V*) ∑ᵢ Pᵢ^μPᵢ^ν/Pᵢ^0.

R12 therefore does not invalidate the dust/radiation or kinetic T^{μν} results. It changes their predictive status:

current P states supplied or measured
→ T^{μν}_kin reconstructible

native event dynamics supplied
→ future P states predictable.

The first step is conditionally available. The second is not yet native.

## 6C.8 Gate results after R12

Gate 1 — causal discrete kinematics:
**CONDITIONAL PASS under R11a; unchanged by R12**

Gate 2 — active source extraction:
**ACCOUNTING PASS / DYNAMICAL EVOLUTION OPEN.** Source double counting is controlled, but current source evolution cannot be predicted until ΔP is selected.

Gate 3 — relativistic T<sub>μν</sub>:
**CONDITIONAL KINEMATIC PASS for supplied free-lineage states / PREDICTIVE DYNAMICS OPEN.**

Gate 4 — native weak-field spatial response:
**PROMISING CONDITIONAL PASS under R11e; unaffected by R12.**

Gate 5 — novel falsifiable consequence:
**NOT YET PASSED.** A predictive interaction law or independently derived strong-field spatial bridge is still required before a new discriminator is promoted.

## 6C.9 R12 overall result

R12 rejects the idea that four-momentum conservation alone is the missing PMM interaction law.

The sharper result is:

**conservation constrains ΔP; it does not select ΔP.**

Current PMM provides a strong event architecture, causal/recovery kinematics, completed energy continuity, relational geometry, and a consistent way to record/reconstruct current lineage states. It does not yet provide a participant-level interaction generator that selects one outgoing momentum channel from the conservation-allowed family.

The remaining law-level blocker is therefore renamed more precisely:

**Native D Interaction Law / C₂ Outcome Law**

with event-to-lineage four-momentum transfer ΔPᵢ|α as its required readout.

**R12 OVERALL: PARTIAL / CONSERVATION STRUCTURE SURVIVES / INTERACTION DYNAMICS OPEN**

This result leaves the canonical A = (c³)k<sub>B</sub> architecture unchanged. The unresolved dynamics remain upstream in D/C₂: current lineage source states can be accounted for once ΔP is known, but the law generating or weighting ΔP is still missing.

---

# 6D. R13 — Native D Interaction / C₂ Outcome Audit

**Question:** Do the frozen PMM 3.7.3 variables and constraints determine, or uniquely probabilistically weight, the event-to-lineage four-momentum transfer ΔP identified by R12?

**Current status:** **FAIL AS A NATIVE DERIVATION / MISSING DYNAMICAL LAW IDENTIFIED**

R13 does not modify Core 3.7.3. It treats the R12 conservation law as an admissibility condition and asks whether the current D/C₂ structure contains enough additional information to choose one physical outgoing channel.

## 6D.1 R13a — Invariant inventory

The current architecture supplies the following relevant data classes.

**Recovered lineage state**

Pᵢ^μ = (Eᵢ/c, p⃗ᵢ)

Pⱼ^μ = (Eⱼ/c, p⃗ⱼ)

with causal/mass-shell constraints supplied by the existing massive/null recovery. From these states one may form the usual local invariants, including Pᵢ², Pⱼ², and the total pair invariant c²(Pᵢ + Pⱼ)².

**Native single-FTU D data**

Eᴰ, θᴰ, L, a, r, Σ, Θ<sub>win</sub>, together with the selected-pair D-vantage seed weights.

**Multi-FTU relational/context data**

δᵢⱼ, the locally embedded δ-network when available, Φ, and the lineage clock state κ or φ when gravity-sector timing is relevant.

Dimensionless combinations can be built, for example, from θᴰ, a, r, Σ/L, and ratios such as δ/L when the quantities refer to one specified local comparison. The recovered four-momentum data also allow outcome-dependent invariants such as the transfer variable:

t = c²(Pᵢ⁺ − Pᵢ⁻)².

For a two-body elastic event, choosing t is equivalent to choosing the scattering angle once the incoming invariant energy and masses are fixed.

The key R13 question is therefore whether the existing PMM inputs determine t.

**R13a RESULT:** **INVARIANT INVENTORY COMPLETE ENOUGH TO DEFINE THE ADMISSIBLE CHANNEL SPACE; NO EXISTING NATIVE RELATION FOUND THAT FIXES THE OUTCOME VARIABLE t.**

## 6D.2 R13b — Equal-mass elastic family

Use local center-of-momentum units with c = 1 for this toy test. Let two equal massive lineages have m = 1 and incoming three-momentum magnitude p = 0.75. Then each incoming energy is:

E = √(m² + p²) = 1.25.

Choose the incoming z axis:

Pᵢ⁻ = (1.25, 0, 0, 0.75)

Pⱼ⁻ = (1.25, 0, 0, −0.75).

For every angle χ, define:

Pᵢ⁺(χ) = (1.25, 0.75 sinχ, 0, 0.75 cosχ)

Pⱼ⁺(χ) = (1.25, −0.75 sinχ, 0, −0.75 cosχ).

For every χ:

Pᵢ⁺ + Pⱼ⁺ = (2.5, 0, 0, 0) = Pᵢ⁻ + Pⱼ⁻

and:

(Pᵢ⁺)² = (Pⱼ⁺)² = 1.

Thus four-momentum conservation, the mass shell, and the causal ceiling are all satisfied by the continuous family χ ∈ [0,π].

The transfer invariant varies across the family:

t(χ) = −2p²(1 − cosχ)

so the physically distinct outcomes are not merely coordinate relabelings.

Current PMM does not provide a relation t = t(Eᴰ,L,a,r,θᴰ,Σ,δ,Φ,...) or an equivalent rule that selects χ.

**R13b RESULT:** **FAIL — THE CURRENT CORE DOES NOT SELECT A UNIQUE ELASTIC OUTGOING CHANNEL.**

## 6D.3 R13c — Carrier-emission family

The underdetermination becomes stronger when a null carrier can leave the event.

Again use a local center-of-momentum frame with c = 1. Let the incoming pair have total energy W and total spatial momentum zero. A possible emitted null carrier has:

Kγ = (ε, ε n̂)

with arbitrary unit direction n̂. The residual two-lineage four-momentum is:

Q = P<sub>tot</sub> − Kγ.

Its invariant is:

Q² = W² − 2Wε.

For two equal residual masses m, the kinematic threshold is:

Q² ≥ 4m².

For the explicit choice W = 4m, every emission energy in:

0 < ε ≤ 1.5m

can satisfy that threshold, and n̂ remains free before the residual pair is further resolved.

Conservation therefore permits a continuous family of emission energies and directions. Current PMM supplies the null relation |pγ| = Eγ/c once a carrier state is specified, but it does not determine ε or n̂ from the native D equations.

**R13c RESULT:** **FAIL / UNDERDETERMINED — CONSERVATION AND NULL KINEMATICS DO NOT GENERATE THE EMISSION LAW.**

## 6D.4 R13d — Can an existing PMM D variable select the channel?

R13 tests the strongest apparent candidates directly.

**θᴰ / Sᴰ**

At completed closure, θᴰ = π and Sᴰ = πℏ for the whole R13b elastic family. The present phase-action readout therefore does not distinguish χ.

**r**

r is the internal c¹/c² D-vantage imbalance. The current core explicitly does not identify V₁/V₂ with participant lineages, and r → 0 at closure. Promoting r to participant scattering rapidity or angle would violate the present event/lineage typing.

**a**

a is a planar x-y shape coordinate. No current PMM bridge identifies a or a<sub>cl</sub> with the direction of an outgoing participant momentum. Such an identification would be a new physical bridge.

**Ξ̃ᴰ / half-angle transport**

The current core permits a mathematical half-angle carrier, but its interpretation as physical spatial rotation is explicitly conditional and lacks a native rotation-axis/outgoing-momentum bridge. It cannot presently select the scattering plane or angle.

**δ**

The embedded δ-network can reconstruct relational direction, but a direction field is not an interaction law. No native potential U(δ), force law, or impulse functional is currently specified that maps the relational geometry to ΔP.

**Φ**

Φ records completed history and conditions later admissibility/timing. No current source-history functional provides an outgoing-channel probability or deterministic transfer rule.

**R13d RESULT:** **NO EXISTING PMM VARIABLE CAN BE REINTERPRETED AS THE MISSING SELECTOR WITHOUT ADDING NEW PHYSICAL CONTENT.**

## 6D.5 R13e — Minimal completion classes

Two completion classes remain mathematically possible.

### Deterministic C₂ map

A future law could define:

Γ<sub>out</sub> = F<sub>C₂</sub>(Γ<sub>in</sub>; Φ, δ, event data)

with the map required to preserve local four-momentum balance, the massive/null shell conditions, covariance in the recovered local frame, and the present participant/vantage distinction.

No such F<sub>C₂</sub> is derived by Core 3.7.3.

### Normalized C₂ transition kernel

More generally define a conditional measure over the conservation-admissible outcome space Ω<sub>out</sub>:

𝒦<sub>C₂</sub>(dΓ<sub>out</sub> | Γ<sub>in</sub>, Φ, δ, event data) ≥ 0

with:

∫<sub>Ωout</sub> 𝒦<sub>C₂</sub> = 1.

A deterministic law is the special case in which the kernel is concentrated on one outcome. A genuinely probabilistic interaction is represented by a nontrivial distribution.

At minimum, a valid kernel must:

1. assign zero weight to four-momentum-nonconserving channels;
2. assign zero weight to channels violating the relevant massive/null causal shell;
3. transform consistently under the recovered local Lorentz frame;
4. respect pair/participant exchange symmetry when the physical event has that symmetry;
5. depend only on physically available local relational/history data;
6. reduce to the free-lineage limit when interaction vanishes;
7. never identify c¹/c² D-vantage order with permanent participant identity;
8. be normalized over the complete admissible outcome set.

These conditions restrict a future law but do not determine one. Infinitely many kernels can satisfy them.

**R13e RESULT:** **A C₂ KERNEL IS A CLEAN MINIMAL PLACEHOLDER, NOT A DERIVATION. SPECIFYING ITS PHYSICAL WEIGHTS WOULD BE NEW DYNAMICAL CONTENT.**

## 6D.6 R13f — Interaction-action route

R12 proposed a possible interaction extension:

Sᴰ_total = ℏθᴰ + Sᴰ_int.

R13 now sharpens the requirement. Sᴰ_int must vary across physically distinct allowed outcomes and must generate or weight the transfer variable t or its equivalent. A generic scalar form:

Sᴰ_int = ℏ F(invariants)

is dimensionally easy to write because PMM already supplies dimensionless combinations, but symmetry and dimensions alone do not determine the function F.

Choosing F by convenience would therefore insert the interaction law rather than derive it. The historical reserved 𝓛_int sector has the same status.

**R13f RESULT:** **NO UNIQUE MINIMAL INTERACTION ACTION IS FORCED BY THE PRESENT CORE.**

## 6D.7 Consequence for event chains and Tμν

Once an outcome is supplied, R11/R12 accounting remains consistent:

Pᵢ(n+1) = Pᵢ(n) + ΔPᵢ|α.

But without C₂ outcome dynamics, the future state is a family or distribution rather than one native PMM prediction. Therefore:

current measured/supplied lineage states
→ kinetic T<sub>μν</sub> reconstruction remains available

current lineage states + native C₂ law
→ predictive future T<sub>μν</sub> evolution remains OPEN.

This is an incompleteness of dynamics, not a double-counting or conservation inconsistency.

## 6D.8 Gate results after R13

Gate 1 — causal lineage kinematics:
**CONDITIONAL PASS under R11a.**

Gate 2 — active source state/accounting:
**ACCOUNTING PASS / PREDICTIVE TRANSFER OPEN.**

Gate 3 — relativistic source reconstruction:
**KINEMATIC/COARSE-GRAINING CANDIDATE PASS FOR SUPPLIED STATES / DYNAMICAL PREDICTION OPEN.**

Gate 4 — native spatial GR response:
**PROMISING CONDITIONAL PASS under the separate R11e null-calibration route.**

Gate 5 — new discriminating prediction:
**NOT PASSED.** The current interaction sector cannot yet generate a quantitative channel distribution or cross section.

## 6D.9 R13 overall result

R13 reaches the present dynamics wall.

The frozen c³ core determines or constrains:

- which pair contact can actualize through C₁;
- the native D event geometry and closure structure;
- causal/mass-shell admissibility at recovery level;
- local four-momentum conservation;
- persistent C₃/A/Φ recording;
- current-state accounting once signed transfers are known.

It does **not** determine which conservation-admissible outgoing channel occurs or how those channels are probabilistically weighted.

Therefore:

**R13 OVERALL: FAIL AS A NATIVE INTERACTION DERIVATION / SUCCESSFUL IDENTIFICATION OF A SINGLE MISSING DYNAMICAL LAW**

If PMM is intended only as an event/geometry/gravity framework, the interaction law may remain an external sector. If PMM is intended as a predictive fundamental interaction theory, a new native C₂ dynamical postulate or a deeper derivation of the C₂ kernel is required.

No modification of P0, the c³ A grade, P1–P7, or the current B→D→A architecture is justified by this failure.

---


# 6E. R14 — Legacy Dynamics Compatibility Audit

**Question:** Do older PMM dynamics already contain a compatible precursor of the missing current event-progression and C₂ interaction laws, or would importing them require restoring retired assumptions?

**Current status:** **PARTIAL LEGACY RECOVERY / DYNAMICAL SKELETON SURVIVES / ABSOLUTE EVENT-RATE AND GENERAL INTERACTION LAW OPEN**

R14 does not modify Core 3.7.3. It treats older PMM equations as historical candidates and retypes them only where their mathematical and physical roles remain compatible with the current event/lineage architecture.

## 6E.1 Legacy inventory

The older PMM line contains five dynamical structures relevant to the present gap:

1. a generic monotonic phase-progress parameter `u` ordering B → D → A;
2. a common reciprocal contact-evolution parameter `λ_@` for one two-body interaction;
3. a contact-rate map `ζᵢ = dλ_@/dτᴰ_i` connecting common contact progression to local proper time;
4. a local receiver-response equation of the form `d p⃗ᵢ/dτᴰ_i = ζᵢ C_R(Eᴰ_i/c²)B⃗ᵢ←ⱼ` in the older gravity sector;
5. the pair momentum ledger `q₁ + q₂ + p_carrier = 0`, together with a D-field action whose interaction sector `𝓛_int[Φ,δ]` was reserved but never physically specified.

The present core already absorbed the old generic `u` notation: native D progression is now `θᴰ`, with `q = θᴰ/π`. Therefore `u` is not an independent surviving dynamical variable.

## 6E.2 Contact parameter versus current angular progress

Older PMM defined `λ_@` as a common monotonic label of the same interaction history from both participant vantages and explicitly kept it separate from local proper time until a rate map was supplied.

Current PMM instead has one native D progress coordinate:

`0 ≤ θᴰ ≤ π`.

Any monotonic identification:

`λ_@ = f(θᴰ)`

is mathematically allowed as a reparameterization. It does not by itself add physical dynamics.

If one chooses the dimensionless contact gauge:

`λ_@ = θᴰ`,

then the old rate variable becomes:

`ζᵢ → dθᴰ/dτᴰ_i ≡ Ωᴰ_i`.

If `λ_@` is instead retained with time units, then:

`Ωᴰ_i = (dθᴰ/dλ_@)(dλ_@/dτᴰ_i)`.

Older PMM did not derive both factors. In fact, the historical text explicitly left the contact-rate-to-proper-time map as a deeper kinetic target.

**R14a RESULT:** **STRUCTURAL COMPATIBILITY PASS / NO ABSOLUTE EVENT-RATE DERIVATION.**

The old `λ_@` machinery identifies the correct missing dynamical slot, but identifying `λ_@` with `θᴰ` merely renames the current unknown `dθᴰ/dτᴰ`.

## 6E.3 The normalized rate already survives in current κ

Current PMM defines the lineage clock response from a shared D angular increment:

`κᵢ = [Δθᴰ/Δt_i] / [Δθᴰ/Δt₀]`.

In an infinitesimal rate form, define:

`Ωᴰ_i ≡ dθᴰ/dt_i`,

`Ωᴰ₀ ≡ dθᴰ/dt₀`.

Then:

`κᵢ = Ωᴰ_i/Ωᴰ₀`,

so:

`Ωᴰ_i = κᵢ Ωᴰ₀`.

This is a cleaner current descendant of the legacy contact-rate idea. PMM already knows how a relational clock state changes an angular rate **relative to a neutral/reference rate**.

What remains missing is the absolute and interaction-conditioned baseline:

`Ωᴰ₀ = ?`

and, for a nonfree realized interaction, whether the physical event-progression rate is identical to the carrier/phase rate or has an additional C₂ dependence.

R10 supplied the recovery-level neutral interval candidate:

`Δt₀ = ℏΔθᴰ/Eᴰ`,

which would imply:

`Ωᴰ₀ = Eᴰ/ℏ`.

This relation is exact in the current null phase-time sector. It is **not promoted for generic massive/interacting laboratory event progression**. The Predictions audit already shows that a massive monitored transition can have an event-flight timescale very different from the underlying carrier/transition frequency. Therefore PMM must preserve the distinction:

`carrier / phase rate` ≠ automatically `interaction-conditioned event-progression rate`.

**R14b RESULT:** **NORMALIZED EVENT-RATE STRUCTURE SURVIVES / ABSOLUTE MASSIVE-INTERACTION RATE OPEN.**

## 6E.4 Legacy receiver-response law

Older PMM used a gravity-sector response equation of the schematic form:

`d p⃗ᵢ/dτᴰ_i = ζᵢ C_R(Eᴰ_i/c²)B⃗ᵢ←ⱼ`.

For an on-shell massive receiver in its instantaneous local rest frame, the old construction reduced to a universal acceleration law once the contact-rate normalization was fixed.

A narrow current retyping is possible at recovery level. Current PMM already defines the local gravity readout:

`g⃗ = c²∇φ`.

Therefore a candidate local gravitational response has the form:

`d p⃗ᵢ/dτᴰ_i = (Eᵢ/c²) g⃗ᵢ`

in the instantaneous local rest-frame recovery representation. With `Eᵢ = mᵢc²`, this gives:

`d p⃗ᵢ/dτᴰ_i = mᵢ g⃗ᵢ`,

and hence the usual mass-independent local acceleration form.

However, the historical derivation cannot be imported unchanged. It relied on older source-bond variables and pre-SR exchange tensors in which c-grade/participant roles were organized differently from the current rule that c¹/c² label internal D-vantage slots rather than permanent participant identities. The current δ/Φ gravity architecture is also different.

The receiver-response equation therefore remains a **legacy-motivated recovery candidate**, not a recovered current-core theorem.

It also does not solve R13. A gravity-specific force response does not determine a general microscopic scattering or emission kernel.

**R14c RESULT:** **GRAVITATIONAL RESPONSE CANDIDATE SURVIVES IN RETYPED FORM / GENERAL C₂ DYNAMICS NOT SUPPLIED.**

## 6E.5 Momentum ledger

The older law:

`q₁ + q₂ + p_carrier = 0`

is the cleanest legacy dynamical structure to survive.

R11/R12 have already retyped it into lineage four-momentum continuity:

`Pᵢ⁻ + Pⱼ⁻ + ΣP_in,carrier = Pᵢ⁺ + Pⱼ⁺ + ΣP_out,carrier`.

For a closed two-lineage event:

`ΔPᵢ|α + ΔPⱼ|α = 0`.

This modern form preserves the physical conservation content while removing the old ambiguity between event vantages and participant identities.

**R14d RESULT:** **PASS — LEGACY MOMENTUM ACCOUNTING SUCCESSFULLY SURVIVES AS CURRENT LINEAGE FOUR-MOMENTUM CONTINUITY.**

R12/R13 still apply: conservation constrains the transfer but does not select its magnitude/direction or probability distribution.

## 6E.6 Legacy variational dynamics

Older PMM also introduced a D-field action:

`𝒜ᴰ_field = ∫ d⁴x √(−gᴰ) 𝓛ᴰ`

and explicitly reserved an interaction sector:

`𝓛_int[Φ,δ]`.

This is important historically because it shows that PMM already recognized that geometry plus conservation would not be enough; an interaction generator was expected.

But the legacy interaction term was never physically specified. In addition, the surrounding older metric/depth and Φ dynamics do not map one-for-one onto Core 3.7.3.

Therefore the variational **method** remains available, while the old field action cannot be imported as a completed current interaction theory.

A future current-compatible candidate could still take the form:

`Sᴰ_total = Sᴰ_phase + Sᴰ_int`,

with:

`Sᴰ_phase = ℏθᴰ`,

but `Sᴰ_int` remains OPEN and must be independently motivated and falsifiable.

**R14e RESULT:** **VARIATIONAL FRAMEWORK REUSABLE / LEGACY INTERACTION LAW ABSENT.**

## 6E.7 Compatibility table

| Legacy object | Current disposition | Result |
|---|---|---|
| generic phase progress `u` | absorbed by native `θᴰ` / `q` progression | **SURVIVES AS NOTATIONAL PRECURSOR ONLY** |
| common contact parameter `λ_@` | compatible as a reparameterization of one realized D history | **STRUCTURAL PASS** |
| `ζ = dλ_@/dτᴰ` | current analogue is the event angular-rate map; normalized rate ratio already appears in `κ` | **PARTIAL SURVIVAL** |
| receiver-response law | can be retyped narrowly as a gravity-sector response candidate | **CONDITIONAL / RECOVERY ONLY** |
| pair momentum ledger | retyped as lineage four-momentum continuity | **PASS** |
| legacy `𝓛_int[Φ,δ]` | interaction slot existed but was unspecified | **NO COMPLETED LAW TO RECOVER** |
| old participant/c-grade exchange tensors | conflict with current internal D-slot versus lineage separation if imported literally | **DO NOT IMPORT AS-IS** |

## 6E.8 R14 overall result

R14 changes the interpretation of the present dynamics gap.

PMM is **not inventing dynamics from zero**. Older versions already contained:

- a common interaction-progress parameter;
- an explicit rate-map problem;
- a local force/response equation in the gravity sector;
- pairwise momentum conservation;
- a variational framework with a reserved interaction sector.

The modern 3.7.3 line kept the strongest geometric and conservation pieces but removed or retyped much of this dynamical scaffolding.

The important modern synthesis is:

`θᴰ` = native event progress coordinate

`κ = Ωᴰ/Ωᴰ₀` = normalized lineage/event clock-rate response

`ΔP` = signed lineage state update constrained by conservation

while the two genuinely missing laws are:

1. **Absolute / Interaction-Conditioned Event Progression:** what fixes `Ωᴰ₀` and, for interacting massive events, `dθᴰ/dτ` or `dθᴰ/dt`?
2. **C₂ Outcome Dynamics:** what determines or weights the conservation-admissible `ΔP` channel?

The legacy `λ_@`/`ζ` machinery is therefore best treated as a historical precursor to the first problem, not as its solution.

**R14 OVERALL: PARTIAL LEGACY RECOVERY / DYNAMICAL SKELETON SURVIVES / TWO RATE-AND-OUTCOME LAWS REMAIN OPEN**

No modification of P0, P1–P7, the c³ A grade, or the B→D→A architecture is justified by R14.

The next focused test should be **R16 — Absolute Event-Rate Audit**: determine whether current PMM can derive a non-arbitrary `Ωᴰ₀` and an interaction-conditioned progression law from existing quantities without identifying massive event progression with carrier phase by fiat.

---

# 6F. R15 — Temporal State-Space / Static Gravity Audit

R15 tests the new Core 3.7.3 interpretation of the existing FTU time tuple:

Fₜᵤᵀ = (Tᴮ,Tᴰ,Tᴬ)

as the three-coordinate temporal state space of a complete FTU. It then asks how far that temporal geometry can carry the existing PMM gravity chain without importing the Einstein field equations into the foundation.

## 6F.1 R15a — Temporal state-space rank

Write:

β = Δθᴮ

and use the existing one-probability B/A span relation:

Pₑ@ = cos²β

so:

Δθᴬ = −lnPₑ@ = −2ln(cosβ) ≡ f(β).

The physical FTU time tuple is:

Tᴮ = [ℏ/(mₚc²)]β

Tᴰ = d/c

Tᴬ = [ℏ/Eᴰ]f(β).

Using local coordinates (β,d,Eᴰ), the Jacobian determinant is:

**det J = −ℏ² f(β) / [mₚc³(Eᴰ)²].**

For:

0 < β < π/2

and:

Eᴰ > 0

this is nonzero. Therefore the physical temporal map is generically rank three across the nondegenerate FTU family.

At Pₑ@ = 1, β = 0 and f(β) = 0, so the map reaches a degenerate boundary. The rank result therefore supports a three-coordinate temporal state space without implying a globally Euclidean metric or three freely independent angular spans.

**R15a RESULT: ALGEBRAIC PASS — GENERIC PHYSICAL TEMPORAL RANK = 3 / ORTHOGONAL METRIC OPEN.**

## 6F.2 R15b — Stronger d = L recovery check

Core 3.7.3 gives Sᴰ/Eᴰ = L/c. If Tᴰ = d/c denotes this same action time, d = L follows conditionally. The massive proper-time identification further requires the timelike phase/action bridge. On that branch:

d = L = (ℏc/Eᴰ)θᴰ.

Then:

Tᴰ = ℏθᴰ/Eᴰ.

Using coordinates (β,θᴰ,Eᴰ):

**det J = −ℏ³ f(β) / [mₚc²(Eᴰ)³].**

The determinant is nonzero in the nondegenerate active D interior, where θᴰ is variable. Completed closure fixes θᴰ = π, leaving inputs (β,Eᴰ) and rank at most two. A completed-event sample therefore cannot be assigned the active-interior rank-three requirement.

**R15b RESULT: ALGEBRAIC PASS IN ACTIVE D / d = L CONDITIONAL ON THE D ACTION-TIME IDENTIFICATION / COMPLETED CLOSURE RANK ≤ 2.**

## 6F.3 R15c — Weak-field clock recovery and the second-order fork

PMM defines:

κ = e⁻ᵠ

and:

g = c²∇φ.

For a static isolated spherical source, the present flat continuum Clock Flux equation gives:

φ(r) = G<sub>N</sub>M/(rc²) ≡ x

once the Newtonian normalization λ<sub>G</sub> = 4πG<sub>N</sub>/c² is imposed.

Therefore:

κ<sub>flat</sub> = e⁻ˣ

with expansion:

κ<sub>flat</sub> = 1 − x + ½x² − ⅙x³ + ...

The exact Schwarzschild stationary-clock factor relative to infinity is:

κ<sub>GR</sub> = √(1 − 2x)

with expansion:

κ<sub>GR</sub> = 1 − x − ½x² − ½x³ + ...

The current flat equation therefore passes at first order and separates beginning at second order:

κ<sub>flat</sub> − κ<sub>GR</sub> = x² + O(x³).

This difference is a diagnostic of the strong-field completion, not yet an independent prediction.

**R15c RESULT: WEAK-FIELD PASS / FLAT STRONG-FIELD EXTENSION FAILS EXACT SCHWARZSCHILD AT O(x²).**

## 6F.4 R15d — Candidate covariant Clock Flux

Test the recovery candidate:

□φ = 0

in a source-free region, with:

φ = −lnκ.

For a static metric:

ds² = −κ²c²dt² + hᵢⱼdxⁱdxʲ

the scalar equation is:

□φ = [1/(κ√h)] ∂ᵢ[κ√h hⁱʲ∂ⱼφ].

Since:

κ∇ₕφ = −∇ₕκ

we obtain:

**□φ = 0 ⇔ Δₕκ = 0.**

This is a recovery candidate for the covariant continuum limit. Core 3.7.3 does not derive it from the discrete δ-network law.

**R15d RESULT: ALGEBRAIC PASS / COVARIANT CONTINUUM BRIDGE CANDIDATE.**

## 6F.5 R15e — Clock–Distance Reciprocity and exact Schwarzschild

The current clock response is a normalized angular rate with respect to comparison time t. For identical massive clocks it is conditionally a normalized dτ/dt. Intrinsic Tᴰ=d/c therefore does not imply κ=d₀/d; the former intrinsic-time derivation is withdrawn.

For static spherical recovery, use areal radius r and adopt the independent radial spatial bridge:

**dℓᵣ = dr/κ**

and:

hᵣᵣ = κ⁻².

The spatial metric is therefore:

dℓ² = κ⁻²dr² + r²dΩ².

The candidate covariant clock equation Δₕκ = 0 becomes:

(d/dr)[r²κ(dκ/dr)] = 0.

With asymptotic boundary condition κ → 1 and Newtonian normalization m = G<sub>N</sub>M/c²:

κ² = 1 − 2m/r.

Therefore:

**κ = √(1 − 2G<sub>N</sub>M/(rc²))**

and the recovered static spherical metric is:

**ds² = −(1 − 2G<sub>N</sub>M/(rc²))c²dt² + (1 − 2G<sub>N</sub>M/(rc²))⁻¹dr² + r²dΩ².**

This is the Schwarzschild exterior metric.

The same metric gives radial null propagation:

dr/dt = cκ²

and the standard stationary-observer proper-acceleration magnitude:

|a| = G<sub>N</sub>M/(r²κ).

**R15e RESULT: EXACT STATIC SPHERICAL GR RECOVERY / CONDITIONAL on Clock–Distance Reciprocity + covariant Clock Flux + areal-radius identification.**

## 6F.6 R15f — General static-vacuum clock–curvature candidate

The general static-vacuum GR target is:

Δₕκ = 0

and:

Rᵢⱼ = κ⁻¹DᵢDⱼκ.

Clock Flux alone supplies only the scalar clock equation under the candidate covariant completion. Test the recovery functional:

**𝓘ₛₜₐₜ = Cᴳ ∫ κ R[h] √h d³x.**

Variation with respect to κ gives:

R = 0.

Variation with respect to hᵢⱼ gives:

κGᵢⱼ + hᵢⱼΔₕκ − DᵢDⱼκ = 0.

Using R = 0 and the trace gives:

Δₕκ = 0

and therefore:

**Rᵢⱼ = κ⁻¹DᵢDⱼκ.**

Thus the candidate functional reproduces the complete static-vacuum GR equations. A relational discretization has the Regge-like form:

𝓘δ ∝ ∑ₑ κ̄ₑ δₑΔₑ

where Δₑ is the δ-network deficit angle and κ̄ₑ is an edge clock factor.

Current PMM does not derive this functional from the single-FTU action or the persistent-record source. It remains a recovery candidate.

**R15f RESULT: EXACT GENERAL STATIC-VACUUM GR IF THE CLOCK–CURVATURE FUNCTIONAL IS ADOPTED / NATIVE DERIVATION OPEN.**


## 6F.7 R15g — Three-gap bridge audit

The Schwarzschild branch leaves three separate geometric questions that must not be collapsed into one recovery statement.

**Gap 1: d → δ.** For a realized FTU α with e@(α) = {i,j}, test the candidate event-edge bridge:

**dα ↔ δᵢⱼⁿ.**

This maps the D traversal length entering Tᴰ = d/c to the inter-lineage relational edge of the same realized pair event. It does not identify the internal single-FTU depth zᴰ directly with δᵢⱼ. No PMM-native derivation is currently supplied.

**Gap 2: directional geometry.** The spherical rule dℓᵣ = dr/κ stretches one adapted radial coordinate. It cannot be assumed to be a universal law with both transverse directions unchanged.

**Gap 3: areal radius.** In spherical symmetry define r from the transverse area A by A = 4πr². This makes the Schwarzschild coordinate choice geometric inside that symmetry class. For a non-spherical source there is no single areal-radius scalar carrying the full transverse geometry; the full two-metric is required.

**R15g RESULT: THREE GAPS SEPARATED / d↔δ, DIRECTIONAL RESPONSE, AND TRANSVERSE GEOMETRY REMAIN DISTINCT.**

## 6F.8 R15h — Non-spherical test of the longitudinal-only metric

Test the universal ansatz:

hᵢⱼ = h̄ᵢⱼ + (κ⁻² − 1)nᵢnⱼ,

with flat h̄ᵢⱼ, n ∥ ∇κ, and unchanged transverse geometry.

Use a weak source-free clock field:

κ = 1 + u,

u = εxy,

∇²u = 0.

At first order, static vacuum GR requires:

Rᵢⱼ = ∂ᵢ∂ⱼu.

Therefore:

Rₓᵧ = ε.

The longitudinal-only ansatz instead gives:

**Rₓᵧ = 0.**

At x = y it also gives Rₓₓ = −ε while the target has ∂ₓ²u = 0.

The ansatz therefore recovers the spherical Schwarzschild coordinate form but fails as a universal non-spherical static law.

**R15h RESULT: FAILED BRIDGE — UNIVERSAL LONGITUDINAL-ONLY / UNCHANGED-TRANSVERSE METRIC RETIRED.**

## 6F.9 R15i — Native D common-scale weak-field test

The existing D geometry has:

xᴰ = Leᵃ,

yᴰ = Le⁻ᵃ,

zᴰ = L.

Hence a change of L changes zᴰ and the mean transverse scale together. Test the recovery candidate:

L/L₀ = κ⁻¹ = eᵠ,

with a = 0 and fixed local principal orientation on a flat reference chart. Then:

hᵢⱼ = e²ᵠ h̄ᵢⱼ,

κ = e⁻ᵠ.

For source-free flat-reference Δφ = 0, the exact tensor residual of this restricted ansatz is:

Rᵢⱼ − κ⁻¹DᵢDⱼκ
= −2(∂ᵢφ)(∂ⱼφ) − h̄ᵢⱼΔφ,

so:

**Rᵢⱼ − κ⁻¹DᵢDⱼκ = −2(∂ᵢφ)(∂ⱼφ).**

The residual is quadratic. Therefore the common-scale branch satisfies the general static-vacuum tensor equation at first order for arbitrary weak harmonic φ, while nonlinear static recovery requires extra transverse/shear response.

**R15i RESULT: GENERAL STATIC WEAK-FIELD PASS TO FIRST ORDER / NONLINEAR COMMON-SCALE-ONLY BRANCH FAILS AT QUADRATIC ORDER.**

## 6F.10 R15j — Transverse D geometry and the nonlinear target

A local positive two-dimensional transverse metric can be parameterized as:

q = L² R(ψ)ᵀ diag(e²ᵃ,e⁻²ᵃ) R(ψ),

with:

det q = L⁴.

This gives a useful PMM mapping:

L → transverse area/common scale,<br>
a → transverse anisotropy/shear amplitude,<br>
ψ → principal-axis orientation.

L and a already exist in the D geometry. The minimal A record can reconstruct the completed L and a values from ωᴬ and a_cl, but it does not explicitly carry a rotation axis or a cross-FTU orientation variable. The dynamics of a and ψ are also absent because the native D interaction-energy / C₂ outcome law remains open.

This parameterization shows representation capacity, not a GR derivation. The decisive test is to derive the evolution of L, a, and any required orientation from PMM first principles, then compare the resulting q and hᵢⱼ with the static-vacuum equations. Agreement gives native recovery; disagreement gives a PMM discriminator; inability to derive the dynamics leaves the recovery conditional.

**R15j RESULT: TRANSVERSE REPRESENTATION CAPACITY PRESENT / NONLINEAR SHEAR DYNAMICS OPEN.**

## 6F.11 Prediction consequence

The flat strong-field expression:

κ = e⁻ᴳᴹ⁄ʳᶜ²

would have produced a second-order departure from Schwarzschild. R15 shows that the candidate covariant completion removes that departure and recovers exact Schwarzschild in the static spherical sector.

Therefore the e⁻ˣ second-order term is **not retained as an independent PMM prediction**.

The surviving prediction opportunities lie in sectors where PMM has not yet collapsed onto the GR continuum limit:

- finite/discrete δ-network corrections;
- non-spherical relational geometry;
- time-dependent multi-FTU evolution;
- native active-source and lineage-state dynamics.

None of these yet has a parameter-free quantitative departure in the current source theory.

## 6F.12 R15 overall result

R15 now separates what is established from what was bridge-driven. The existing Fₜᵤᵀ readout has rank three in the independent-d parameterization and in active D on the conditional d=L branch; completed closure on that branch has rank at most two. The covariant Clock Flux plus areal-radius Clock–Distance Reciprocity branch gives an exact conditional Schwarzschild recovery. That spherical success does not establish a universal radial-only law: the longitudinal-only / unchanged-transverse metric fails an explicit non-spherical harmonic test and is retired.

The native D common-scale geometry supplies a stronger route: under the candidate L/L₀ = κ⁻¹ bridge it satisfies the general static-vacuum tensor equation at first order, while the surviving quadratic residual isolates the missing nonlinear response in transverse/shear dynamics. L and a can carry transverse scale and anisotropy; orientation transport and their dynamics remain open. The clock-weighted curvature functional remains a compatibility/recovery candidate rather than a native derivation.

**R15 OVERALL: NATIVE TEMPORAL RANK-THREE ALGEBRAIC PASS / EXACT SCHWARZSCHILD CONDITIONAL SPHERICAL PASS / UNIVERSAL LONGITUDINAL-ONLY BRIDGE FAIL / GENERAL STATIC FIRST-ORDER PASS UNDER COMMON-SCALE CANDIDATE / NONLINEAR NATIVE GEOMETRY OPEN.**

---

## 6G. 3.7.3 Endpoint, Time and Supporting-Test Reconciliation

**SYNCHRONIZATION / CONDITIONAL RECOVERY — NO GRADE PROMOTION**

The source baseline is PMM 3.7.3 Core 3.7.3. One elementary pair interaction remains one FTU with event identity α. C₃ supplies two endpoint records Rᴬ_i|α and Rᴬ_j|α; both refer to one event-level Eᴬ(α). Fₜᵤᴿ ≡ Recᴬ(Fₜᵤ) supplies the event record vantage A[xy ; (B,D,A) ; ψᴮ(x,y,z)]. This notation adds neither a participant nor a third endpoint record. The richer record reference does not yet derive generic momentum transfer, stress, or cross-FTU carrier orientation.

### Endpoint/source accounting

The Endpoint Record Pressure Test establishes the required accounting distinction: event multiplicity 1, endpoint-record multiplicity 2, event-source multiplicity 1. Both lineage histories may store α; source extraction must deduplicate those references and distinguish persistent history from current carried source. R4 and the R11/R12 source-state proposals remain conditional; two endpoint records do not supply two masses or derive the Einstein coefficient.

For a closed pair, the proposed source update must satisfy ΔE_i|α + ΔE_j|α = 0, with μ_i updated by ΔE_i|α/c². Conservation constrains an update but does not choose the transfer. The native D/C₂ outcome law and active-source extraction remain open.

### Intrinsic time and comparison time

The Massive Proper-Time Audit supplies Sᴰ/Eᴰ = L/c from the existing scale and angular-action readouts. Identifying Tᴰ=d/c with that action time gives d=L conditionally. Identifying it further with massive proper time requires the timelike phase/action bridge; null proper time stays zero.

The gravity clock uses the distinct comparison time t:

κ = (dθᴰ/dt)/(dθᴰ/dt)₀.

For identical fixed-energy massive clocks on the timelike branch, κ = (dτ/dt)/(dτ/dt)₀. For a fixed angular increment, comparison intervals satisfy κ = Δt₀/Δt. This is not a ratio of intrinsic Tᴰ intervals. R10's neutral phase-interval identification is an additional reference-clock bridge, not a definition of an arbitrary comparison clock. Its transport, velocity and source consequences remain conditional on that bridge and the event-edge embedding.

### P3 and the four-mode D geometry

P3 is terminal vantage lock: r=b=Σ=0 at −@. The earlier throughout-D equality of planar aspect ratios is retired. The fourth mode b=¼ln[(x₁ᴰ/y₁ᴰ)/(x₂ᴰ/y₂ᴰ)] allows disagreement during D. The common readouts xᴰ=Leᵃ, yᴰ=Le⁻ᵃ and zᴰ=L survive because r and b cancel from them. The harmonic law for b and its coupling to a remain candidate/open. Existing L/r scalar algebra therefore survives, while any claim to a complete interaction generator or generic transverse dynamics must include the unresolved b sector.

### Scale-rate result

The Scale Dynamics Test is retained with its endpoint intervals retyped as comparison intervals Δt. For the same constant-energy event increment ΔL=ℓ_EΔθᴰ, define v_L=ΔL/Δt and its neutral reference similarly. Then κ=v_L/v_L₀. This is a derived normalization identity; it does not derive L/L₀=κ⁻¹ or a δ-network evolution law. Distance δ, internal depth zᴰ and traversal readout d remain distinct.

### Static spherical recovery and Einstein normalization

The Schwarzschild Pressure Test rechecks the changed κ typing. The lapse identification is compatible with rate-based κ. Exact Schwarzschild still requires the independent radial-metric candidate h_rr=κ⁻², the covariant clock candidate Δₕκ=0, areal radius and Newtonian coupling normalization. Flat-reference Clock Flux alone gives the weak-field correspondence and not the exact strong-field solution. The old inference κ=d₀/d from intrinsic Tᴰ=d/c is withdrawn.

The weak-field metric coefficient 2 follows under the lapse bridge from g₀₀=−κ². The corresponding 8πG_N/c⁴ comparison remains recovery content; endpoint multiplicity is not its derivation and no c⁴ FTU grade is introduced.

### Shear and accumulation tests

The supporting-test index separates frozen test reports, later corrections and unadopted proposals. The Blocker2, pair-shear, 3D accumulation and Shear Extension notes constrain possible nonlinear laws in their stated charts, seeds and perturbative domains. Their reported numerical/symbolic checks are not re-run by this synchronization. The later Shear Extension status supersedes earlier withdrawn local/Poisson constructions; its reported λ=−4 and c₀=2/3 are comparison requirements in tested branches, not PMM-native coefficients. The proposed 4/6 counting explanation supplies no mechanism and is not promoted. Native interaction energy, b/a/orientation dynamics and general geometric transport remain open.

The Triangle sketch's three-equal-vantage construction is withdrawn. The Topology and cOrder Restoration audits propose two lineage FTUs and different c-grade assignments; 3.7.3 has not adopted those proposals. They remain separate research alternatives and are not inputs to this recovery baseline.

### Mₒₚ spatial-gravity pressure tests — 3.7.3 supplement

The Mₒₚ Spatial-Gravity Pressure Tests v1.1 add a scoped assessment against Core 3.7.3; the preceding 3.7.3 calculations remain frozen. In a smooth local Euclidean embedding with shared comparison time t and gravity supplying the relative acceleration, vector separation ξ obeys ξ̈ = gⱼ − gᵢ ≈ c²(∇∇φ)·ξ. Scalar edge acceleration instead includes the transverse term aᴿ = n̂·ξ̈ + |u⊥|²/δ. Scalar edge rate, embedded lineage velocity, and internal D-scale rate are distinct readouts.

For the stated weak-field point-source potential φ = G_NM/(c²r), differentiating g gives ξ̈ = (G_NM/r³)(3r̂r̂ − I)ξ and the radial/transverse tidal ratio +2 : −1 : −1. This demonstrates weak-field tidal correspondence under the source normalization and local receiver-response identification. The pattern also occurs in Newtonian gravity and does not alone determine the GR spatial metric. It strengthens the relational spatial-deformation account without completing a native metric derivation.

The γ = 1 linear spatial response remains the existing R15i conditional result under L/L₀ = κ⁻¹, a = 0 and fixed orientation; the new note does not independently derive that bridge. The nonlinear residual remains −2(∂ᵢφ)(∂ⱼφ) in the stated source-free branch. Native scale response, a/b dynamics where relevant, orientation transport, event-edge identification and covariant coarse-graining remain open. Mₒₚ does not determine the C₂ outcome law or absolute comparison-time event rate.

**Mₒₚ RESULT: WEAK-FIELD TIDAL CORRESPONDENCE DEMONSTRATED UNDER STATED ASSUMPTIONS / LINEAR SPATIAL-METRIC RECOVERY CONDITIONAL / NONLINEAR NATIVE GEOMETRY OPEN / NO EMPIRICAL-GRADE PROMOTION.**

---

# 7. Recovery Ledger

| Test | Target | Current result | Main dependency | Next action |
|---|---|---|---|---|
| R0 | Local SR / Lorentz structure + covariant closure | **A algebraic / B physical-recovery structure; COMMON-BOOST ALGEBRAIC PASS / PHYSICAL BRIDGE CONDITIONAL** | physical reciprocal-channel instantiation; full 3+1 extension | Test physical channel instantiation and extend to full 3+1 covariance |
| R1 | Newtonian gravity | **CONDITIONAL PASS / PARTIAL** | active source extraction 𝒮[Φ]; Qᴬ = M recovery candidate; discrete→continuum bridge | Derive active source extraction and coarse-graining |
| R2 | Weak-field GR | **CONDITIONAL PASS / NATIVE SPATIAL GAP** | κ↔lapse plus recovery-level γ = 1 spatial bridge | Derive γ = 1 from δ-network geometry |
| R3 | Null / light sector | **NULL KINEMATIC CORRESPONDENCE / SEPARATE POSITIVE-PAIR 1+1 ALGEBRA; PHYSICAL BRIDGE CONDITIONAL; GR OPTICS CONDITIONAL** | full 3+1 covariance; R2 spatial metric for curved-space optics | Extend covariance and rerun curved-space light tests after native spatial bridge |
| R4 | Source stability / relativistic source | **CANDIDATE / CONDITIONAL STATIONARY + NEWTONIAN TOY SOURCE PASS** | active source extraction; native stress completion | Derive active source extraction and relativistic source |
| R10 | A-side relativistic source reconstruction | **CONDITIONAL PASS / PARTIAL RELATIVISTIC SOURCE RECONSTRUCTION** | lineage interval/frame bridge; source extraction; interacting stress | Test synchronization, causal network evolution, and full covariant T<sub>μν</sub> coarse-graining |
| R11 | Multi-FTU causal/source gate audit | **CONDITIONAL PASS / ONE DYNAMICAL LAW OPEN** | event→lineage four-momentum transfer; δ null-calibration bridge | Derive ΔP from D dynamics; test R11a/R11e on explicit relational cells; then coarse-grain T<sub>μν</sub> |
| R12 | Event-to-lineage transfer audit | **PARTIAL / CONSERVATION PASS / INTERACTION DYNAMICS OPEN** | native D interaction generator or C₂ outcome law | Derive or postulate the interaction law that selects ΔP; then rerun event chains and predictive T<sub>μν</sub> evolution |
| R13 | Native D interaction / C₂ outcome audit | **FAIL AS NATIVE DERIVATION / MISSING DYNAMICAL LAW IDENTIFIED** | physical C₂ outcome map/kernel or independently derived Sᴰ_int | Decide theory scope; if fundamental interaction prediction is required, propose one minimal C₂ law and subject it to scattering/emission falsification tests |
| R14 | Legacy dynamics compatibility audit | **PARTIAL LEGACY RECOVERY / DYNAMICAL SKELETON SURVIVES** | absolute/interacting event-rate law; current-compatible response dynamics | Run R16 absolute event-rate audit; retain momentum continuity and gravity response only at their current qualified status |
| R15 | Temporal rank + static geometry | **BRANCH-SCOPED TEMPORAL ALGEBRA (ACTIVE RANK 3; CONDITIONAL COMPLETED RANK ≤ 2) / EXACT SCHWARZSCHILD CONDITIONAL SPHERICAL PASS / LONGITUDINAL-ONLY BRIDGE FAIL / GENERAL STATIC LINEAR PASS UNDER COMMON-SCALE CANDIDATE** | d↔δ event-edge bridge; rate-based lapse and independent radial-metric bridge; covariant δ limit; nonlinear L/a/b/orientation dynamics | Freeze the recovery result until one of these upstream dependencies changes; derive native transverse/shear dynamics before another GR rerun |

The ledger records recovery status only. It does not change the status of equations in PMM 3.7.3.

---

# 8. Immediate Research Sequence

## Recovery freeze after v1.15

R15 is frozen at the status recorded above. Do not rerun Schwarzschild, weak-field redshift, or the same static-vacuum comparisons unless at least one upstream dependency changes: the event-edge bridge d↔δ, the active-source/current-lineage law, the native D interaction/shear dynamics, or the discrete→covariant continuum map.

The next work on this branch must proceed PMM-first: derive a native law, calculate its consequence, and only then compare with GR. This prevents a new comparison bridge from being mistaken for a new recovery.


The recovery program proceeds from the strongest existing PMM chain outward.

## R1 continuation

Derive or reject the completed-record source:

Qᴬ = ∑ completed Eᴬ/c²

Then derive the discrete δ-network coarse-graining limit that produces the continuum Clock Flux equation.

## R2 continuation

Test bridge R2-B1 beyond first order and derive the spatial metric sector from δ geometry.

The next useful checkpoint is a static spherical weak-field configuration, since R1 and R2 can then be tested against the same source and boundary conditions.

## R10 / R11 / R12 / R13 / R14 / R15 continuation

R11 localized the unconstrained-speed failure in R10 and supplied a conditional Lorentz-admissibility repair. R12 showed that local four-momentum conservation does not uniquely determine event-to-lineage transfer. R13 showed that the present native variables define the admissible outcome space but not the outcome selector. R14 then audited older PMM dynamics and found that the old contact parameter/rate machinery supplies a compatible historical skeleton but no derived absolute event rate. Current κ already carries the normalized angular-rate ratio, while the legacy momentum ledger has already survived as lineage four-momentum continuity.

R16 — Absolute Event-Rate Audit remains a separate dynamics test. It asks whether the neutral/reference event rate Ωᴰ₀ can be derived from current PMM without simply extending the null carrier identity `dθᴰ = ωdt` to generic massive interactions. It does not reopen R15. Any Event Progression Principle would require its own PMM-native justification and would trigger only the recoveries that depend on it.

The separate R13 scope decision remains: if PMM is intended as a predictive fundamental interaction theory, one C₂ outcome law is still required after the event-rate problem is isolated. Only after a physical C₂ law generates ΔPᵢ|α should the program rerun sequential multi-lineage event chains, replace the toy LRSP with current-state extraction 𝒮<sub>P</sub>[Φ], and test predictive evolution of the free-lineage T<sub>μν</sub>.

In parallel, continue the explicit R11a relational-cell test and derive or reject the R11e δ ↔ null-calibrated distance bridge. Only after the transfer dynamics and spatial bridge are independently closed should a higher-order metric discriminator be promoted into Predictions.

---

# 9. Candidate Future Recoveries

These are retained as recovery targets in v1.15 with their current synchronized statuses below. R10–R15 partially probe the source, spatial, and covariant-gravity problems but do not complete the full native relativistic-source or general non-spherical covariant recovery.

**R5 — Static spherical field / Schwarzschild correspondence**  
Status: SUBSUMED BY R15e — CONDITIONAL EXACT SPHERICAL PASS; native d↔δ/covariant derivation open

**R6 — Curved-space null optics / gravitational light behavior**  
Status: CONDITIONAL in the recovered Schwarzschild branch; general non-spherical/time-dependent derivation open

**R7 — Equivalence-principle correspondence**  
Status: OPEN

**R8 — Continuum curvature from the δ network**  
Status: OPEN

**R9 — Relativistic source / stress-energy correspondence**  
Status: OPEN

Each future recovery must use the firewall and status rules defined in this document.

---

# 10. Baseline Protection Rule

PMM 3.7.3, Core Revision 3.7.3 remains the frozen source theory for Recovery v1.15.

Recovery work may identify a required PMM revision. Such a revision belongs in a later PMM source-theory version and must then be tested by a new recovery baseline.

Recovery calculations therefore never rewrite the baseline retroactively.

---

# 11. Current Summary

**R0:** The PMM two-vantage scalar geometry has an exact local 1+1 light-cone / SO(1,1) form. With the reciprocal recovery identification ℰ₊ ↔ E + pc and ℰ₋ ↔ E − pc, it recovers E² − p²c² = m²c⁴ in the massive sector and r ↔ rapidity. The covariance construction in §2B gives common-boost balance invariance; physical closure covariance remains conditional on channel/reference and event-progress bridges. Physical channel instantiation and full 3+1 covariance remain open.

**R1:** The PMM clock-gradient field reproduces Newtonian Gauss-law normalization when Qᴬ = M is used and λ<sub>G</sub> is fixed to 4πG<sub>N</sub>/c². Core 3.7.3 closes the clock-response architecture by treating κ as the Clock Flux network solution once sᴬ is supplied. The remaining native gaps are active source extraction 𝒮[Φ] and continuum coarse-graining.

**R2:** Identifying κ with the normalized static lapse gives g₀₀ = −e<sup>−2φ</sup>, whose weak-field expansion matches the standard temporal GR relation when Φ<sub>N</sub> = −c²φ. The spatial metric recovery from the δ network remains open.

**R3:** Under the stated constant-frequency definitions, the null sector reproduces local propagation at c and zero proper-time accumulation. Separately, the positive reciprocal pair supplies timelike SO(1,1) algebra and common-boost balance invariance under the candidate reference bridge. Curved-space light deflection and Shapiro delay remain conditional on the unresolved R2 spatial metric and full 3+1 extension.

**R4:** The toy Latest-Record Source Projection passes the stationary and Newtonian sum tests only for independently supplied nonduplicated effective entries satisfying the stated rest-energy assignment. Core 3.7.3 now supplies lineage typing through ∼ᴸ; active source extraction from Φ and relativistic stress-energy completion remain open.

**R10:** The existing lineage clock definition admits a candidate neutral phase-interval bridge Δt₀ = ℏΔθᴰ/Eᴰ. It is exact in the stated null-sector phase-time relation and has the correct form for the massive/timelike sector under the existing R0 bridge. Together with δ-network embedding and lineage continuity, it supplies a conditional route to direction, displacement, velocity, free-dust source content, and isotropic null-source behavior. The null scale law plus Vᴰ = L³ yields p = u/3 under a stated isotropic deformation bridge. Interacting/composite stress, source extraction, synchronization, and full covariant T<sub>μν</sub> remain open. R10 does not alter the canonical c³ A grade; the standard G<sub>N</sub>/c⁴ coupling is retained only as recovery bookkeeping, not as an FTU-grade argument.

**R11:** The unconstrained δ-speed failure is localized and conditionally repaired by a lineage Lorentz embedding that rejects spacelike adjacent-lineage updates while preserving the native null c limit. The old contact momentum-exchange idea is retyped as lineage four-momentum continuity, separating persistent A/Φ transaction history from current carried lineage state and removing stationary-source double counting at the accounting level. Free massive/null lineage states then admit a kinetic T<sub>μν</sub> coarse-graining without a general material energy functional. A null-calibrated δ-distance bridge can conditionally select the γ = 1 weak-field spatial response without setting the exponent from Einstein comparison.

**R12:** Explicit elastic and carrier-emission tests show that four-momentum conservation constrains but does not uniquely select the signed event-to-lineage transfer ΔP. In the center-of-momentum elastic test, a continuous family of outgoing directions satisfies the same conservation and mass-shell constraints. The present D action Sᴰ = ℏθᴰ is a phase-action readout and gives the same πℏ closure value across that family, so it cannot by itself select the scattering outcome. Historical PMM versions reserved an interaction Lagrangian sector but did not specify the missing interaction dynamics. The remaining law-level blocker is therefore more precisely a **Native D Interaction Law / C₂ Outcome Law** that generates or weights ΔP while preserving the existing event/lineage separation and conservation structure.

**R13:** The complete current invariant inventory, explicit elastic family, and explicit null-carrier emission family confirm that the frozen core defines the allowed outcome space but not a physical outcome selector. θᴰ/Sᴰ, r, a, the half-angle carrier, δ, and Φ each fail as native selectors without adding a new bridge or law. A normalized C₂ transition kernel is the cleanest general mathematical placeholder because it includes a deterministic map as a limiting case, but its physical weighting is not derived. R13 therefore records a localized failure of interaction completeness rather than a contradiction of the c³ B→D→A architecture.

**R14:** Older PMM does contain genuine dynamical scaffolding. The generic phase parameter `u` is now absorbed by θᴰ/q. The common contact parameter `λ_@` survives as a possible reparameterization of one D history, and its rate map `ζ = dλ_@/dτᴰ` identifies the same absolute-rate problem now exposed by the missing interaction-conditioned event generator and comparison-clock synchronization. Current κ already supplies the normalized relation `κ = Ωᴰ/Ωᴰ₀`; the missing quantity is the absolute/interacting baseline rate. The older gravity receiver-response equation can be retyped only as a recovery-level candidate because its original bond/tensor derivation used retired participant/c-grade structures. The momentum ledger survives strongly as current lineage four-momentum continuity. The old variational framework remains methodologically useful, but its `𝓛_int` sector was never specified. R14 therefore recovers a dynamical skeleton, not a completed dynamics.

**R15:** The existing Fₜᵤᵀ = (Tᴮ,Tᴰ,Tᴬ) readout is rank three in the independent-d family and in active D on the conditional d=L branch, but completed closure on that branch has rank at most two; temporal-cube orthogonality remains open. Flat Clock Flux gives the correct first-order spherical clock slowing but its direct strong-field extension separates from Schwarzschild at O(x²). The candidate covariant clock equation plus areal-radius Clock–Distance Reciprocity gives an exact conditional Schwarzschild exterior. The universal longitudinal-only / unchanged-transverse metric then fails a non-spherical harmonic weak-field test and is retired. A different branch based on the native D common scale L, with L/L₀ = κ⁻¹ as a recovery bridge, satisfies general static vacuum at first order but leaves the quadratic residual −2∂ᵢφ∂ⱼφ. The native variables L and a can parameterize transverse scale and shear; cross-FTU orientation and their nonlinear dynamics remain open. General static GR is therefore not yet natively recovered, and no parameter-free nonlinear departure is yet promoted to Predictions.

The immediate recovery program is therefore: run R16 on the absolute/interacting event-progression rate before adding any new core postulate; keep the R13 C₂ outcome problem separate; in parallel continue the explicit R11a causal-cell and R11e null-calibration tests and complete the continuum/covariant coarse-graining needed by R2/R3/R9/R10/R11/R12/R13/R14.
