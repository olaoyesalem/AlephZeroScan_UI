# Aleph Zero Blockchain Explorer
## Tooling/Infrastructure - Create developer/infrastructure tooling for the Aleph Zero Ecosystem.
## Overview


Welcome to the Aleph Zero Blockchain Explorer - your gateway to the heart of the Aleph Zero blockchain. Crafted with precision and designed for seasoned developers, this project is the culmination of our efforts in the [Hackathon Name]. Dive deep into Aleph Zero's intricacies, explore extrinsic transactions, unravel event blocks, and seamlessly navigate to the Aleph Zero documentation for a holistic understanding.

## Features

- **Extrinsic Transactions:** Illuminate the intricate dance of transactions within the Aleph Zero blockchain. Uncover sender details, recipient information, transaction amounts, and timestamps with unparalleled clarity.

- **Event Blocks:** Elevate your insights by exploring event blocks. Gain a nuanced understanding of diverse activities pulsating through the Aleph Zero network.



### AlephZero SUBQL
[link](https://github.com/olaoyesalem/alephZeroScan_suql.git)

* AFter Cloning the repository above
run 
```bash
yarn subql publish
```
this will get the CID.
* Head On to [link](https://managedservice.subquery.network). Create a project with the CID;
*  Take the hash of the project you have deployed on subquery and add it to this repository in the
  ```bash
src/utils/index.ts
```
Deploy The Boiler Plate of the UI- [link](https://github.com/olaoyesalem/AlephZeroScan_UI.git)

You're Done 😍


## Getting Started

### Prerequisites

To embark on this journey, ensure you have the following tools at your disposal:

- **Node.js:** The backbone of our development environment. Install it from [here](https://nodejs.org/).

- **Yarn (Optional):** Enhance your package management experience with Yarn. Install it from [here](https://yarnpkg.com/).

### Installation

1. Clone this repository:

   ```bash
    git clone https://github.com/your-username/aleph-zero-explorer.git
   ```
2. Navigate to the project directory:
 ```bash
 cd alephZeroScan_UI
 ```
 3. Install Dependencies
 ``` bash
 yarn install
```

### Usage

1. Ignite Development Server
``` bash
yarn start
```




### License
This project operates under the permissive MIT License.

### Acknowledgments
A heartfelt thank you to the Aleph Zero team for their unwavering support and the wealth of knowledge found in the Aleph Zero documentation.



#### Contributors
Olaoye Salem 
