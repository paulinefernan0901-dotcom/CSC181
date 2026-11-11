**PRODUCT BACKLOG**

**CSC181  \|  TEAM PROJECT DOCUMENT**

**Team Information**

**•** Team name: FTF

**•** Project title: PiliPiliWais

**•** Primary user group for the first release: MSU-IIT Undergraduate Students	

**•** Format: \[User stories with one use case / Use cases with acceptance criteria\]

| Member | GitHub username | Personal CSC181 repository |
| :---- | :---- | :---- |
| Desmond Gold G. Bongcawel | cooky | https\://github.com/cooky922/CSC181 |
| Pauline N. Fernan | paulinefernan0901-dotcom | https\://github.com/paulinefernan0901-dotcom/CSC181 |
| Vince Ryan P. Dizon | Pintakasi | https\://github.com/Pintakasi/CSC181 |
| Sam Gabriel Benedict A. Laguda | sgblaguda | https\://github.com/sgblaguda/CSC181 |

**1\. Interview Summary**

| Code | Stakeholder role | Date | Method | Interviewer(s) |
| :---- | :---- | :---- | :---- | :---- |
| S1 | Undergraduate student (2nd year), boarding house resident | 2026-10-23 | In person, structured interview | Bongcawel |
| S2 | Undergraduate student (2nd year), boarding house resident | 2026-10-23 | In person, structured interview | Bongcawel |
| S3 | Undergraduate student (3rd year), boarding house resident | 2026-10-23 | In person, structured interview | Bongcawel |
| S4 | Undergraduate student (2nd year), boarding house resident | 2026-10-23 | In person, structured interview | Bongcawel |
| V1 | Sari-sari store vendor | 2026-10-25 | In person, structured interview (audio recorded) | Dizon, Fernan, Laguda |
| V2 | Sari-sari store vendor | 2026-10-25 | In person, structured interview (audio recorded) | Dizon, Fernan, Laguda |

**2\. From Interview Notes to Needs**

| ID | Source | What we heard or saw | Underlying need | Requirement idea | Type |
| :---- | :---- | :---- | :---- | :---- | :---- |
| F1 | S1 | Biggest budgeting challenge: "Walay time magpalit ug mas cheaper item, so I instead go to near shops for convenience." (No time to buy a cheaper item.) | Find cheaper options without spending extra time travelling between stores. | Search results show an item's price at each store on one screen. | F |
| F2 | S1, S2, S3 | Three of four students said they visit multiple stores to get the cheapest price for each item. S4 buys everything in one store for convenience. | Avoid checking store by store by hand. | Search results rank an item's prices from lowest to highest. | F |
| F3 | S1, S2, S3, S4 | All four noticed price differences for the same item across nearby stores: S3 said "significant", S1, S2, and S4 said "slight". | Know where the lowest price is, since differences exist. | Search results label an item's lowest price as "Lowest". | F |
| F4 | S2, S3, S4 | S2: "spontaneous hangouts can also lead to unexpected expenses." S3: "Dali ra mag crave (impulsive)." S4: trying not to get tempted and keeping to the budget set for a period. | Stay within a weekly budget despite unplanned spending. | An item basket (shopping list) shows the difference between its total and the budget the student entered. | F |
| F5 | S1, S2, S3, S4 | Willingness to walk for a cheaper price differs: S3 under 5 minutes, S1 5 to 10 minutes, S2 and S4 more than 10 minutes. | See only the stores that match how far each student is willing to walk. | A student can filter stores by walking time from campus. | F |
| F6 | S1, S2, S3 | Main reason for choosing a store includes product variety: "They almost have everything I need." | Know which items a store does not have before walking there. | Store recommendations list the items of the basket that a store has no price for. | F |
| F7 | V2 | Asked about changing prices themselves, V2 said "Pwede ra kung dili busy." (Fine if not busy.) and said they sometimes focus on selling and also look after an elementary student. | Change a price while spending as little time as possible away from customers. | A vendor can complete an item's price update within 30 seconds, from opening the update form to the saved confirmation. | Q |
| F8 | V1 | Asked about changing prices themselves, V1 said "Kapoy ra oy." (It is tiring.) | Changing a price must not feel slow or difficult during a store day. | Each vendor screen responds to a tap or input within 1 second on a mobile phone. | Q |
| F9 | V1, V2 | Vendors change prices themselves only when they are not busy (V2) and find it tiring (V1). | Students need to tell whether a price is still current, since vendors cannot always update it. | Each price shows the date it was last updated. | F |
| F10 | V1, V2 | V1 said they would take part "kung maka tabang sa mga estudyante" (if it helps students). V2 said they would take part "kung gamit siya" (if it is useful). | See a clear benefit before spending effort. | A vendor can create a store profile with the store's name, landmark, and walking time from campus. | F |
| F11 | V1, V2 | Reaction to price comparison was mixed. V1: "Ahh, bati mana." V2: "Pwede ra." and still fine if their store is the most expensive, "basta makita lang amoang tindahan" (as long as our store is seen), since most customers live nearby. | Prices shown for a store must be the store's own, so vendors are not misrepresented and students can rely on them. | Only a store's own vendor can add, change, or remove that store's prices. | C |
| F12 | V2, S1, S2, S3, S4 | V2's most bought items: coffee, Bear Brand, Milo, shampoo, and "delata" (canned goods). Students' top-5 lists repeat eggs (S1, S2, S4), water gallon (S1, S2, S4), and cooked meal (S2, S3). | A starting item list that matches what is sold and bought. | The first release covers a fixed list of 10 items. | C |

