flowchart LR
    A[Packet Capture] --> B[Decoder]
    B --> C[Detection Engine]
    C --> D[Alert Output (EVE JSON)]
