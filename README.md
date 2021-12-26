# personal_token
Creating Cryptocurrency using Solana CLI

# SPL token CLI
cargo install spl-token-cli

# Airdropping SOL
solana airdrop 1 {pub-key} --url https://api.devnet.solana.com

# Checking Balance
solana balance  --url https://api.devnet.solana.com

# Creating a token
spl-token create-toke --url https://api.devnet.solana.com

# Creating a account
spl-token create-account 8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 --url https://api.devnet.solana.com

# To check the balance of our token i.e. number of tokens that we have in our newly created account, run the following command.
spl-token balance  8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 --url https://api.devnet.solana.com

# Minting tokens
spl-token mint 8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 1000 --url https://api.devnet.solana.com

# Checking the supply
spl-token supply 8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 --url https://api.devnet.solana.com

# Limiting Supply
spl-token authorize 8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 mint –disable --url https://api.devnet.solana.com

# Buring tokens
spl-token burn <source token account address> <tokens to be burnt>

# Sending tokens
spl-token transfer 8qz75zYA6zrvzRwSBuHWTsjyAFLU1xnPAxNcZfgaKM64 100 <Token address> --url https://api.devnet.solana.com

CzTbpK6y48gWr7pjBQqP46J9VkPXuBBq8G7wXoMPStP1
