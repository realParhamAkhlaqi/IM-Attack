# Methodology

## Testing Protocol
- Each prompt was sent **once** to each model.
- Responses were recorded **completely and without any editing** in the `test.txt` file.
- **Objective:** Capture the **first reaction** of each model without using multi-step prompt engineering techniques.
- **No iterative refinement** or follow-up prompts were used to extract additional information.

## Rationale
This approach aims to simulate a real-world attack scenario where an adversary has only **one opportunity** to bypass the model's safety mechanisms. The first response is the most critical indicator of the model's inherent vulnerability.
