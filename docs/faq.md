# FAQ

Common questions about using Payflip, grouped by topic.

---

## Usage

### Do I need multiple wallets?

No. Payflip abstracts wallet management into a single interface. You interact with one balance, regardless of how funds are actually distributed across underlying systems.

### Do I need to bridge funds?

No. Bridging, routing, and asset movement are handled automatically. You don't move funds before using them.

### Do I need to choose a chain or asset?

No. You don't select chains, tokens, or execution paths. You interact with a unified balance, and the system determines how the transaction is executed.

### Do I need to understand crypto to use Payflip?

No. Payflip is designed so users don't need to understand chains, bridges, tokens, or gas. The system handles those concepts internally.

### Can I still control how my funds are held?

Yes. By default, Payflip works without any configuration. If you want, you can set preferences for where funds are held and how they're received. Setting preferences doesn't change the simplicity of the experience.

---

## Recipients

### How are payments sent?

Payments are made using names or email addresses, not blockchain addresses. You enter an amount and a recipient, and Payflip handles everything else.

### What does the recipient receive?

By default, the recipient receives funds in the same asset and on the same chain the sender used. If the recipient has configured preferences, funds arrive on their preferred chain and in their preferred asset format. In both cases, the sender doesn't manage this.

### What happens if the recipient is not on Payflip?

You can still send them money using their email. When they join Payflip, the funds are available to them.

---

## Security & custody

### Is Payflip custodial?

No. Payflip is non-custodial. You retain control of your funds at all times — Payflip only coordinates how they are used, never takes ownership.

### How does that work technically?

Payflip uses a smart-account model based on [EIP-7702](https://eips.ethereum.org/EIPS/eip-7702). A smart account is an on-chain account that can be programmed with custom logic — in Payflip's case, logic that lets the system execute complex cross-system flows on your behalf while keeping you as the sole owner of the underlying assets.

You don't need to understand this to use Payflip. It's the mechanism that makes "non-custodial" and "automated execution" possible at the same time.

---

## Fees & speed

### Are payments instant?

Yes. Payflip coordinates fund sourcing, routing, and execution in real time, so payments complete as a single action from your perspective. You see the result immediately.

### Are there fees?

Yes, but they're handled transparently. You don't manage gas or separate execution costs manually — any required fees are incorporated into the transaction flow and shown before you confirm.
