
---

# 🎓 Turbin3 Q4 Registration Task

This is a small info about the task I did 🚀

---

## 🛠️ Prerequisites

- Install Rust: [Install Rust](https://www.rust-lang.org/tools/install)
- Install Solana CLI: [Install Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)

---

## 📝 Steps

### 1. 🗝️ **Create a New Keypair**

To begin, generate a new Solana keypair for use in development.

### 2. 🖥️ **Setting up the Environment**

- Open your terminal.
- Initialize a new Rust library:
  ```bash
  cargo init --lib
  ```
- Add **solana-sdk** to your `Cargo.toml`:
  ```toml
  [dependencies]
  solana-sdk = "1.15.2"
  ```
- Create the following functions in `src/lib.rs`:
  ```rust
  #[cfg(test)]
  mod tests {
      use solana_sdk;
      
      #[test]
      fn keygen() {}
      
      #[test]
      fn airdrop() {}
      
      #[test]
      fn transfer_sol() {}
  }
  ```

---

### 3. 🔑 **Generating a Keypair**

- Generate a new Solana keypair using the function:
  ```rust
  let kp = Keypair::new();
  ```
- Save the keypair in a JSON file for future use.

---

### 4. 💼 **Import/Export to Phantom Wallet**

Easily import or export your wallet to Phantom using keypairs.

---

### 5. 🔄 **Conversion Functions**

- Add **bs58** to your `Cargo.toml` to support Base58 encoding:
  ```toml
  bs58 = "0.4"
  ```
- Implement conversion functions to encode and decode between Base58 and wallet byte arrays.

---

### 6. 💧 **Claiming Token Airdrop**

- Add **solana-client** to your `Cargo.toml`:
  ```toml
  solana-client = "1.15.2"
  ```
- Import key modules:
  ```rust
  use solana_sdk::{signature::{Keypair, Signer}, system_instruction::SystemInstruction, pubkey::Pubkey, native_token::LAMPORTS_PER_SOL};
  ```
- Establish a connection to the Solana Devnet and claim 2 SOL tokens:
  ```rust
  client.request_airdrop(&keypair.pubkey(), 2 * LAMPORTS_PER_SOL);
  ```

- Check Signature: [here](https://explorer.solana.com/tx/5qTzBqvxjy1jX2ZESAmNEZzn934jbd3DQuEpQzYTsF3cxBcB8FAht97fjBSJWieqdMoophjahUEYJUSdiTAixs1t?cluster=devnet)

---

### 7. 💸 **Transfer Tokens to Turbin Wallet Address**

- Add **solana-program** to your `Cargo.toml` to handle transactions.
- Import necessary modules, and define the **Turbin3 public key**.
- Connect to the Devnet and execute a transaction to send some SOL to the Turbin3 Wallet Address.

- Check Signature: [here](https://explorer.solana.com/tx/5BSshDiiCNyz9gTfnqJZ7PpzaDz9ncMz1ikQFYYsE5pRRE6rxxZVHEPSrE1C3mhS3EKrPnZRWxepAwg3oBE1jeMZ/?cluster=devnet)

---

### 8. 🧾 **Empty Devnet Wallet into Turbin3 Wallet**

- Calculate the transaction fee.
- Transfer all remaining lamports (minus the fee) to the Turbin3 wallet.
- Broadcast and confirm the transaction.

- Check Signature: [here](https://explorer.solana.com/tx/3RvDzAQ976SWahPnZL9JcfdSZ4sKMoc7xb5EuQzmRcW4stV7MP8AtotSZsxD5kXPBV7uRBUw28W3dwEEcg4JCEJ/?cluster=devnet)

---

## 🧠 **Understanding PDA and IDL**

Learn about **Program Derived Addresses (PDA)** and **Interface Definition Language (IDL)** and explore them.

Don't forget to:
- Add **borsh** and **solana-idlgen** to `Cargo.toml`:
  ```toml
  borsh = "0.9"
  solana-idlgen = "1.0"
  ```
- In the `src` folder, create a `programs` folder and add the `mod.rs` and `Turbin3_prereq.rs` files to consume the IDL.

---

### Finally Enroll in the Turbin3 Program 📝🚀

After transferring the remaining balance, enroll yourself by submitting your GitHub username to the **Turbin3 program account** using the crates provided earlier.

- Check Signature: [here](https://explorer.solana.com/tx/5Ue7ktrcvYXydywUZg184RW64kccDKFQ54DbhdepR8RPA4PdnAA5ifKfBYnCbywZxm3LSsKWtzJJGuiG7BoXFTEX?cluster=devnet)

--- 
