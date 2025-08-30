# Python
# Clone the project repository
git clone https://github.com/Tencent/Youtu-agent.git
cd Youtu-agent

# We use `uv` to manage the virtual environment and dependencies
# Create the virtual environment
uv venv

# Activate the environment
source .venv/bin/activate

# Install all dependencies, including development tools
uv sync --group dev

# Create your environment configuration file from the example
cp .env.example .env
