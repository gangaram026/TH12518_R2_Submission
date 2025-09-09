Solution FacilityCare provides an integrated solution with: - AI-based
faint detection and instant hospital alerts. - Smart cleanliness
monitoring with worker reward/deduction through tokens. - Token
redemption system for meals, clothes, or other benefits. - Interactive
UI for workers, admins, and families to track safety and cleanliness.

3. Logic & Workflow

Data Collection - AI camera captures human poses (MediaPipe Pose). -
Workers submit before/after images of cleaned areas. - Location and
hospital data collected using Leaflet + OpenStreetMap.

Processing - Pose landmarks processed to detect fainting. - Image
similarity algorithms calculate cleanliness levels. - Token system
updates based on performance.

Output - Alerts shown on-screen and via voice (speech synthesis). -
Nearby hospitals displayed on map. - Tokens awarded/deducted and stored
in user account.

User Side - Workers: Log in, upload images, earn tokens, redeem
rewards. - Families: Monitor cleanliness and safety. - Public: Report
complaints with photos.

Admin Side - Task assignment and worker monitoring. - View cleanliness
reports and health alerts. - Approve/reject worker submissions and
manage token distribution.

4. Tech Stack

-   Frontend: HTML, CSS, JavaScript
-   AI/Detection: MediaPipe Pose (Faint Detection), Image Similarity for
    Cleanliness
-   Maps & Location: Leaflet.js + OpenStreetMap
-   Backend (Planned): Node.js + Express
-   Database (Planned): MongoDB / Firebase for user & token management
-   Other: Web Speech API (voice alerts), LocalStorage (prototype user
    data)

5. Future Scope

-   Integration of Mobile App for real-time reporting and monitoring.
-   Blockchain-based CleanToken System for transparent worker rewards.
-   Advanced AI for multi-emergency detection (heart attack, falls,
    etc.).
-   IoT sensor integration for automated cleanliness and water/air
    quality monitoring.
-   Scalable multi-user platform with cloud support for large facilities
    and events.
