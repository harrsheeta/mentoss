
# Setting Up Your Development Environment  

Follow these steps to set up your development environment efficiently:  

## 1️⃣ Install `uv`  
`uv` is a fast package manager for Python. Install it using:  
```sh
pip install uv
```

## 2️⃣ Set Up a Virtual Environment  
Create a virtual environment using `uv`:  
```sh
uv venv
```

## 3️⃣ Activate the Virtual Environment  
On macOS/Linux:  
```sh
source .venv/bin/activate
```
On Windows (PowerShell):  
```sh
.venv\Scripts\Activate
```

## 4️⃣ Install Python Dependencies  
Use `uv` to install the required Python dependencies:  
```sh
uv pip install .
```

## 5️⃣ Install Moccasin Dependencies  
Run the following command to install Moccasin dependencies:  
```sh
uv run moccasin install
```

Now you're all set! 🚀
