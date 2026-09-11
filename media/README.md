# Showcase media scaffold

Use real product captures with synthetic token details. The main README already
contains commented placements; enable them after adding the corresponding files.

| Suggested file | Capture | Suggested caption |
| --- | --- | --- |
| `launch-desktop.webp` | A desktop view with sample token details and destination selection visible. | Prepare a token and choose supported launch destinations in one workspace. |
| `creator-fees.webp` | Fee discovery or claim review with demo data, if available. | Review supported creator-fee positions and eligible claims. |
| `market-narratives.webp` | The market feed with narrative names, distinct-token counts, and ages visible. | Follow shared narrative arrivals without counting the same token's pools twice. |
| `walkthrough.mp4` | A 20–30 second recording of preparation, selection, and review. | From a token draft to launch review. |

## Capture outline

1. Start with a sample token such as `Example Token` / `EXAMPLE` and sample artwork.
2. Show the token details and a supported destination selection.
3. Reload once to demonstrate draft restoration.
4. Show the review step, ending before a signature or transaction submission.

Use a consistent viewport and readable interface scale. Keep personal wallet
addresses, balances, browser extensions, and operational configuration out of the
captures. Label any demo data clearly; only describe behavior visible in the
captured build.

For the video, upload it as a GitHub attachment when ready if inline playback is
preferred, then replace the README's commented video link with the attachment URL.

## Optional API case-study capture

Use two product views taken before and after a reload to illustrate a narrative
retaining its arrival time and order. If using staged data, label both views as a
demo. Pair them with the third engineering highlight in the main README. This
shows the effect of persistent API state without exposing requests, provider
configuration, database contents, or transaction payloads.
