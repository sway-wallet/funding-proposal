# Funding proposal for SWAY Wallet Integration into EON

## Objective Statement

The objective of this proposal is to integrate the SWAY Wallet — a Simple Wallet and Yield solution—into the EON ecosystem, leveraging its full EVM compatibility for enhanced user security and experience. The integration aims to utilize **MetaMask Snaps** to bring the power of Zero Knowledge Proofs (ZKPs), Social Recovery, and Smart OTPs directly to the EON network. By implementing a Diamond Upgradeable Smart Contract Wallet based on ERC-2535 (Diamonds, Multi-Facet Proxy), SWAY will provide a robust and flexible infrastructure for wallet management.

This integration targets to:

- Empower **average users** by simplifying the management of private keys and mnemonic phrases, thus removing barriers to entry and enhancing security.
- Drive **user adoption to Horizen** by offering a secure, yet user-friendly wallet interface, promoting greater engagement and network growth.
- Create **opportunities for developers to build and monetize extensions** for the SWAY Wallet, much like existing platforms such as NL Bots, fostering an innovative and revenue-generating ecosystem.

The ultimate goal is to make Horizen's EON platform the go-to for both novices and veterans in the cryptocurrency space by delivering a seamless, secure, and adaptable wallet experience.

## Problem Statement

The current landscape of cryptocurrency wallet security is fraught with challenges. Users often face the daunting task of managing private keys and mnemonic phrases, which, if lost or stolen, can lead to irreversible asset loss. Traditional security measures have proven inadequate against the evolving threats, leaving a gap for a solution that balances robust security with ease of use.

- **Cryptocurrency wallet security is a really big problem**
- **Cryptocurrency wallets are hard to use for average users**
- **Hardware wallets alone are not good enough**
- **Mnemonic phrases are not good enough**

### Cryptocurrency wallet security is a really big problem

Wallet security is a major concern in the cryptocurrency ecosystem, with numerous stories of losses and thefts plaguing the industry. Hardware wallets, while considered to be the most secure type of wallet, are not foolproof and can still be vulnerable to attacks. Software wallets and web wallets, on the other hand, are more vulnerable to attacks due to their connection to the internet.

In addition, losses can occur due to the loss of private keys or the forgetting of passwords. This can be catastrophic, as there is often no way to recover lost funds. The importance of the wallet security problem cannot be underestimated, and it is essential that solutions be developed to reduce the quantity of losses and thefts taking place.

### Cryptocurrency wallets are hard to use for average users

Many cryptocurrency users, especially those who are new to the space, find it difficult to navigate the complexities of wallets and transactions. The process of setting up a wallet, transferring funds, and executing smart contracts can be confusing and intimidating for those who are not tech-savvy. This can lead to a lack of adoption, as users may be hesitant to use cryptocurrency if they do not feel comfortable with the process.

### Hardware wallets alone are not good enough

Hardware wallets are often touted as the best-in-class solution for cryptocurrency funds management. However, they are not foolproof and can still be vulnerable to attacks. In addition, they may not be user-friendly for those who are not tech-savvy, and can be lost or stolen. While hardware wallets do provide an additional layer of security, they are not a standalone solution to the wallet security problem.

### Mnemonic phrases are not good enough

Mnemonic phrases, also known as seed phrases or recovery phrases, are a common method of backing up and restoring wallet data. They are a series of words that can be used to recreate a user's private keys and restore access to their funds. However, mnIf you lose your wallet but you have the mnemonic phrase, you can input the phrase when setting up a new wallet to recover your account, as the mnemonic phrase contains the root key from which all of your other keys can be generated.

Mnemonic phrases are good for protecting against loss, but they do nothing against theft. Even worse, they add a new vector for theft: if you have the standard hardware wallet + mnemonic backup combo, then someone stealing either your hardware wallet + PIN or your mnemonic backup can steal your funds. Furthermore, maintaining a mnemonic phrase and not accidentally throwing it away is itself a non-trivial mental effort.

## Solution

SWAY Wallet addresses these concerns by offering a keyless solution that eliminates the need for users to handle sensitive information directly. It integrates advanced security measures, such as Zero Knowledge Proofs, to provide privacy and security without compromising usability. Its use of Social Recovery introduces a decentralized approach to asset recovery, while Smart OTPs offer an additional layer of security for transactions.

For EON's scalable infrastructure, SWAY's upgradable smart contract wallet aligns perfectly. It supports EON's scalability goals by ensuring that as the network grows, the wallet's security features can evolve without disrupting the user experience or compromising security. This makes SWAY an ideal candidate for integration into the EON platform, promising to elevate the security standards while enhancing user adoption through its simplified approach to wallet management.

