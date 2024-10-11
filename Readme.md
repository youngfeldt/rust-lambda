

# Install nitro enclave cli
sudo amazon-linux-extras install aws-nitro-enclaves-cli -y
sudo yum install aws-nitro-enclaves-cli-devel -y
sudo usermod -aG ne root
sudo usermod -aG docker root
sudo usermod -aG wheel root


# Cert Service  - AWS Lambda
 
## Notes
 
init:
    @rustup target add x86_64-unknown-linux-musl
build:
 