**Assumption log**

| ID | Assumption | Risk if wrong (High/Medium/Low) | How we will check it |
| :---- | :---- | :---- | :---- |
| A1 | Prices posted by the vendors themselves are credible: vendors post honest prices, and students trust them. Because of this, only vendors can post prices. | High | Compare posted prices with the shelf prices at five stores, and ask students in the walk-through whether they would rely on a price posted by the store itself. |
| A2 | Vendors will keep their prices current, even though V1 called updating "tiring". | High | Time how long a vendor takes to update a price in a prototype, and ask more vendors if that time is acceptable. |
| A3 | Prices of the same item differ enough between nearby stores to matter. Three of four students called the differences "slight". | High | Collect prices of the 10 items from at least five stores near the campus and compute the differences. |
| A4 | Students will keep using the app after they learn which stores are cheapest. | High | During testing, ask students whether they would still open the app after one month of use. |
| A5 | Students use the app on a phone with mobile data while being busy. | Medium | Ask a short question in the walk-through about how and where students would use it. |

**3\. User Stories**

| ID | User story | Source finding(s) | Epic | INVEST check |
| :---- | :---- | :---- | :---- | :---- |
| US-01 | As a student with a limited budget, I want to search for an item and see its price in each nearby store, so that I can find where to buy it without visiting several stores. | F1, F12 | Price search and comparison | Yes |
| US-02 | As a student with a limited budget, I want an item's prices ranked from lowest to highest, so that I can pick the cheapest store at a glance. | F2, F3 | Price search and comparison | No |
| US-03 | As a student with a limited budget, I want to filter stores by walking distance from campus, so that I only see stores within the walk I am willing to make. | F5 | Price search and comparison | No |
| US-04 | As a student with a limited budget, I want to see the date each price was last updated, so that I can tell whether a price is still current. | F9 | Price search and comparison | No |
| US-05 | As a student with a limited budget, I want to browse the list of supported items, so that I know what I can look up. | F12 | Price search and comparison | No |
| US-06 | As a student with a limited budget, I want to build an item basket (shopping list) with quantities, so that I can plan my purchases before going to a store. | F4, F6 | Item basket and budget | No |
| US-07 | As a student with a limited budget, I want to compare my list's total with a budget I set, so that I know if I am going over before I buy. | F4 | Item basket and budget | No |
| US-08 | As a student with a limited budget, I want stores ranked by the total cost of my whole list, so that I can pick the store that fits my budget. | F2, F4, F6 | Item basket and budget | No |
| US-09 | As a student with a limited budget, I want to see each ranked store's walking time beside its list total, so that I can weigh a lower total against a longer walk. | F5, F2 | Item basket and budget | No |
| US-10 | As a sari-sari store vendor, I want to add an item's price to my store, so that students can see what I charge. | F10, F11 | Store and price data | No |
| US-11 | As a sari-sari store vendor, I want to update an item's price within 30 seconds, so that updating does not take time away from serving customers. | F7, F8, F11 | Store and price data | No |
| US-12 | As a sari-sari store vendor, I want to create a store profile with my store's location, so that students near the campus can find my store. | F10 | Store and price data | No |
| US-13 | As a sari-sari store vendor, I want to remove an item I no longer sell, so that students do not see a price I cannot honor. | F9, F11 | Store and price data | No |

**Epics and how we split them**

