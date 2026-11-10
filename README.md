# CYFI445 Final Project

## Team Members

- Jamie Murray

- Ethan Majeed

- Israel Burrell

## Project Overview

This project focused on tracing, visualizing, and validating AI agent tool-calling behavior using **Hermes Agent** and **Langfuse**.

The project collected trace information from Hermes Agent executions, exported telemetry into JSON reference records, generated graph visualizations, and performed validation and mutation testing using custom analysis workflows.

## Technologies Used

- Hermes Agent

- Langfuse

- GitHub

- export-trace

- trace-analyzer

## Experimental Scenarios
### M0
Baseline reasoning task without file access.

### M1
Single-file lookup using devices.csv.

### M2
Cross-file lookup using devices.csv and auth_events.csv.

### F1
Rule-based investigation using devices.csv, auth_events.csv, and alert_rule.txt.

### F2
Missing-file validation test.
