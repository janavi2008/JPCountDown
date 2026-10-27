# JPCountDown
its a mechanical counter with 3 digits- so it goes upto 999. ill be designing it to act as a countdown, e.g days until summer vacation. i saw the mechanism for a tally counter online, and found it really interesting, so i thought id try and replicate it for this project. i wanted to use it as a countdown for the end of 12th grade, plus itll look so cool sitting on my desk.

# Design
for the actual counting part, the carry mechanism is similar to that used in car odometers - the part where the tens digit goes from 0-1 when incrementing from 9 to 10. how it works is, on the left side face of the one's digit wheel, there is a gear with 2 teeth and the rest smoothed out- so it only meshes with the other gear once each rotation. there is a carry pinion that has half its teeth cut off on one side as a locking mechanism, and this gear only turns when the 2 teeth of the one's digit contact it. the other side of this pinion meshes with a gear on the right face of the ten's digit wheel. this ir replicated between ten's and hundred's.
for decrementing the counter, ive used a ratchet and pawl mechanism, so pulling down a lever(withe a driving pinion attached to it) rotated the ratchet by 36 degrees, and then a spring pushes the lever back up, but a locking pawl holds the ratchet in place.

ratchet:<img width="293" height="297" alt="image" src="https://github.com/user-attachments/assets/833f08dd-5e12-450a-8faf-997ebba3d004" />

pawl:<img width="226" height="188" alt="image" src="https://github.com/user-attachments/assets/b4725e50-c84d-4d18-82f8-6c4ad5b73312" />

lever:<img width="421" height="302" alt="image" src="https://github.com/user-attachments/assets/9a98e35b-54e5-4a21-ab8f-c5e0da5ba9bc" />

carry pinion:<img width="257" height="239" alt="image" src="https://github.com/user-attachments/assets/afb45e1d-5f7f-4b35-9597-95a70872986e" />

digit wheel:<img width="390" height="323" alt="image" src="https://github.com/user-attachments/assets/602f6566-18fb-4421-a78d-7e93116a77a5" />


<img width="327" height="260" alt="image" src="https://github.com/user-attachments/assets/e5d6bf25-27f9-4355-9fa2-284a79b46742" />


# Bill of Materials


| Part | Quantity |
| :--- | :---: |
| case 3d print | 1 |
| ratchet 3d print | 1 |
| digit wheel 3d print | 3 |
| pawl 3d print | 2 |
| lever 3d print | 1 |
| carrier gear 3d print | 2 |
| springs | 3 |
| 6mm od 200mm length axle | 2 |