| Epic | Split into | How we split it |
| :---- | :---- | :---- |
| Price search and comparison | US-01, US-02, US-03, US-04, US-05 | By workflow step (find an item, compare, narrow the results), and by data type (price, distance, date). |
| Item basket and budget | US-06, US-07, US-08, US-09 | By workflow step (build the list, set a budget, get a store recommendation, weigh distance). Happy path first. |
| Store and price data | US-10, US-11, US-12, US-13 | By workflow step (create the profile, add a price, update it, remove it), and by business rule (only a store's own vendor changes its prices). |

**Stories we rewrote**

**1\.** Before: "As a student, I want to compare prices, so that I save money."

> **After:** US-01 (search an item and see its price in each nearby store) and US-02 (rank an item's prices from lowest to highest).

> **Reason:** The original was not Small or Testable. "Compare" and "save money" could mean many things and could not be checked.

**2\.** Before: "As a vendor, I want to manage my store in the app, so that students can find me."

> **After:** US-10 (add a price), US-11 (update a price), US-12 (create a store profile), and US-13 (remove an item).

> **Reason:** The original was too big (not Small), and "manage" was too vague to estimate (not Estimable).

**3\.** Before: "As a student, I want to enter a budget and see my list total against it."

> **After:** US-07 (compare my list's total with a budget I set).

> **Reason:** The original joined two actions with "and", which breaks the one-thing-per-story quality on Week 4, slide 11\.

**4\.** Before: "As a student, I want to submit a price I saw in a store, so that other students see up-to-date prices."

> **After:** removed. Vendors post their own prices in US-10 and US-11 instead.

> **Reason:** The team decided that only vendors post prices, because vendor-posted prices are more credible. Keeping the student story would contradict F11 (Consistent).

**5\.** Before: "As a vendor, I want to update an item's price in a few taps."

> **After:** US-11 (update an item's price within 30 seconds).

> **Reason:** "A few taps" was not Testable or Estimable, and the real need in F7 is the vendor's time away from customers.

**4\. Acceptance Criteria**

**US-01: Search an item and see prices**

**Acceptance criteria**

☐  Entering the name of one of the 10 supported items lists each store that has a price for it, with the store name and the price in pesos.

☐  Searching "Eggs", "eggs", and "EGGS" returns the same results.

☐  Results appear within 2.5 seconds when the app holds prices from at least 5 different stores.

☐  (unhappy) If the item has no price records, the app shows "No prices yet for \[item\]" and no store rows.

☐  (unhappy) If the text does not match a supported item, the app shows "Item not found" and the list of supported items.

**Scenario 1: Normal case**

Given eggs have a price of ₱9 at Store A, ₱10 at Store B, and ₱8 at Store C  
When the student searches "eggs"  
Then the results list Store A with ₱9, Store B with ₱10, and Store C with ₱8

**Scenario 2: No prices recorded**

Given no price records exist for milk  
When the student searches "milk"  
Then the app shows "No prices yet for milk" and lists no stores

**US-02: Prices ranked from lowest to highest**

**Acceptance criteria**

☐  Results are sorted from lowest to highest price by default.

☐  The lowest price is labelled "Lowest".

☐  Each other price shows how many pesos it is above the lowest, for example "+₱1".

☐  Stores with the same price are ordered alphabetically by store name.

☐  (unhappy) If only one store has a price, the app shows that store with "Only one store has a price" and no comparison difference.

**Scenario 1: Normal case**

Given eggs have a price of ₱9 at Store A, ₱10 at Store B, and ₱8 at Store C  
When the student views the eggs results  
Then the order is Store C ₱8 (Lowest), Store A ₱9 (+₱1), Store B ₱10 (+₱2)

**Scenario 2: Only one price**

Given only Store A has a price for rice  
When the student views the rice results  
Then Store A is shown with "Only one store has a price" and no "Lowest" label or difference

**US-03: Filter stores by distance**

**Acceptance criteria**

☐  Each store in the results shows its walking time from campus in minutes and estimated distance in meters.

☐  The student can filter by walking distance, and only stores at or under the chosen limit are shown.

☐  (unhappy) If no store within the chosen limit has a price for the item, the app shows "No stores within \[distance\] m / km have prices for \[item\]" and offers the next limit.

**US-04: Last-updated date**

**Acceptance criteria**

☐  Each price shows the date it was last updated, for example "Nov 11, 2026".

☐  A price not updated in the last 14 days is labelled "Outdated".

☐  (unhappy) A price record with no date shows "Date unknown" instead of a blank.

**US-05: Browse supported items**

**Acceptance criteria**

☐  The home screen lists atleast 10 items by name.

☐  Selecting an item opens the same results as searching its name.

☐  (unhappy) An item with no price records is still listed and opens "No prices yet for \[item\]".

**US-06: Build an item basket**

**Acceptance criteria**

☐  A student can add any of the 10 supported items to the list with a whole-number quantity from 1 to 99\.

☐  A student can remove an item, and the list updates within ms.

☐  (unhappy) Adding an item already on the list shows "Already on your list" and does not add a second row.

☐  (unhappy) A quantity of 0, a negative number, a decimal, or a blank is rejected with "Enter a quantity from 1 to 99".

**Scenario 1: Normal case**

Given the item basket is empty  
When the student adds eggs with quantity 6  
Then the list shows one row, "Eggs x 6"

**Scenario 2: Duplicate item**

Given the item basket contains "Eggs x 6"  
When the student adds eggs again  
Then the app shows "Already on your list" and the list still has one eggs row

**US-07: Compare the list total with a budget**

**Acceptance criteria**

☐  A student can enter a budget as a whole number of pesos from ₱1 to ₱10,000.

☐  The app shows the list total, using the lowest known price for each item, and the amount remaining or over budget.

☐  The total updates when an item or quantity changes.

☐  (unhappy) A budget that is blank, zero, negative, or not a number is rejected with "Enter a budget in pesos".

☐  (unhappy) If a listed item has no price, the app leaves it out of the total and shows "No price for \[item\], not included in total".

**Scenario 1: Within budget**

Given the list is "Eggs x 6" and the lowest egg price is ₱8  
When the student enters a budget of ₱100  
Then the app shows a total of ₱48 and ₱52 remaining

**Scenario 2: Over budget**

Given the list is "Eggs x 6" and "Rice x 1", the lowest egg price is ₱8, and the lowest rice price is ₱60  
When the student enters a budget of ₱100  
Then the app shows a total of ₱108 and "₱8 over budget"

**US-08: Stores ranked by list total**

**Acceptance criteria**

☐  The app ranks the stores that have a price for each item on the list, from lowest to highest total.

☐  Each ranked store shows its total and either "Within budget" or "Over by ₱\[amount\]".

☐  Stores missing a price for any list item are shown in a separate "Missing items" section with the names of the missing items, and are not ranked.

☐  (unhappy) If no store has a price for each list item, the app shows "No single store has every item on your list" and still lists each store with its missing items.

**Scenario 1: Normal case**

Given the list is "Eggs x 6" and "Rice x 1", and the budget is ₱115  
And Store A charges ₱9 for eggs and ₱60 for rice  
And Store B charges ₱10 for eggs and ₱55 for rice  
And Store C charges ₱8 for eggs and has no rice price  
When the student opens the store recommendations  
Then Store A is ranked first with ₱114 (Within budget)  
And Store B is ranked second with ₱115 (Within budget)  
And Store C appears under "Missing items: rice"

**Scenario 2: Stores over budget**

Given the same list and prices as above, and the budget is ₱100  
When the student opens the store recommendations  
Then Store A shows ₱114 (Over by ₱14) and Store B shows ₱115 (Over by ₱15), in that order

**US-09: Walking time beside list total**

**Acceptance criteria**

☐  Each ranked store shows its walking time from campus beside its total.

☐  The student can sort ranked stores by total or by walking time.

☐  (unhappy) A store with no walking time recorded shows "Distance not set" and is placed last when sorted by walking time.

**US-10: Vendor adds an item's price**

**Acceptance criteria**

☐  A signed-in vendor can add a price for one of the 10 supported items to their own store.

☐  The price must be a number greater than ₱0 and at most ₱9,999.99, with at most 2 decimal places.

☐  The app records today's date with the price, and the store appears in that item's results.

☐  (unhappy) A price that is blank, zero, negative, or not a number is rejected with "Enter a price greater than ₱0" and nothing is saved.

☐  (unhappy) An item already priced at the store is rejected with "Already listed. Update the price instead" and no second row is added.

☐  (unhappy) A student account, or a user who is not signed in as a vendor, is blocked from the add-price form with "Only store vendors can post prices".

☐  (unhappy) A price that differs by more than 50% from the median price of that item across stores asks "This price is far from other stores. Confirm?" and is saved only if the vendor confirms.

**Scenario 1: Normal case**

Given a vendor is signed in to Store A, eggs are not yet priced at Store A, and the median egg price is ₱9  
When the vendor adds eggs at ₱9.50  
Then the price is saved with today's date and Store A appears in the eggs results at ₱9.50

**Scenario 2: Student tries to post a price**

Given a student is signed in and is not the vendor of any store  
When the student opens the add-price form  
Then the app shows "Only store vendors can post prices" and no form is shown

**US-11: Vendor updates a price within 30 seconds**

**Acceptance criteria**

☐  In 5 test runs on a mobile phone, each price update takes 30 seconds or less, measured from opening the update form to the saved confirmation.

☐  Each tap or input on the update form gets a visible response within 1 second on a mobile phone.

☐  Saving an update changes only that item's price and date, and the results show the new price with today's date.

☐  (unhappy) A price that is blank, zero, negative, or not a number is rejected with "Enter a price greater than ₱0", and the old price stays.

☐  (unhappy) If the save fails because there is no connection, the app shows "Not saved. Check your connection and try again", and the old price stays.

☐  (unhappy) A vendor who tries to edit another store's price is blocked with "You can only edit your own store".

**Scenario 1: Normal case**

Given a vendor's store lists eggs at ₱9  
When the vendor sets eggs to ₱10 and saves  
Then the results show eggs at ₱10 with today's date, and ₱9 is no longer shown as current

**Scenario 2: No connection**

Given a vendor's store lists eggs at ₱9 and the device has no connection  
When the vendor sets eggs to ₱10 and saves  
Then the app shows "Not saved. Check your connection and try again", and eggs remain at ₱9

**US-12: Vendor creates a store profile**

**Acceptance criteria**

☐  A vendor can create a profile with a store name (2 to 50 characters), and store’s location..

☐  After saving, the store name, landmark, and walking time are shown with each price the store posts.

☐  (unhappy) A missing required field is rejected with an error that names the field.

☐  (unhappy) A walking time of 0, a negative number, a decimal, or more than 60 is rejected with "Enter a walking time from 1 to 60 minutes".

☐  (unhappy) A store with the same name and landmark as an existing store is rejected with "Store already exists".

**Scenario 1: Normal case**

Given a signed-in vendor has no store profile  
When the vendor saves a profile with the name "Store A", the landmark "near the campus gate", and a walking time of 6 minutes  
Then the profile is saved and "Store A, near the campus gate, 6 minutes" is shown with each price the store posts

**Scenario 2: Duplicate store**

Given a store named "Store A" near the campus gate already exists  
When another vendor saves a profile named "Store A" with the landmark "near the campus gate"  
Then the app shows "Store already exists" and no profile is saved

**US-13: Vendor removes an item**

**Acceptance criteria**

☐  A vendor can remove an item from their own store after confirming "Remove \[item\] from \[store\]?".

☐  After removal, the next search for that item no longer lists the store.

☐  (unhappy) If the vendor cancels the confirmation, the item and its price stay.

☐  (unhappy) A vendor who tries to remove an item from another store is blocked with "You can only edit your own store".

**5\. Quality Requirements and Constraints (EARS)**

| ID | Requirement | EARS pattern | Type | Source | Number agreed with |
| :---- | :---- | :---- | :---- | :---- | :---- |
| NFR-01 | When a student searches for an item, the system shall display the price comparison within 2 seconds | *Event-driven* | *Quality* | F1, F2 | N/A |
| NFR-02 | When a vendor opens an item’s price update form, the system shall let the vendor complete the update, through to the saved confirmation, within 30 seconds.  | Event-driven | *Quality* | F7 | N/A |
| NFR-03 | The system shall list every vendor’s price for an item in the comparison results, including when it is not the lowest price. | Ubiquitous | Quality | F2, F11 | N/A |
| NFR-04 | When a vendor taps or enters input on any vendor screen, the system shall respond within 1 second on a mobile phone.  | Event-driven  | Quality | F8 | N/A |
| NFR-05 | The system shall allow only a store’s own vendor to add, change, or remove that store’s prices.  | Ubiquitous | Quality | F11 | N/A |

**6\. Use Case**

**Use-case diagram**

![][image1]

**UC-01: Find cheapest store for item basket**

| Field | Description |
| :---- | :---- |
| **Primary actor** | Registered user |
| **Precondition** | User is logged in and has added items to their item basket |
| **Main success scenario** | 1\. Users open their item basket. 2\. The user presses “Find cheapest store”. 3\. The system gets the price of each listed item from every store that has it. 4\. The system shows the stores that have every listed item, ranked by total price for the whole list, with the cheapest first.  5\. Users select a store and view its location. |
| **Extensions** | 1a. Item basket is empty: system shows “Your basket is empty” and offers the user to search for the items they need to buy. 3a. No store carries every item: the system shows “No single store has every item on your list” and lists each store with its missing items, without ranking any of them.  3b. Network fails: system shows “Can’t load prices, check your connection” and keeps the basket as it was. 4a. Two stores have the same total: the system shows both at the same rank. |
| **Postcondition** | Users know which stores have the lowest total for their list and where to find them. |
| **Stories covered** | US-06, US-08, US-09  |

**7\. Story Map**

|  | Find an item | Compare prices | Plan an item basket | Stores supply prices |
| :---- | :---- | :---- | :---- | :---- |
| Release 1 (MVP) | US-01 | US-02 | US-06, US-08,  | US-10, US-11, US-12, US-13 |
| Release 2 |  |  | US-09 |  |
| Later | US-05 | US-03, US-04 | US-07 |  |

**8\. The Ordered Backlog**

| Rank | Story | MoSCoW | Size (S/M/L) | Value / effort quadrant | Sprint |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | US-12 — Vendor creates a store profile | Must | S | Quick win | Sprint 1 |
| 2 | US-10 — Vendor adds an item's price | Must | M | Big bets | Sprint 1 |
| 3 | US-01 — Search an item and see prices | Must | M | Big bets | Sprint 1 |
| 4 | US-02 — Prices ranked from lowest to highest | Must | S | Quick wins | Sprint 1 |
| 5 | US-13 — Vendor removes an item | Must | S | Quick Wins | Sprint 1 |
| 6 | US-11 — Vendor updates a price within 30 seconds | Must | M | Big bets | Sprint 1 |
| 7 | US-06 — Build an item basket | Must | M | Big bets | Sprint 2 |
| 8 | US-08 — Stores ranked by list total | Must | M | Big bets | Sprint 2 |
| 9 | US-04 — Last-updated date | Must | S | Quick Wins | Sprint 2 |
| 10 | US-09 — Walking time beside list total | Should | S | Fillers | Sprint 2 |
| 11 | US-07 — Compare the list total with a budget | Should | M | Big bets | Later |
| 12 | US-03 — Filter stores by walking time | Should | S | Fillers | Later |
| 13 | US-05 — Browse supported items | Could | S | Quick wins | Later |

**How we ordered it**

Nothing can be searched or compared until vendors have a store and prices in the system, that’s why US-12 and US-10 come first. US-01 and US-02 follow because they deliver the core student value (F1, F2, F3); finding the cheapest store for an item. US-11 is in Sprint 1 because assumption A2 (vendors will keep the prices current) is high-risk, and testing the 30-second update early in the process shows whether the product works at all. The shopping list stories (US-06, US-08, US-09) build on the search results, so they go in Sprint 2\. 

**Capacity check**

| Question | Answer |
| :---- | :---- |
| **How many Must-have stories, and their total size?** | 6 stories: 2 S and 4 M (10 size units if S \= 1 and M \= 2). |
| **Do the Must-haves fit in about 60% of our time for two sprints?** | Yes since we consist of 4 members and have access to AI agents.  |
| **Do the Release 1 stories form one complete path through the core workflow?** | Yes. A vendor creates a profile and posts prices; a student searches and compares, builds a list, and views store totals and walking time. |
| **Are all L-sized Must-have stories split?** | Yes |

**9\. Definition of Done**

**☐** Every acceptance criterion for the story passes, including each unhappy-path criterion and the Given-When-Then scenario.

**☐** All Must in the category backlog are implemented and passes unit test.

**☐** The feature is tested on a mobile phone, and any performance numbers in the criteria (1,3 or 30 seconds) are measured

**☐** Invalid input, unavailable data, and relevant permission or save failures show the specified user-facing feedback and do not leave incorrect data saved.

**☐** The code is reviewed and approved by at least one other team member through a pull request before merging to the main branch.

**☐** The change is merged to the main branch with no known open bugs, and the GitHub issue is closed with a link to the pull request.

**10\. Traceability Table**

\[One row per Must-have story. See Week 4, slide 30\. You will add test case IDs

in Week 9.\]

| Story | Problem or goal it addresses | Source finding(s) | Test cases (Week 9\) |
| :---- | :---- | :---- | :---- |
| US-12 | Help students identify a participating store and where it is located. | F10 | \[Leave blank for now\] |
| US-10	 | Let students see a store's own prices while preventing store misrepresentation. | F10, F11 | \[Leave blank for now\] |
| US-01 | Find cheaper options without travelling between stores. | F12 | \[Leave blank for now\] |
| US-02 | Know where the lowest price is without checking store by store | F2, F3 | \[Leave blank for now\] |
| US-08	 | Help students compare the cost of a complete shopping list across stores. | F2, F4, F6 | \[Leave blank for now\] |
| US-06 | Help students plan quantities and account for unplanned spending. | F4, F6 | \[Leave blank for now\] |

Gaps found: None

**11\. Validation**

**Team review**

\[Record at least two problems the team found using INVEST, the quality

checklist on Week 4, slide 11, and the common mistakes on slide 32.\]

| Problem found | Story or requirement | How we fixed it |
| :---- | :---- | :---- |
| *E-Estimable Needs to clarify how nearby stores are Identified* | *US-01* | *\[Fix\]* |
| *\[Problem\]* | *\[ID\]* | *\[Fix\]* |

**Stakeholder walk-through**

\[Show the story map and the top of the backlog to at least one stakeholder you

interviewed. See Week 4, slide 31.\]

| Stakeholder | Date | What they said | What we changed |
| :---- | :---- | :---- | :---- |
| V2, sari-sari store vendor | 2026-10-25 |  | \[Change\] |
|  |  |  |  |

**12\. Open Questions for Sprint 1**

1.How will students verify that the prices they see are accurate?

2.How do we ensure that a user registered as a store owner is legitimate and uploads accurate product prices?

3\. How do we find the lowest store to buy the items in the user’s basket if we can’t find a store that has all the items in the basket ?

4\. Should users be notified when a vendor changes a product's price?

 

**13\. Member Contribution Record**

| Member | Interviews or analysis | Stories, criteria, or use case | Review or validation |
| :---- | :---- | :---- | :---- |
| Desmond Gold C. Bongcawel | Interviewed students S1, S2, S3, and S4 on 10/23/2026 | Worked on section 2, 3, and 4 | Reviewed and validated each section as well as the whole paper |
| Pauline N. Fernan | Interviewed vendors V1 and V2 on 10/25/2026 | Worked on section 5, 6, and 7 | Reviewed and validated each section as well as the whole paper |
| Vince Ryan P. Dizon | Interviewed vendors V1 and V2 on 10/25/2026 | Worked on section 11, 12, and created the use-case diagram  | Reviewed and validated each section as well as the whole paper |
| Sam Gabriel Benedict A. Laguda | Interviewed vendors V1 and V2 on 10/25/2026 | Worked on sections 8, 9, and 10 | Reviewed and validated assigned sections as well as the whole paper. |

**14\. References**

* CSC181 Week 3 Lecture slide — Stakeholders, problem framing, scope, and feasibility  
* CSC181 Week 4 Lecture slide — Requirements, user stories, use cases, and acceptance criteria

**15\. Team AI Use Declaration**

Select one option:

**☐**  No generative AI tools were used by any member in preparing this submission.

**☐**  One or more members used generative AI tools. Details are provided below.

*\[If AI was used, complete the table. If not, write Not applicable.\]*

| Member who used AI | Tool | Purpose and sections assisted | How output was checked or revised |
| :---- | :---- | :---- | :---- |
| *\[Name\]* | *\[Tool\]* | *\[Purpose/sections\]* | *\[Review process\]* |

**Main prompts or interaction summary**

\[Provide the main prompts or a clear summary of the assistance received.

Write Not applicable if no AI tools were used.\]

We acknowledge that AI-generated suggestions are not evidence of actual

stakeholder interviews, feedback, or verified user needs. Every finding in

Section 2 and every walk-through in Section 11 comes from a real person we

spoke to or observed. We remain responsible for the accuracy and

explainability of this submission.

**16\. Team Confirmation**

We confirm that this document reflects our team's agreed-upon product backlog. All members

listed below reviewed the final version, and each member will upload the same

Markdown file to their personal CSC181 repository.

| Member | Reviewed final version |
| :---- | :---- |
| Desmond Gold C. Bongcawel | Yes |
| Pauline N. Fernan | Yes |
| Vince Ryan P. Dizon | Yes |
| Sam Gabriel Benedict A. Laguda | Yes |

**Submission Checklist**

**☐**  Interviews cover at least two stakeholder groups, with sources coded and no personal information.

**☐**  The needs table has at least 8 findings, each labelled F, Q, or C.

**☐**  Assumptions are recorded separately from evidence.

**☐**  There are 10 to 15 user stories, each with a real role, a "so that", and at least one finding.

**☐**  Epics are split, and at least two rewrites are recorded.

**☐**  Every story has at least 3 acceptance criteria, including an unhappy path, with no weak words.

**☐**  Every Must-have story has at least 2 Given–When–Then scenarios.

**☐**  At least 3 quality requirements or constraints use EARS patterns.

**☐**  One use case has a diagram, a main success scenario, and at least 2 extensions.

**☐**  The story map has a Release 1 line that crosses every journey step.

**☐**  Every story has a MoSCoW label and a size, and the backlog is in one order with no ties.

**☐**  Must-haves fit in about 60% of capacity. Won't-have stories are kept, not deleted.

**☐**  A Definition of Done is included.

**☐**  The traceability table covers every Must-have story.

**☐**  The team review and the stakeholder walk-through are recorded.

**☐**  Contributions, references, and AI use are declared.

**☐**  All members reviewed the same final document.

**☐**  Each member saved the file as activities/product-backlog.md, with images in activities/backlog-images/.

**☐**  Each member committed and pushed their copy to their personal repository.

**☐**  Each member submitted their own GitHub file link through MOLE before November 9, 2026 23:59:59.

[image1]: <data:image/png;base64,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Xn/QQKxOVA85LSI4Mg6/gFx++eUJfZXh/eg77g3q7sTl008/zfT8GDduXPT4448Pec1vvvkmsd0ggFidqB5yWkRwZBw2glQh4LYXXnzxRX3PKWHJ56WXXtroMfyf/OlPf0pskxe77757tGDBgsaxTJs2LbFNXUGsTlQPOS0iODIOv8SxWH2dQBTf0pr4rMr777/fc2HArLjhhhsax/e3v/0tMV43EKsT1UNOiwiOjMNvo+XLl0dvvvlmQt+KtH9oV199dUJHbAS3e+65Z2IsS3h/vE+rH3SYWfFy8803J8bLBr2rfvzxR3e899xzT2K8Lsgu1QM5LSI4Mg4bP4MpU6Yk9K3gqjz++NFHH43mzJnj7hNoef3110czZsxoZCCNHz8+euGFF9z9p556yt0efvjhjedTY+W5556Ltt9+e/d4yZIl7vl23+eff767veaaa1wlXkr9x4+jHQR36rseykMPPeQ+k0WLFiXGyg6Os5dhw4YlxquOztV6IKdFBGfQjQPdlhGyPuxYK+JOC+mu3PInsvXWW0d33323e7x69erGTAtxCX77l19+2d3GnZYHHnjA3SL8kfrn230/++yz7jHLF93GWvjic8ok2ogXMnzsWJXAqe32/K0CiNWJ6iGnRQRnEI0DAY0///yzy9QYNWqUa3J41113JbZrRdxpYR/cbrnllm7qntgDHsedltmzZyeeG3dabrrpJneL0GzRP9/u28cy9OK08P54n7vttpurEUJqbfwYBonzzjuv43n/7bffNu5///33ifF+IP35rLPOaixJdrM02YzTTz/dvR/elx2rKp2+H1EN5LSI4NTdOBA78swzz7g/IRwUOw7bbrttX58DMyE4Ftzfb7/93C29iux2v//97xM6zxFHHOFu/X788+P7/t3vfhdtscUWieemAeF9Wj34paNuHLeqwrJamu/6nXfecSnOX3zxRfTZZ585HY4jt0ceeWRjHz/99FPjORs2bGgs4VE0ju8O55PHtroyzS79sh9OC/v25yffwyeffOLu+9eh5k78+c1I876qQp3eyyAjp0UEp47G4bTTTovWrVvnUlcPOOCAxHgzKBDm/5z64aSTToquu+66hL4buolVSQPvi/dn9c0499xz3Tlx3333JcbqAMJsk9VbcFqYKbvwwgvd58dzjjrqqGjTTTd1s2V+9oVbZjh23XVXd//KK690+l122cU5Lc2cVx+Ezb7o0o3TEu8UznKhd1riTlEnOMZly5Yl9FWkjnZpEJHTIoJTF+PAEgxy5513JsbSgjz44IMJfZXh/fT6HbM89eWXX0Ynn3xyYqyKkB2U9rPAafH3cVpwMD744IPo1ltvdbMncacFh+W1115z4+hWrlwZXXzxxdFee+3litERx3TVVVc19ocjzRIfpf95jHONI7N27VrXfgGdd1oI5n733XcTx9eKtO+v7NTlfQw6clpEcKpsHPhjYEo+VFfj4cOHu8+DoFc7VkXIVEJ4X3asG8hOWbhwofusmcWy41UBufbaaxP6kIwcOdIt5eDE2LE8QHpdQiwTVbZL4hfktIjgVMk4bLXVVo2ZA9J+7XgoED/NX1W8WH2/0Etn/vz5boaBZoF2vMwgRx99dEJfJxCWsay+amRx7or8kdMiglN240CGyxtvvOGm02k4Z8ez4NBDD934j/9/QvExO15mCOJE3n777cRYFuBEkok1YsSIxFjZQGhWaPV1ArnxxhsbdYGqCmJ1onrIaRHBKaNxuOSSS9xxUYNihx12SIznxeLFi91xEAy5xx57JMbLxC233OKOFfnDH/6QGM+a448/3sV+sCTFEokdLwPUvSFrx+rrRPz3/Morr0SXXnppYpsqEH8forrIaRHBKYtxmDRpkvvTK2P2A0XdvMybNy8xXiQcj5eyLH1wHGQrUVdmxx13TIwXCWJ1/UCmF3EyaeNIOMdJh7b6UPgUa49vU0BQsN22zIT+nkQxyGkRwSnSOFBUDQmd4psVJ554olsK8eIr1ubJPvvs417XC8djtykT1DThj/T55593acB2PG/ov4RYfa/4An2+bxH9gObOneuWy6jzQm0dUuB91eOZM2c6p4XgaGalSHm2++yVdu+LYHWWWK2+rLR7L6I6yGkRwcnTOFC3YunSpdFXX30V/fnPf06MVwlqeJAO7IX79AsKWSafpTEq3z799NON1/Gv1awZY9k57LDDXErvZZddlhjLEyRNrZY0xKsK812RGs19gmF9pdt4UTo/00K7Bt9rKgSvv/66e19WbyGNnbRtqy8bad6LKD9yWkRwsjYO9HbBQFM63nc4rht29sPKN99848rmM9tARdbbb7/dpcVSwI2y/RQgY5ztmsl7773nir7Z160yVINF4vVL8gShkaXVd4t3WnDIiMWKj+G0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iCqCWF3WUFJgxowZjce+YanP9vMwS4lj8/TTT7vHdFwnBo5Z4lNPPbWQYy8rclpEcMr6AyvrcbWCZSMyedoJtWBIUyZb56yzznKZRePGjXPZQQTebrLJJtE222zjsn+YcaKLNNWDr7jiiujmm2+O/vGPf7glqmZCJtGdd96Z6CItRBVBrC5rbrjhhsZ9fntArJ11Wj7//HN3y8XJUUcdlTjW77//PrHvQUVOiwiO/cGViTIfW1q23nprNxPCFdxbb7210cPoQehKTXAwqc0nnXSSKzJnX0uIuoBYXdaQQYcTEtdxMWKdln/9618Np8aXI7jjjjsazoqcll+Q0yKCU4Rx6IayH58QIjxF/e6pVXTEEUdEm2++ebRo0aLo0EMPddWpiRFDzzZffvmlu2XGdMSIEdF7773nHvtK16p39AtyWkRwijIO3XDfffc5o2H1Qoh6UgW7JDojp0UEpyrG4bHHHov22GOPhF4IUT+qYpdEe+S0iOBUyThQAn/bbbdN6IUQ9aJKdkm0Rk6LCE7VjAN9e8iysXohRH0IYZfI5qOv16677trQ+SalvUIfMavrB5a+++kwX3bktIjghDAOeUN9FKsTQtSHfu0SGXtk9lA+YPLkyQ19Fpk948ePT+jSQoNTblesWJEYqwNyWkRw+jUORfHFF18kdEKIetCvXfrhhx/cbSunBTnyyCNdrByPKQxJbaTly5c7PZVxee6jjz7qHCAKx/kK06NHj47OOecclxxAhtG0adPcPihD8Ne//tVlHPH422+/bdR+ocYS+6N0AY8//vhjV7zOH4+v/VI35LSI4PRrHIrk559/TuiqCqmTFLLad999ndHjlsd0wLbbClF3+rVL/vntnBZuJ0yY4G4vv/zyhp4lIHjooYeGHId3WkiHxvm45pprnN47Lffee2/juaRJ47Sgp9bLypUrnX79+vXud3322We7MZwlv2//OnVCTosITvxHWUWuuuqqhK5oqJR55plnuiq2S5cudeX0sxT2z+vweryuL3glRFVBrK4b4s/HmbB6f+udFu942Nf1MyNbbrllw2mJj69bt67x3KuvvjraYostGmPeaRk7dmyjxovnyiuvdLd+hsXP+NQNOS0iOPZHWDWmTJnisPo82GyzzVwlTIpNNROMFtPNVNTkyosrLLuPfmB/VMe9++673evwes2EqzuOU52dRVVA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>