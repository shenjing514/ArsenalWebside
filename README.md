# ArsenalWeb

## Application Domain
This dynamic website is designed for Arsenal Football Club fans. It provides the latest news, player profiles, and match schedules. Users can explore player details and check upcoming matches. The website now includes the Arsenal logo displayed next to the title.

## Entity Types
1. **Players**
   - Attributes: Name, Position, Number, Photo, Biography
   - Relationships: Related Matches

2. **Matches**
   - Attributes: Opponent, Date, Location, Score
   - Relationships: Involved Players

## REST API Methods
### Players
- `GET /players`: Retrieve a list of all players (IDs and names)
- `GET /players/:id`: Retrieve details of a specific player, including related matches
- `POST /players`: Add a new player

### Matches
- `GET /matches`: Retrieve a list of all matches (IDs, opponents, and dates)
- `GET /matches/:id`: Retrieve details of a specific match, including scores and participating players
- `POST /matches`: Add a new match
