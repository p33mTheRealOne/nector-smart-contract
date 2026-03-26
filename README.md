# nector-smart-contract
Nector smart contract implementation — a deterministic escrow state machine handling funding, delivery, disputes, and timeouts. Built in Rust and TypeScript, and this is the exact same smart contract used in production on Nector.

# Overview

Nector is a chat-native, non-custodial escrow system designed to enable safe transactions between strangers.

This repository contains the exact smart contract used in production, written in:

Rust (on-chain program)
TypeScript (clients, scripts, automation)

The contract is designed as a deterministic state machine, where every transition is enforced by:

strict rules
time-based constraints
economic incentives
