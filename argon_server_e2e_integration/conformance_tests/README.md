# Operational Flows 

The following flows are enabled in this directory to mimic interactions with GCS:

- **F1** Accepted -> Activated -> (submit telemetry) -> Ended
- **F2** Accepted -> Activated -> (submit telemetry) -> Contingent -> Ended 
- **F3** Accepted -> Activated -> (submit telemetry) -> Non-Conforming (set by Argon Server) -> Ended
- **F4** Accepted -> Activated -> (submit telemetry) -> Non-Conforming (set by Argon Server) -> Activated (off-nominal volumes removed) (set by Argon Server) -> Ended
- **F5** Accepted -> Activated -> (submit telemetry) -> Non-Conforming (set by Argon Server) -> Contingent -> Ended


# Argon Server Conformance Monitoring 
The image below shows how the internal mechanism of Argon Server works in the context of conformance monitoring

[Argon Server Conformance High level architecture](https://github.com/xtmalliance/argon-server/blob/master/images/argon-server-conformance-monitoring.png)
