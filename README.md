
# btckun

**btckun** is a video browsing application designed for charitable organizations, enabling users to donate using Bitcoin, either on-chain or over the Lightning Network. It aims to simplify and amplify charitable donations by leveraging cryptocurrency's benefits such as minimal transaction fees and faster settlement times.

## Inspiration

Inspired by the need for efficient and transparent charitable donations, btckun aims to provide a platform where users can easily discover and support various charitable causes using Bitcoin.

## What it does

btckun allows users to browse through charitable organizations featured on the platform and make donations directly using Bitcoin. Donations can be sent either on-chain or via the Lightning Network, depending on the charity's setup.

## How we built it

- **Frontend**: Built using React.js, providing a responsive and intuitive user interface.
- **Backend**: Node.js server manages charity information and transaction handling.
- **Authentication**: Blockstack authentication API is used for user accounts and profiles.
- **Storage**: Blockstack's Gaia decentralized storage handles donation history securely.
- **Payment Integration**: Utilizes the OpenNode Lightning Network API for Bitcoin payments.

## Challenges we ran into

Integrating Lightning Network payments securely and ensuring seamless user experience were primary challenges. Ensuring compatibility with various Bitcoin wallets and exchanges for Lightning Network payments also required careful planning and implementation.

## Accomplishments that we're proud of

- Successfully integrating Lightning Network payments, providing users with a fast and cost-effective way to donate.
- Implementing Blockstack for decentralized user authentication and storage, enhancing privacy and security.

## What we learned

- Enhanced understanding of Bitcoin's Lightning Network and its potential for micropayments in charitable donations.
- Improved skills in frontend and backend integration for decentralized applications.

## What's next for btckun

- **Payment Integration**: Expand support for more Bitcoin wallets and exchanges.
- **Automated Withdrawals**: Implement automated withdrawal options for charities.
- **Enhanced User Engagement**: Introduce social sharing features to encourage wider adoption and donations.

Check it out live at [btckun.app](https://blockcharity.space/).
