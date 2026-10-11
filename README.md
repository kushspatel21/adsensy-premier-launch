# adsensy-premier-launch
Adsensy helps retailers and businesses advertise across Ahmedabad Metro stations. Customers can upload video and image ads, book available screens, and pay online. Metro administrators can manage stations, screens, and approvals, while footfall-based pricing and revenue analytics help maximize advertising opportunities.


Adsensy — Ahmedabad Metro Advertising Platform
Adsensy is a digital advertising platform designed to help retailers, local businesses, and brands promote their products and services through available Ahmedabad Metro station displays.
Businesses can upload video and image advertisements, choose available advertising screens, pay online, and manage their campaigns. Metro administrators can manage stations, screens, users, approvals, and advertising inventory. The platform also aims to provide footfall-based pricing, advertising performance insights, and revenue analytics.
Hackathon/demo note: Station inventory, footfall figures, pricing, and metro-screen integrations should be treated as sample/demo data unless verified and authorized by the Ahmedabad Metro operator.

Key Features
- Advertiser app: Upload video and image ads, browse available screens, and manage campaigns.
- Admin panel: Manage users, stations, screens, advertising inventory, and campaign approvals.
- Screen playback: Display approved advertisements on connected digital-signage screens through the Adsensy player, where integration is configured.
- Revenue analytics: Review ad performance and revenue insights.
- Footfall-based pricing: Support data-informed advertising rates for available screen inventory.
- Campaign management: Organize advertisements and their selected screen placements.
Intended Users
- Retailers and local businesses
- Brands and advertising customers
- Metro advertising administrators and inventory managers
Technology Stack
- Flutter
- PHP
- MySQL
- REST APIs
- Fiberbase
- Digital-signage player integration
- Online payment gateway
- Video/image upload and analytics dashboard
Update this list to match the technologies and integrations currently implemented in the repository.
High-Level Workflow
1. The administrator adds stations and available advertising screens.
2. The administrator reviews advertiser accounts and approves campaigns.
3. A business selects available screen inventory and uploads its advertisement.
4. The customer completes payment through the configured payment flow.
5. The approved advertisement is assigned to a connected screen.
6. Campaign and revenue data can be reviewed in the analytics area.
Getting Started
Setup steps depend on the specific app and backend repositories. In general:
1. Clone this repository.
2. Open the relevant Flutter project in your IDE.
3. Configure the PHP backend and MySQL database using the project's environment/configuration instructions.
4. Configure API base URLs, upload storage, and payment gateway credentials for your development environment.
5. Run database migrations or import the supplied schema/seed data, if included.
6. Run the Flutter app and test with demo inventory before connecting any real metro advertising screens.
Do not commit passwords, API keys, payment secrets, production database credentials, or other sensitive configuration.
Important Notes
- Use only authorized advertising inventory and screens.
- Real Ahmedabad Metro screen access and actual footfall data require authorization from the relevant operator.
- Clearly label simulated footfall, prices, revenue, and performance metrics as estimates or demo data.
- Payment, screen playback, and analytics features depend on the integrations configured in the project.
Project Status
Hackathon / prototype project for exploring digital advertising inventory management and footfall-informed revenue opportunities for Ahmedabad Metro.

CHECK MY DOC FILE INSIDE WHICH THERE IS PHOTO OF WORKING APP AND I MENTION LIVE LINK IN GOOGLE FORM
