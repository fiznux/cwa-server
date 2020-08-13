# CWA-Server Documentation

- [Architecture](./ARCHITECTURE.md)
  - [Overview](./ARCHITECTURE.md#overview)
  - [Integration with Other Systems](./ARCHITECTURE.md#integration-with-other-systems)
    - [Object Store](./ARCHITECTURE.md#object-store)
    - [Verification Server](./ARCHITECTURE.md#verification-server)
  - [Security](./ARCHITECTURE.md#security)
    - [Endpoint Protection](./ARCHITECTURE.md#endpoint-protection)
    - [Authenticity](./ARCHITECTURE.md#authenticity)
    - [Fake Submissions (Plausible Deniability)](./ARCHITECTURE.md#fake-submissions--plausible-deniability-)
  - [Services](./ARCHITECTURE.md#services)
    - [Submission Service](./ARCHITECTURE.md#submission-service)
    - [Distribution Service](./ARCHITECTURE.md#distribution-service)
      - [Key Export](./ARCHITECTURE.md#key-export)
      - [Configuration](./ARCHITECTURE.md#configuration)
      - [Discovery](./ARCHITECTURE.md#discovery)
  - [Data Retention](./ARCHITECTURE.md#data-retention)
- [Distribution Service](./DISTRIBUTION.md)
  - [Spring Profiles](./DISTRIBUTION.md#spring-profiles)
    - [Available Profiles](./DISTRIBUTION.md#available-profiles)
  - [Configuration Properties](./DISTRIBUTION.md#configuration-properties)
  - [Object Store](./DISTRIBUTION.md#object-store)
    - [Headers](./DISTRIBUTION.md#headers)
    - [Threading](./DISTRIBUTION.md#threading)
    - [Error Handling](./DISTRIBUTION.md#error-handling)
    - [Retention](./DISTRIBUTION.md#retention)
  - [Assembly Process](./DISTRIBUTION.md#assembly-process)
  - [Diagnosis Key Export Files](./DISTRIBUTION.md#diagnosis-key-export-files)
  - [Signing](./DISTRIBUTION.md#signing)
  - [Bundling and Shifting](./DISTRIBUTION.md#bundling-and-shifting)
- [Submission Service](./SUBMISSION.md)
  - [Spring Profiles](./SUBMISSION.md#spring-profiles)
  - [TAN Verification](./SUBMISSION.md#tan-verification)
  - [Submission Validations](./SUBMISSION.md#submission-validations)
- [Persistence](./PERSISTENCE.md)
  - [Data Migration / Flyway](./PERSISTENCE.md#data-migration---flyway)
  - [Data Retention Policy](./PERSISTENCE.md#data-retention-policy)
- [Security](./SECURITY.md)
  - [TLS Configuration](./SECURITY.md#tls-configuration)
  - [Security-Related Spring Profiles](./SECURITY.md#security-related-spring-profiles)