## Technical Overview

The SWAY Wallet is a paradigm shift in crypto-asset management, employing cutting-edge technologies to enhance user security and experience. At its core, SWAY utilizes ZK Social Recovery, allowing users to regain access to their wallet through trusted individuals or entities—guardians—without exposing sensitive data. This mechanism leverages Zero Knowledge Proofs to authenticate recovery actions while preserving privacy.

In tandem, Smart OTPs provide a dynamic layer of security for transactions. These one-time passwords are generated through algorithms that ensure each code is unique and time-bound, significantly reducing the risk of unauthorized access.

For EON's EVM-compatible sidechain, SWAY Wallet's architecture can be seamlessly integrated. The sidechain's capacity for handling numerous transactions and smart contracts aligns with SWAY's scalable security features. The Diamond Standard (ERC-2535) further enhances this by allowing modular updates to the wallet's facets, ensuring that it remains robust against evolving threats while catering to a growing user base on EON.

## Integration Strategy

The integration of SWAY Wallet with EON requires a strategic approach that encompasses both technical implementation and community engagement:

- **Technical Assessment**: Evaluate EON's infrastructure compatibility with SWAY Wallet's features, focusing on the EVM compatibility and the Diamond Standard implementation.

- **Community Consultation**: Engage with the EON and Horizen communities to align the integration with user needs and expectations, gathering feedback and building anticipation.

- **Guardian Network Establishment**: Set up a robust network of guardians, leveraging the Horizen community's existing trust structures and reputation systems.

- **Smart Contract Deployment**: Develop and deploy a suite of smart contracts on EON's sidechain, designed in accordance with the Diamond Standard for upgradability and flexibility.

- **Security Auditing**: Conduct thorough security audits of the SWAY Wallet integration to ensure the resilience of the system against potential vulnerabilities.

- **User Interface Adaptation**: Customize SWAY Wallet's user interface for EON, ensuring a seamless experience that resonates with the platform's users.

- **Beta Testing**: Roll out a beta version of the integration to a closed group of EON users, collecting data on usability and security, and making iterative improvements.

- **Educational Campaign**: Launch an educational campaign to inform users about the features and benefits of SWAY Wallet, emphasizing its security aspects and ease of use.

- **Full Deployment**: After successful testing and community approval, fully deploy SWAY Wallet on EON, with continuous monitoring and support.

- **Ongoing Development**: Establish a framework for continuous improvement and extension development, encouraging the Horizen developer community to contribute to the SWAY Wallet ecosystem.

## Security Analysis

SWAY Wallet enhances the security of digital asset management on the EON sidechain by incorporating several innovative features:

- **ZK Social Recovery**: SWAY Wallet's Social Recovery feature allows users to recover access to their wallets through a network of trusted guardians without revealing any sensitive information. This decentralized approach mitigates the risks associated with the loss or theft of private keys or mnemonic phrases.

- **Smart OTPs**: The Wallet employs Smart One-Time Passwords (OTP), adding an extra security layer for transaction verification. These passwords are generated and validated using cryptographic hash functions, ensuring that each OTP is unique and ephemeral.

- **Zero Knowledge Proofs**: By leveraging Zero Knowledge Proofs, SWAY Wallet ensures that no personal or sensitive user data is disclosed during transactions or wallet recovery. This preserves user privacy while maintaining high security standards.

- **Diamond Upgradeable Smart Contract**: The use of Diamond Standard (ERC-2535) for smart contracts allows for modular updates and enhancements to the wallet's functionality without sacrificing security or requiring migrations that expose users to risks.

- **Compatibility with Fast Finality Blockchains**: The technical analysis from the provided documents indicates that SWAY Wallet is well-suited to blockchains with fast finality, like EON, which prevents double-spending attacks and provides quicker transaction confirmations.

- **Resilience to Quantum Computing**: The wallet's security mechanisms are built on hash-based cryptographic practices, which are known to have inherent resistance to quantum computing attacks. This future-proofs the wallet against potential threats posed by advancements in quantum technology.

The implementation of SWAY Wallet on EON's sidechain will take advantage of these security features, aligning with the sidechain's emphasis on scalability and secure, fast transactions. This integration will significantly enhance the overall security posture of the EON platform, providing users with a robust, resilient, and user-friendly wallet solution.

## User Experience

The SWAY Wallet is poised to revolutionize the user experience (UX) for EON users by focusing on simplification, security, and seamless interaction with the blockchain. Here's how it enhances UX:

