# azp-agent-linux

docker run -e AZP_URL="https://dev.azure.com/{yourdevops}" -e AZP_TOKEN="{token}" -e AZP_POOL="default" -e AZP_AGENT_NAME="Docker Agent - Linux" --name "azp-agent-linux" azp-agent:linux
