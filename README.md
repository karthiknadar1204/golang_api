golang_api/
├── main.go              # Application entry point
├── go.mod               # Go module dependencies
├── controllers/         # HTTP request handlers
│   ├── controllers.go   # Core user/product operations
│   ├── cart.go         # Cart management operations
│   └── address.go      # Address management operations
├── database/           # Database operations
│   ├── databasetup.go  # MongoDB connection setup
│   └── cart.go         # Cart database operations
├── models/             # Data structures
│   └── models.go       # User, Product, Order, Address models
├── routes/             # API route definitions
│   └── routes.go       # Route handlers
├── middleware/         # HTTP middleware (currently empty)
│   └── middleware.go
└── tokens/            # JWT token management
    └── tokengen.go    # Token generation and validation
