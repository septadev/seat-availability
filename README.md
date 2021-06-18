# Estimated Seat Availability
This dataset estimates the seat availability on SEPTA routes.

## Latest release
Latest version: [v202106201](https://github.com/septadev/seat-availability/releases/tag/v202106201), containing estimates for the week of June 20, 2021 to June 26, 2021.
These estimates are based on data collected from June 6, 2021 to June 15, 2021.

### Changes since previous version:
* Includes estimates for Routes "101B" and "102B", which are the shuttle bus replacements for Routes 101 and 102 respectively. We anticipating providing these estimates while shuttle buses are operating.
* A new schedule went into effect on June 6, 2021. The estimated seat availability  is based on data from June 6, 2021 to June 15, 2021. Using fewer but more recent observations for estimations following a schedule change is a departure from previous methodology regarding schedule changes. Previously, at the beginning of a new schedule change, a seat availability estimate for a scheduled stop was based on an average of ridership observations at similar times of day and the same service day, route, direction, and stop during the previous schedule. It is now based on ridership data observed after the current schedule took effect.
* Fixed mislabeled column name in metadata file and made minor edits for clarity.

### Known issues:
* This version has estimations for some bus routes, but not all bus routes. This version does not contain estimations for some modes, routes, trips, and stops due to data availability. We expect to update existing estimations and to add estimations for additional routes in future versions.
* All bus, trolley, trackless trolley, NHSL, MFL, and BSL trips are included for completeness, but some have empty values in the "estimated_seat_availability_category" column, indicating no estimation is available.
* In future versions, this dataset may include a separate file containing seat availability estimations for Regional Rail routes.

## License Agreement
By downloading any dataset(s) from this website (https://github.com/septadev/seat-availability), you acknowledge and agree to the following LICENSE AGREEMENT: 

This LICENSE AGREEMENT ("Agreement") is entered into by and between Southeastern Pennsylvania Transportation Authority ("SEPTA") and you ("Licensee"). 

SEPTA hereby grants to Licensee a non-exclusive, non-assignable, non-transferable, limited and revocable right to use, reproduce and redistribute the Estimated Seat Availability Dataset (“the dataset”) subject to the following terms and conditions: 

* Licensee may not use SEPTA's trademarks and copyrighted materials for any commercial or profit-making use and may not alter them in any way. See SEPTA’s Copyright Notice and Trademark Notice for the full text: http://www.septa.org/site/copyright.html 
* The dataset is provided on an "as is" and "as available" basis. SEPTA makes no representations or warranties of any kind, express or implied, pertaining to the dataset. SEPTA disclaims all warranties pertaining to the dataset, express or implied, including but not limited to implied warranties of merchantability, fitness for a particular purpose, accuracy, completeness, usefulness, timeliness, reliability or functionality. SEPTA and its employees, officers, Board members and agents will not be liable for damages of any kind arising from the use of the dataset including but not limited to direct, indirect, incidental, punitive and consequential damages. 
* SEPTA reserves the right to alter and/or no longer provide the dataset at any time without prior notice. 
* Licensee agrees to indemnify, defend and hold harmless SEPTA, its employees, officers, Board members and agents, from and against all fines, suits, proceedings, claims, causes of action, demands, or liabilities of any kind or of any nature arising out of or in connection with Licensee's use of the dataset. 
* The validity of any term or provision of the Agreement will not affect the validity of any other provision set forth herein. 
* SEPTA does not currently charge a license fee to download the dataset. However, SEPTA reserves the right to institute a license fee at any time in the future without prior notice. 
* SEPTA maintains title, ownership, rights and interest in and to the dataset. 
* SEPTA reserves the right to modify or revoke the Agreement at any time. 
* The laws of the Commonwealth of Pennsylvania shall govern all rights and obligations under the Agreement. 
* Licensee agrees that any dispute with SEPTA arising out of any use of the dataset must be brought by Licensee exclusively in the state or federal courts situated in Philadelphia County, State of Pennsylvania. 
* Licensee agrees to observe and comply with all applicable laws, ordinances, rules, regulations, and executive orders of Federal, state and local government entities, now existing or hereinafter in effect, which may in any manner affect the performance of this License Agreement. Provision(s) required by law, ordinances, rules, regulations, or executive orders to be inserted in this License Agreement will be deemed inserted herein whether or not they appear in this License Agreement. 
* The most recent version of the Agreement shall always apply. It is the responsibility of the Licensee to seek out the most recent Agreement if accessing any dataset prior to the most recent. 
* The Agreement constitutes the complete and exclusive agreement between SEPTA and Licensee with respect to the subject matter hereof and supersedes all prior oral or written understandings, communications, or arguments not specifically incorporated herein.
