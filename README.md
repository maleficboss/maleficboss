# Usman Ayomide

JavaScript developer building wallet-safety tools for Web3. Node and Express on the back end, React on the front, ethers v6 for the chain. Self-taught, shipping in public.

## Building now

### Wallet Approval Scanner
[Repo](https://github.com/maleficboss/ui-practice)

Enter a wallet address and see every ERC-20 approval it has given out, with unlimited approvals flagged.

- Express backend pulls approval logs with `eth_getLogs`, scanning the last 300 blocks in 10-block chunks
- Reads the live allowance, decimals and symbol for each token and spender pair
- Flags unlimited approvals (`MaxUint256` and max `uint96`)
- Server errors return a fixed message, never the raw provider response. I leaked an API key that way once, rotated it and closed the hole.
- React frontend, running on Sepolia for now

**Next:** wallet connect, then a simulator that shows what a transaction will do before you sign it. I'm building that part after a run-in with a drainer contract.

## Shipped

### CoinScope
[Live](https://coinscope-j49d.onrender.com/) · [Repo](https://github.com/maleficboss/coinscope)

A live crypto dashboard on the CoinGecko API that tracks prices and market data in real time. Deployed on Render. Its 27-second demo was shared by a CoinGecko PM ([post](https://x.com/maleficboss/status/2074777038943137841)).

More in my [repositories](https://github.com/maleficboss?tab=repositories).

## Stack

- **Language:** JavaScript
- **Back end:** Node.js · Express · EJS · REST APIs
- **Front end:** React
- **Database:** PostgreSQL
- **Web3:** ethers v6 · Alchemy

## Connect

- X: [@maleficboss](https://x.com/maleficboss)
- LinkedIn: [maleficboss](https://linkedin.com/in/maleficboss)
- Email: oyebamijiusmanayomide@gmail.com

Open to freelance and contract work.