- **Simplified Key Management**: SWAY eliminates the complexity associated with managing private keys and mnemonic phrases. This simplicity lowers the entry barrier for new users and reduces the stress for experienced users worried about losing access to their assets.

- **Social Recovery**: The integration of Social Recovery allows users to regain access to their funds through a network of trusted contacts without compromising security. This feature not only provides peace of mind but also adds a layer of social interaction, which can enhance community engagement within the EON ecosystem.

- **Smart OTPs**: By integrating Smart OTPs, SWAY ensures each transaction is secure and unique, offering users a familiar experience similar to other secure services like banking apps. This familiarity promotes user confidence and trust in the system.

- **Zero Knowledge Proofs**: The use of Zero Knowledge Proofs ensures that users' privacy is maintained, a feature that is highly valued by cryptocurrency enthusiasts and can be a strong draw for privacy-conscious users.

- **Upgradable Smart Contracts**: The Diamond Standard allows for the wallet's continuous improvement without service interruption or the need for users to take action. This ensures that the wallet grows with the user's needs and with EON's expanding capabilities.

- **User-Centric Design**: A focus on an intuitive and accessible design ensures that users of all technical levels can navigate the wallet with ease, which is crucial for widespread adoption.

- **Community-Driven Extensions**: With the ability for developers to create and integrate extensions, users benefit from a rich ecosystem of features and services, tailored to their needs and driving continuous engagement.

- **Security Without Compromise**: While the wallet simplifies the user experience, it does not compromise on security. The balance between high security and ease of use is key to ensuring that users feel comfortable and safe while navigating the EON platform.

By addressing these critical aspects of UX, SWAY Wallet is expected to achieve higher adoption rates and user satisfaction, contributing to the growth and success of the Horizen EON ecosystem.

## Budget

**Design / UI/UX**:

- Initial design and prototyping: $2,000
- User interface development: $3,000
- User experience testing and improvements: $1,000

### Integrate Horizen EON to MetaMask Snap, implement the SNAP

- Development and integration: $10,000
Testing and deployment: $5,000

### Integrate PoC zkWallet to MetaMask Snap, including Wallet UI

- Integration of existing features to MetaMask Snap (semaphore group, guardians, ERC20 management): $10,000
- Deployment and testing: $5,000

### Shamir Secret Sharing into MetaMask Snap

- Development of secret sharing mechanism: $5,000
- Integration with MetaMask Snap: $5,000

### ZK Recovery Service

- Development of ZK proofs for recovery service: $10,000
Integration and testing with the EON blockchain: $5,000

## Add SmartOTP's

- Development of SmartOTP feature: $30,000
- Integration and testing: $5,000

### Integrate existing DEX

- DEX integration: $39,000
- Facet development and testing: $5,000
  
### Hosting for 1 year

- Server costs: $2,000
- Maintenance and monitoring: $5,000

## Milestones and Timeline

### Phase 1 MetaMask Snap, budget $36,000

Milestone 1: Design / UI/UX Completion

- Deliverables:
  - Completed design prototypes.
  - UI/UX test reports.
- Timeframe: Month 1-2

Milestone 2: MetaMask Snap and SWAY Integration

- Deliverables:
  - Integration strategy for Horizen EON with MetaMask Snap.
  - PoC zkWallet features integrated into MetaMask Snap.
- Timeframe: Month 2-3

## Phase 2 ZK Recovery Service and Smart OTPs, budget $60,000

Milestone 3: Shamir Secret Sharing and ZK Recovery Service

- Deliverables:
  - Development of Shamir Secret Sharing mechanism for MetaMask Snap.
  - ZK Recovery Service with proof-of-concept integration.
- Timeframe: Month 4-5

Milestone 4: Smart OTPs Integration

- Deliverables:
  - Smart OTP feature fully developed and integrated.
- Timeframe: Month 5-6
  
## Phase 3 DEX Integration, $44,000

Milestone 5: DEX Integration

- Deliverables:
  - Existing DEX integrated with SWAY contracts.
- Timeframe: Month 7-9


## References

- [ERC-2535: Diamonds, Multi-Facet Proxy](https://eips.ethereum.org/EIPS/eip-2535)
- [Bots.io](https://bots.io/)
- [SmartOTPs: An Air-Gapped 2-Factor Authentication for
Smart-Contract Wallets (Extended Version)](https://arxiv.org/pdf/1812.03598.pdf)
- [Hours of Horus:
Keyless Cryptocurrency Wallets](https://eprint.iacr.org/2021/715.pdf)
- [MetaMask Snaps](https://docs.metamask.io/snaps/)
- [zkWallet evm](https://github.com/zkWallet/zkWallet-docs)
