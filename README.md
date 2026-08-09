# Meridian
### A prototype AI tax platform, built for GG CPA Services

## What this is

This is a working prototype of a client platform designed for a firm like GG CPA Services.
It is not a real product connected to real client data. It is a demonstration of how the
platform could look, feel, and work, built to show product thinking and design decisions,
not just code.

You can click through every screen. Nothing here is a static picture.

## Why it is built this way

GG CPA Services is not a franchise like H&R Block. The firm builds real, personal relationships
with clients across South Jersey and the Philadelphia area, and that relationship is the reason
clients stay. So the guiding question behind every decision in this prototype was simple: how
does AI help a CPA do their job faster, without ever asking a client to trust a black box.

Every design choice below comes back to that one idea.

## Which parts of the case study this covers

The assignment offered ten possible design challenges. This prototype focuses on four of them,
built as one connected experience rather than four separate demos:

1. **Tracing every number back to its source.** A preparer should never have to take a number on
   faith. Every figure on a return can be traced back to the exact document and the exact line it
   came from.
2. **A dashboard that tells you what to work on first.** Not a wall of reports. A ranked list that
   surfaces the most urgent work automatically.
3. **A clear, consistent way to tell what is safe to click, edit, or trust.** Every number on the
   screen is color coded the same way, everywhere, so nothing is ever ambiguous.
4. **Making AI explain itself.** Any time AI touches a number, it shows its confidence and, more
   importantly, why. A percentage on its own does not build trust. A reason does.

## How to look through it

Open the file in any web browser. No installation, no account, no setup. Start on the dashboard,
click into the first return, and click on any of the colored numbers to see it in action.

## What is real and what is simulated

Being upfront about this matters, so here is exactly where the line is.

**Genuinely working:**
- Every click, every screen change, and every interaction you see
- The dashboard's ranking of returns, which is calculated live based on urgency, not hardcoded
- The connection between a number, its source document, and the highlighted line it came from
- The correction flow, including the fact that correcting a number keeps the original AI reading
  on record rather than erasing it
- Switching between a preparer's view and a manager's view of the same firm

**Simulated for the purposes of this demo:**
- All client names, dollar figures, and documents. None of this is real data.
- The AI itself. There is no actual document scanning or extraction happening. Confidence scores
  and explanations are written by hand to show how the real thing would be presented.
- Only one return (Renata Solis) has every number fully wired up to a source document. The other
  returns on the dashboard exist to show what a full, busy queue looks like.
- Buttons like Search and New Return are placeholders. They exist to show where those features
  would live, not to actually perform them yet.

## A few decisions worth knowing about

**Every dollar amount uses a distinct, evenly spaced typeface**, separate from the rest of the
text on the page. The idea is that a number should look like something you can verify, not just
another word in a sentence.

**The connection between a number and its source only appears when you click it**, and fades
after a moment, rather than staying on screen permanently. It is meant to feel like getting a
direct answer to a specific question, not a layer of clutter sitting over everything else.

**Correcting a number never deletes the AI's original answer.** In tax work, silently overwriting
what a system originally said is a liability, not a convenience. Keeping both versions on record
protects the firm and the client.

**A locked number looks different from an editable one, and clicking it does nothing.** Some
figures, like a standard IRS deduction, are simply fixed. Pretending they are editable would be
misleading, so the interface does not pretend.

**Switching from a preparer's view to a manager's view does not open a different screen.** It is
the same dashboard, reframed. The goal was one platform that adapts to who is using it, not
several products stitched together.

## What would come next with more time

- Wiring up full source tracing for more than one return, to prove the pattern holds up with
  messier, real-world documents
- A version of the dashboard for a return with no documents uploaded yet
- Making the whole flow usable without a mouse, for accessibility
