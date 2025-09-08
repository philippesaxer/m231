```mermaid
flowchart TD
    A[CNFans] -->|Sign in| B(Search for a spreadsheet)
    B --> C{Choose item}
    C -->|Option One| D[Pants]
    C -->|Option Two| E[T-Shirt]
    C -->|Option Three| F[Shoes]
    D --> G{Copy link}
    E --> G{Copy link}
    F --> G{Copy link}
    G --> H[Paste link to CNFans]
    H --> I{Choose Size & Color}
    I --> K[Not available]
    K --> C
    I --> J[Add to Cart]
    J --> |Forward to Payment| L{choose destination}
    L --> M[choose payment method]
    L --> N[Shipping not available to your destination]
    M --> |advance to confirmation|O[authentify yourself]
    O --> |If possible| P[Pay and finish your order]
   O --> |if not possible| Q[Try again]
   Q --> O
   ```
