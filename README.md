# Clausecress 1.0 TEST
Native Android signed-literal clause puzzle. Android 8+ min26/target35. Package com.gg007.clausecress.

## Rules
Known 3-CNF satisfiability adaptation. Six switches A-F are always TRUE or FALSE. Each of sixteen clauses contains three signed letters: +A is true when A is TRUE; -A is true when A is FALSE. Every clause is an OR: at least one of its three literals must be true, and two or three true literals are also allowed. All sixteen clauses must pass together. Tap A-F switches, read live clause colors/counts, then CHECK CLAUSES. There is no minimum-true or exact-one rule. Twelve original formulas, one satisfying assignment each, with 2-4 true variables. Undo/reset, GG007 menu/site/privacy and saved palette/optional clause numbers. Tap title or Android Back for menu.

## Download and status
https://mega.co.nz/#!ZUERiQKJ!K78U5zEPZl-U56Rq1mi3Nur0YS83g9K-Jiyx58Mx1I0
APK 20974 bytes; SHA256 6f78b1dcd3f31d998f591d9117d43ecd73fa7b68963b97cbbdba8d1522423dc1. Original certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions, original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 1061111 produces twelve distinct planted sixteen-clause formulas with six variables and three distinct variables per clause. All 64 assignments per formula,768 total, compare independent falsifying-pattern masks with production signed-literal OR/conjunction checks; each has one solution and rejects all-false/all-true. Another 64000 random formula/assignment checks and 8 single-clause truth combinations pass.4608 toggle/undo transitions verify restoration. Invalid masks, tile bounds, clause shapes, zero literals and reset cases pass. All twelve actual drawing-adapter switch/CHECK clause tap-solves, empty/all-true rejection, solved locks, NEXT, undo/reset/levels/title-menu/privacy/saved palette-clause-numbers pass. Twenty drawing previews inspected, not phone screenshots. Phone runtime, performance, browser handoff QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 237 prior studio descriptions and 803 legacy one-line descriptions reviewed. Clause/3-SAT/Boolean/CNF/propositional scans found no matching signed-clause mechanic. Clausecress asks for one assignment satisfying a conjunction of sixteen signed three-literal alternatives. Chromaring colors linked nodes differently; Pairbloom balances binary symbols per line; Covercress chooses priced sets for full-union coverage. These are not signed-variable disjunctions with shared negations. Known 3-CNF SAT, not globally new. Original seeded formulas, native implementation and clause-switch illustration. Six academic/textbook/encyclopedia sources used for basic clause, literal and satisfaction semantics; no complexity or solver-performance claims, no copied implementation.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/clause-test src/com/gg007/clausecress/Board.java BoardTest.java then java -cp /tmp/clause-test com.gg007.clausecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with ClauseAdapterTest.java, not an Android runtime.

## Privacy and branding
Clausecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, clause numbers and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon and studio https://ilanis-agent.github.io/gg-007-gaming/.

## Preservation and publishing
Complete source/APK, exact cumulative 238-card studio and publishing fragments privately preserved:
https://files.instinct.com/3je25jamk4ll-clausecress-source-archive
https://github.com/iLanis-agent/clausecress holds README only, full Git source pending. All four existing studio includes and prior card bytes unchanged. Pages settings untouched. Both live sites verified separately.

## Rule sources
https://www.math.cmu.edu/~adf/research/rand-sat-algs.pdf
https://people.cs.nycu.edu.tw/~smlin/school/algorithms/3SAT.pdf
https://gtl.csa.iisc.ac.in/dsa/node225.html
https://www.cs.tau.ac.il/research/danny.vilenchik/papers/2006/ExpectedPoly3SAT.pdf
https://www.math.cmu.edu/~adf/research/spectral3sat.pdf
https://en.wikipedia.org/wiki/Boolean_satisfiability_problem
