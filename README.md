# index_range
allow syntax like:

for( auto i : Range( 1, 5 ) ) { /* ... */ }

for( auto i : Range( 1, 5 ) | Reverse() ) { /* ... */ }

for( auto i : Range( 1, 5 ) | Reverse() | Drop(3) ) { /* ... */ }

etc
