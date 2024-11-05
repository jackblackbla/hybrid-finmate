# Hybrid Finmate

High-performance hybrid financial platform combining the power of Rust and Python.

## 🏗 Architecture Overview
- **Rust**: High-performance core services and data processing
- **Python**: Data analysis, AI/ML capabilities
- **Hybrid Approach**: Best of both worlds

## 📂 Project Structure
```
hybrid-finmate/
├── rust/                      # Rust components
│   ├── core-utils/           # Common utilities
│   ├── examples/            # Rust examples
│   └── benches/            # Performance benchmarks
│
├── python/                  # Python components
│   ├── utils/              # Python utilities
│   └── examples/          # Python examples
│
└── examples/              # Integration examples
    └── rust_python_bridge # Rust-Python interop
```

## 🚀 Getting Started
### Prerequisites
- Rust (latest stable)
- Python 3.10+
- Cargo
- Poetry (Python dependency management)

### Building
```bash
# Rust components
cd rust
cargo build

# Python components
cd python
poetry install
```

## 📖 Documentation
- [Architecture Overview](docs/architecture/)
- [Integration Guide](docs/integration/)