# LER-RS-API
Sandbox for developing an OpenAPI spec for the LER-RS API use cases.

Requirements: Open APIs to support three use cases. 

Three use cases:
A. Moving parts of a resume, or bundles of parts, e.g. one or more OBv3 or other VC/VP
B. Moving and LER-RS from system B to system C (e.g. job board or back to wallet) as a VC/VP (lerr-openapi_v1.json)
C. Apply for a job (including workflow and metadata, record of when applied etc.) (same API as B but with additional workflow support)

Open questions:
* Can CHAPI be used for use case A? Does CHAPI support bundles of VCs? If so then it may be a good choice for A. If not a new Open API that supports array of VC (and non-VC parts of a resume?) may be best.
* Is the issuer of a VC always the person, who owns the DID?
