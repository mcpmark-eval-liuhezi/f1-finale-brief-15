# 2021 Formula 1 Season Finale — Abu Dhabi Grand Prix (Yas Marina) Research Brief

## Race Session
- **Event:** 2021 Abu Dhabi Grand Prix (Round 22 of the 2021 Formula 1 World Championship)
- **Circuit:** Yas Marina Circuit, Abu Dhabi, UAE
- **Session:** Race (Grand Prix race session)
- **Date:** 2021-12-12 (time 13:00:00Z as reported by the race calendar/results source)
- **Session key:** Not returned by the historical sessions lookup (getHistoricalSessions returned empty for all 2021 queries); the weather/telemetry endpoints in this source only serve 2023 sessions (e.g. 9157 = 2023 Italian GP, 9158 = 2023 Singapore GP). The race session is the Race session for Round 22 on 2021-12-12.
- **Result:** Max Verstappen won; Lewis Hamilton finished 2nd (+2.256s); Carlos Sainz 3rd (+5.173s). Verstappen took the title with the win (26 points, fastest lap 1:26.103 on lap 39, total time 1:30:17.345).

## Classified Race Results — Round 22, 2021 (Highlights)
| Pos | Driver | Team | Car # | Points | Time/Gap |
|-----|--------|------|-------|--------|----------|
| 1 | Max Verstappen | Red Bull | 33 | 26 | 1:30:17.345 (Fastest Lap 1:26.103, lap 39) |
| 2 | Lewis Hamilton | Mercedes | 44 | 18 | +2.256 |
| 3 | Carlos Sainz | Ferrari | 55 | 15 | +5.173 |
| 4 | Yuki Tsunoda | AlphaTauri | 22 | 12 | +5.692 |
| 5 | Pierre Gasly | AlphaTauri | 10 | 10 | +6.531 |
| 6 | Valtteri Bottas | Mercedes | 77 | 8 | +7.463 |
| 7 | Lando Norris | McLaren | 4 | 6 | +59.200 |
| 8 | Fernando Alonso | Alpine | 14 | 4 | +1:01.708 |
| 9 | Esteban Ocon | Alpine | 31 | 2 | +1:04.026 |
| 10 | Charles Leclerc | Ferrari | 16 | 1 | +1:06.057 |

## Podium in Finishing Order
1. **Max Verstappen** (Red Bull) — 26 pts
2. **Lewis Hamilton** (Mercedes) — 18 pts
3. **Carlos Sainz** (Ferrari) — 15 pts

## Driver Profiles (as returned by the profile lookup)

### Lewis Hamilton
- **Permanent number:** 44
- **Three-letter code:** HAM
- **Nationality:** British
- **Date of birth:** 1985-01-07
- **Profile link:** http://en.wikipedia.org/wiki/Lewis_Hamilton

### Max Verstappen (driverId: max_verstappen)
- **Permanent number:** 3
- **Three-letter code:** VER
- **Nationality:** Dutch
- **Date of birth:** 1997-09-30
- **Profile link:** http://en.wikipedia.org/wiki/Max_Verstappen

### Carlos Sainz (driverId: sainz)
- **Permanent number:** 55
- **Three-letter code:** SAI
- **Nationality:** Spanish
- **Date of birth:** 1994-09-01
- **Profile link:** http://en.wikipedia.org/wiki/Carlos_Sainz_Jr.

## Notes
- The driverId `verstappen` resolves to Jos Verstappen (1972-03-04, Dutch) in this data source; Max Verstappen's correct entry is `max_verstappen` (permanent number 3, code VER, Dutch, DOB 1997-09-30).
- The driverId `norris` returns permanentNumber "1" in this source (a data quirk); the actual permanent number for Lando Norris is 4, and he finished 7th in this race.
-Hamilton's permanent number and nationality as returned by the lookup: **44** and **British**.
