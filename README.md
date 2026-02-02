# Blocks
Building Blocks of a  Privacy respecting digital world
# Unchuchu Blocks


**The most powerful code is the code we didn't write.**
**The second most powerful is the privacy-preserving one.**

---

## The Philosophy

Before you build anything, ask:

**Do I need to do this at all?**
Not "can I do this in a privacy-preserving way?"
*Do I need to do it at all?*
If no, don't. That's the first win. Most tracking exists because no one asked this question.

If yes, do it without extraction. That's what this repo is for.

---

## The Gap

There's a mountain of brilliant research on privacy-preserving technology. Zero-knowledge proofs. Differential privacy. Confidential computing. Oblivious RAM. Secure multi-party computation.

Papers get published. Conferences happen. Academics cite each other.

Meanwhile, developers ship Google Analytics because it's one line of code.

The research exists. The building blocks don't.

---

## The Problem

Privacy-respecting tech stays trapped in:

- Academic papers nobody reads
- Enterprise products nobody can afford
- Cryptography libraries nobody understands
- Startups that get acquired and shut down

The ideas are proven. The implementations are inaccessible. The gap between "mathematically possible" and "I can npm install this" is enormous.

So developers compromise. They add tracking because the alternative is building a cryptographic protocol from scratch. They store passwords because zero-knowledge auth sounds like a PhD thesis. They collect everything because differential privacy seems like something only Apple can do.

It doesn't have to be this way.

---

## The Idea

Take the research. Turn it into code building blocks. Make them usable.

Not dumbed down. Not "privacy-lite." The real thing. Zero-knowledge proofs that a solo developer can ship. Differential privacy that a startup can afford. Confidential computing that doesn't require a team of cryptographers.

Code that knows nothing. By design. By math. Not by promise.

---

## What This Is

Two things:

### 1. Patterns for Not Doing Things

Code that doesn't track. Not because of fancy cryptography. Because tracking wasn't needed.

Sometimes the answer is "just don't." We document that.

### 2. Building Blocks for Doing Things Privately

When you actually need the functionality — when you genuinely need to verify identity, count users, process data — do it with math, not trust.

- Zero-knowledge proofs
- Differential privacy
- Confidential computing
- Secure multi-party computation

The research exists. We turn it into usable code.

---

## What Exists vs What's Needed

**Zero-knowledge proofs:**
- Exists: ZK-SNARKs, ZK-STARKs, Groth16, Plonk, circom, snarkjs, halo2
- Missing: "Here's how to add ZK auth to your app in an afternoon"

**Differential privacy:**
- Exists: Google's DP library, OpenDP, Apple's implementation
- Missing: "Here's privacy-preserving analytics you can self-host in 10 minutes"

**Confidential computing:**
- Exists: Intel SGX, AMD SEV, AWS Nitro Enclaves
- Missing: "Here's a VM config that actually uses these things correctly"

The primitives exist. The bridges don't.

We're building bridges.

---

## Building Blocks



### Blocks (Do It Privately)

| Block | The Research | The Goal |
|-------|--------------|----------|
| **auth** | Zero-knowledge proofs, anonymous credentials | Prove who you are without revealing who you are. |
| **analytics** | Differential privacy | Know how many, not who. Math that guarantees privacy. |
| **compute** | Confidential computing, TEEs | Process data without seeing it. |
| **storage** | Oblivious RAM, encrypted indexes | Store and retrieve without leaking access patterns. |
| **sharing** | Secure multi-party computation | Share between parties without any party seeing everything. |
| **verify** | ZK proofs, selective disclosure | Prove you're over 18 without revealing your birthdate. |


---

## Roadmap

**Now:**
- Documentation
- Community (GitHub Discussions)
- Patterns for not doing things

**First block:**
- `auth`,  Zero-knowledge authentication

**Then:**
- `analytics`,  Differential privacy
- Everything else, one block at a time

---

## Contributing

We need:

- **Cryptographers** ,  review implementations, catch mistakes
- **Developers**,  turn papers into code, code into packages
- **Writers** , explain hard things simply
- **Researchers** , point us to what's possible
- **Skeptics** , tell us when "just don't track" isn't realistic

---

## Community

[GitHub Discussions](../../discussions)

Async. Focused. Where the code is.

---

## License

MIT. See [LICENSE](LICENSE).

---

## Links

- Website: [unchuchu.com/developers](https://unchuchu.com/developers)

---

*A lot of research is already done. The hard math is solved. What's left is engineering. Packaging. Documentation. Making it real.*

*That's the work.*
