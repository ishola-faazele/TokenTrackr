# TokenTrackr 
- Subgraph repository: https://github.com/ishola-faazele/TokenTrackr-subgraph
- Web app link: https://tokentrackr.vercel.app/
- Web app repository: https://github.com/ishola-faazele/my-graphql-app
  
## Transfer Events Subgraph and Query Implementation
This project implements a subgraph for tracking transfer events on the Sepolia network and a React application for querying and displaying the data.

## Subgraph Implementation

### Features
- Simple event tracking entities for Transfer events
- Domain entities: Account and Token
- Best practices applied:
  - getOrCreate pattern for accounts
  - Bytes used as IDs
- Usage of Data Source Templates for dynamic contract tracking
- Schema best practices:
  - Enums used for TransferType
  - Interfaces (Metadata) implemented

### Testing
- Unit tests implemented using Matchstick

## Query Implementation

### Features
- Queries The Graph using Apollo Client
- Implements sorting and filtering
- Uses pagination (first 10 results)
- Implements logical operators in queries
- Uses Apollo for improved GraphQL querying
- Utilizes GraphQL variables for pagination

### UI Implementation
- React-based user interface
- Material-UI components for styling
- Tabbed interface for different query types
- Loading states and error handling

## Future Improvements

- Implement full-text search
- Add aggregations to the subgraph
- Publish the subgraph to The Graph Network
- Implement nested filtering in queries
- Query multiple subgraphs
