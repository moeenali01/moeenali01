<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/banner-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/banner-light.svg"><img src="assets/bento/banner-dark.svg" width="100%" alt="Moin Shahid — Blockchain Engineer and Smart Contract Security Researcher."></picture>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-145A9D?style=for-the-badge&labelColor=0D1729&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBmaWxsPSIjZmZmZmZmIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BTGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D&logoColor=white)](https://linkedin.com/in/moin-shahid)
[![Email](https://img.shields.io/badge/Email-126B78?style=for-the-badge&labelColor=0D1729&logo=gmail&logoColor=white)](mailto:moinshahid919@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-5A4DB5?style=for-the-badge&labelColor=0D1729&logo=github&logoColor=white)](https://github.com/moeenali01)

[![ABOUT](https://img.shields.io/badge/ABOUT-264362?style=flat-square)](#about)
[![RESEARCH](https://img.shields.io/badge/RESEARCH-264362?style=flat-square)](#security-research)
[![EXPERIENCE](https://img.shields.io/badge/EXPERIENCE-264362?style=flat-square)](#experience)
[![PROJECTS](https://img.shields.io/badge/PROJECTS-264362?style=flat-square)](#selected-engineering-work)
[![TOOLKIT](https://img.shields.io/badge/TOOLKIT-264362?style=flat-square)](#technical-toolkit)
[![EDUCATION](https://img.shields.io/badge/EDUCATION-264362?style=flat-square)](#education--continuous-learning)
[![CONTACT](https://img.shields.io/badge/CONTACT-264362?style=flat-square)](mailto:moinshahid919@gmail.com)

</div>

<br/>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-01-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-01-light.svg"><img src="assets/bento/section-01-dark.svg" width="100%" alt="Section 01 divider"></picture>

## About

### I build with the failure modes in mind.

I am a **Blockchain Engineer**, working across **EVM and Solana**. I build DeFi and smart contract systems, then examine the assumptions that can fail under adversarial use: accounting, permissions, oracle inputs, and upgrade paths.

At **Webevis Technologies**, I develop Solidity contracts and Foundry test suites for EVM deployments. My Solana work uses **Rust, Anchor, and Bankrun**. I aim for systems whose state transitions are clear, whose privileged actions are narrow, and whose important behaviors are covered by reproducible tests.

**How I work**

- **Design:** define invariants, value flows, and trust boundaries before implementation.
- **Verify:** test normal flows, edge cases, and adversarial interactions with unit, fuzz, and invariant tests.
- **Harden:** apply least-privilege access, careful validation, reentrancy protection, and gas-conscious architecture.

<details>
<summary><b>View my profile as Solidity and Rust</b></summary>

<br/>

<p><img src="https://img.shields.io/badge/whoami.sol-about_me-145A9D?style=for-the-badge&labelColor=0D1729&logo=solidity&logoColor=white" alt="whoami.sol - about me, written in Solidity" /></p>

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

/// @title whoami
/// @author Moin Shahid
contract MoinShahid {
    string public constant NAME = "Moin Shahid";
    string public constant ROLE = "Blockchain Engineer";
    string public constant FOCUS = "Smart contract security";
    string public constant COMPANY = "Webevis Technologies";
    string public constant BASED_IN = "Lahore, Pakistan";
    string public constant DEGREE = "BS Information Technology";
    string public constant MOTTO = "Build. Break. Harden.";

    function chains() external pure returns (string[2] memory) {
        return ["EVM", "Solana"];
    }

    function languages() external pure returns (string[3] memory) {
        return ["Solidity", "Rust", "JavaScript"];
    }

    function contact() external pure returns (string memory) {
        return "moinshahid919@gmail.com";
    }
}
```

<p><img src="https://img.shields.io/badge/profile.rs-status_%2B_core__stack-145A9D?style=for-the-badge&labelColor=0D1729&logo=rust&logoColor=white" alt="profile.rs - Solana program with status and core_stack instructions" /></p>

```rust
use anchor_lang::prelude::*;

declare_id!("Fg6PaFpoGXkYsidMpWTK6W2BeZ7FEfcYkg476zPFsLnS");

#[program]
pub mod profile {
    use super::*;

    pub fn status(_ctx: Context<Show>) -> Result<()> {
        msg!("Now: Webevis Technologies");
        msg!("Chains: EVM + Solana");
        msg!("Findings: 3 High, 2 Medium, 1 Low");
        Ok(())
    }

    pub fn core_stack(_ctx: Context<Show>) -> Result<()> {
        msg!("EVM: Solidity, Foundry");
        msg!("Solana: Rust, Anchor, Bankrun");
        msg!("Oracles: Chainlink, Pyth, TWAP");
        Ok(())
    }
}

#[derive(Accounts)]
pub struct Show {}
```

<sub>Yes, it compiles. &nbsp;<code>solc 0.8.30</code> · zero warnings &nbsp;·&nbsp; <code>anchor&#8209;lang 1.2.2</code> · clippy clean.</sub>

</details>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-02-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-02-light.svg"><img src="assets/bento/section-02-dark.svg" width="100%" alt="Section 02 divider"></picture>

## Security Research

My research focuses on protocol correctness, economic and accounting invariants, authorization boundaries, upgrade safety, oracle integrity, and reproducible proof-of-concept testing.

<div align="center">

<a href="#security-research"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/audit-1-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/audit-1-light.svg"><img src="assets/bento/audit-1-dark.svg" width="414" alt="RAIN-USDR Smart Contract Audit, HackenProof · Sep 2026: 2 HIGH, 1 MEDIUM. Confirmed."></picture></a>
<a href="#security-research"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/audit-2-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/audit-2-light.svg"><img src="assets/bento/audit-2-dark.svg" width="414" alt="Firelight, Immunefi: 1 HIGH. Confirmed."></picture></a>
<a href="#security-research"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/audit-3-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/audit-3-light.svg"><img src="assets/bento/audit-3-dark.svg" width="414" alt="BattleChain Confidence Pools, CodeHawks: 1 MEDIUM, 1 LOW. Confirmed."></picture></a>
<a href="#security-research"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/record-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/record-light.svg"><img src="assets/bento/record-dark.svg" width="414" alt="Research record: 6 confirmed findings across public smart contract audit contests - 3 High, 2 Medium, and 1 Low - backed by reproducible proof-of-concept tests."></picture></a>

</div>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-03-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-03-light.svg"><img src="assets/bento/section-03-dark.svg" width="100%" alt="Section 03 divider"></picture>

## Experience

<div align="center">

<a href="#experience"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/exp-1-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/exp-1-light.svg"><img src="assets/bento/exp-1-dark.svg" width="414" alt="Blockchain Developer, Webevis Technologies, Jan 2025 - Present. Develop and deploy secure, gas-optimized Solidity smart contracts across EVM chains. Build comprehensive Foundry test suites with strong coverage to surface vulnerabilities before deployment. Apply access control, reentrancy protection, validation, and upgrade-safety patterns throughout the development lifecycle. Collaborate with frontend engineers and product teams to deliver reliable end-to-end blockchain integrations. Solidity, Foundry, Access control, Reentrancy protection, Upgrade safety."></picture></a>
<a href="#experience"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/exp-2-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/exp-2-light.svg"><img src="assets/bento/exp-2-dark.svg" width="414" alt="Blockchain Developer Intern, Dafi Labs, Sep 2024 - Dec 2024. Engineered multi-node blockchain infrastructure with Geth and GoQuorum using Raft and Proof-of-Work consensus. Built a custom block explorer for real-time visibility into blocks, transactions, and network activity. Developed and tested smart contracts across EVM-compatible networks using industry-standard security practices. Geth, GoQuorum, Raft, Proof-of-Work, Block explorer."></picture></a>

</div>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-04-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-04-light.svg"><img src="assets/bento/section-04-dark.svg" width="100%" alt="Section 04 divider"></picture>

## Selected Engineering Work

<div align="center">

<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-1-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-1-light.svg"><img src="assets/bento/project-1-dark.svg" width="414" alt="EdgeMarket.ai. Decentralized Prediction Market, BSC Mainnet. Developed and deployed a decentralized prediction market that supports market creation, positions, and outcome resolution. Implemented secure result validation, automated payout distribution, and incentive mechanisms for reliable settlement."></picture></a>
<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-2-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-2-light.svg"><img src="assets/bento/project-2-dark.svg" width="414" alt="Meme Curve Launch. Upgradeable Token Launch Protocol, EIP-2535 Diamond. Built a modular token-launch and trading protocol with dedicated facets for token creation, fees, views, pausing, and upgrades. Implemented reserve-based bonding-curve trading with virtual liquidity, slippage protection, configurable fees, reentrancy guards, and internal pool accounting."></picture></a>
<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-3-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-3-light.svg"><img src="assets/bento/project-3-dark.svg" width="414" alt="Merkle Vesting Protocol. Solana, Rust + Anchor. Designed a scalable vesting system supporting thousands of allocations while storing a single Merkle root on-chain. Implemented linear vesting, cliffs, rate-limited and revocable claims, and M-of-N governance for privileged operations."></picture></a>
<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-4-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-4-light.svg"><img src="assets/bento/project-4-dark.svg" width="414" alt="Decentralized Oracle with TWAP. Solana, Rust + Anchor. Architected a stake-weighted median oracle with confidence intervals for manipulation-resistant price feeds. Implemented TWAP-based price discovery to reduce flash-loan and short-window manipulation risk."></picture></a>
<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-5-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-5-light.svg"><img src="assets/bento/project-5-dark.svg" width="414" alt="Multi-Chain Algorithmic Stablecoin. Ethereum + Solana, Over-collateralized. Architected an over-collateralized stablecoin system spanning Ethereum and Solana with WETH, WBTC, and SOL collateral. Integrated Chainlink and Pyth feeds with health-factor monitoring, efficient mint and burn flows, and strict collateral controls."></picture></a>
<a href="#selected-engineering-work"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/project-legend-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/project-legend-light.svg"><img src="assets/bento/project-legend-dark.svg" width="414" alt="5 systems showcased: 2 EVM, 2 Solana, 1 multi-chain. The chip on each tile shows the ecosystem."></picture></a>

</div>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-05-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-05-light.svg"><img src="assets/bento/section-05-dark.svg" width="100%" alt="Section 05 divider"></picture>

## Technical Toolkit

<div align="center">

<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-1-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-1-light.svg"><img src="assets/bento/tool-1-dark.svg" width="414" alt="Languages & Web3 integration: Solidity, Rust, JavaScript, Ethers.js, Web3.js, IPFS"></picture></a>
<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-2-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-2-light.svg"><img src="assets/bento/tool-2-dark.svg" width="414" alt="Frameworks & testing: Foundry, Anchor, OpenZeppelin, Bankrun, Remix"></picture></a>
<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-3-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-3-light.svg"><img src="assets/bento/tool-3-dark.svg" width="414" alt="Chains & infrastructure: Ethereum, Solana, BNB Chain, Arbitrum, Optimism, Geth, GoQuorum"></picture></a>
<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-4-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-4-light.svg"><img src="assets/bento/tool-4-dark.svg" width="414" alt="Oracle systems: Chainlink, Pyth, TWAP, Stake-weighted aggregation"></picture></a>
<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-5-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-5-light.svg"><img src="assets/bento/tool-5-dark.svg" width="414" alt="Smart contract standards: ERC-20, ERC-721, ERC-1155, ERC-4626, EIP-712, EIP-2612, EIP-2535, EIP-4337"></picture></a>
<a href="#technical-toolkit"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/tool-6-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/tool-6-light.svg"><img src="assets/bento/tool-6-dark.svg" width="414" alt="Security & architecture: Access control, Reentrancy protection, Upgrade safety, Invariant testing, Merkle proofs, Meta-transactions, Account abstraction"></picture></a>

</div>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-06-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-06-light.svg"><img src="assets/bento/section-06-dark.svg" width="100%" alt="Section 06 divider"></picture>

## Education & Continuous Learning

<div align="center">

<a href="#education--continuous-learning"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/edu-degree-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/edu-degree-light.svg"><img src="assets/bento/edu-degree-dark.svg" width="414" alt="Bachelor of Science in Information Technology, National Textile University · Faisalabad, Pakistan, Sep 2020 - Jul 2024"></picture></a>
<a href="#education--continuous-learning"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/edu-courses-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/edu-courses-light.svg"><img src="assets/bento/edu-courses-dark.svg" width="414" alt="Solana Developer Bootcamp (2024). Advanced Foundry - Cyfrin Updraft. Ethereum Developer Bootcamp - Udemy. Ultimate Rust Crash Course - Udemy"></picture></a>

</div>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/section-07-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/section-07-light.svg"><img src="assets/bento/section-07-dark.svg" width="100%" alt="Section 07 divider"></picture>

## What I Bring

<div align="center">

<a href="mailto:moinshahid919@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/bring-build-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/bring-build-light.svg"><img src="assets/bento/bring-build-dark.svg" width="272" alt="BUILD: Smart contracts and protocol infrastructure across EVM and Solana"></picture></a>
<a href="mailto:moinshahid919@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/bring-break-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/bring-break-light.svg"><img src="assets/bento/bring-break-dark.svg" width="272" alt="BREAK: Adversarial review, invariant analysis, and reproducible exploit tests"></picture></a>
<a href="mailto:moinshahid919@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/bento/bring-harden-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/bento/bring-harden-light.svg"><img src="assets/bento/bring-harden-dark.svg" width="272" alt="HARDEN: Secure architecture, robust testing, and production-ready integrations"></picture></a>

</div>

<div align="center">

### Let's build protocols that are difficult to break.

[![Start a conversation](https://img.shields.io/badge/Start_a_conversation-126B78?style=for-the-badge&labelColor=0D1729&logo=gmail&logoColor=white)](mailto:moinshahid919@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-145A9D?style=for-the-badge&labelColor=0D1729&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBmaWxsPSIjZmZmZmZmIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BTGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D&logoColor=white)](https://linkedin.com/in/moin-shahid)

</div>
