# Kysira

Kysira is an AI-native application security company. We build a reverse proxy that reads every inbound HTTP request with a purpose-built language model and severs malicious connections at machine speed — before they reach your application stack. No rules, no regex, no signature databases. Just a model that understands what an attack looks like regardless of encoding, obfuscation, or novel phrasing.

The industry average time to detect a breach is 277 days. We think that's a tooling problem, not a people problem. Traditional WAFs are rule engines bolted onto infrastructure that was designed for a different threat model. Kysira replaces that with a compact, quantized classifier that lives as a sidecar on the request hot path, makes a decision in ~40ms on commodity CPU, and resets the TCP connection before your application ever processes a byte of malicious payload.

One container, no SDK, no code changes. Drop it in front of anything that speaks HTTP and it starts classifying traffic immediately — SQL injection, XSS, command injection, SSRF, prompt injection, credential stuffing — all of the OWASP Top 10 and beyond. The economics of accurate request classification have collapsed with modern transformers; what previously required a team of detection engineers now ships in a 60MB image. That's the bet we're building on.
