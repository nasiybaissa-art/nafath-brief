skeleton: NAFATH-V1
Track: Networking, A Secure National Digital Login
Overview: When Salem opens the mobile app to book an appointment and view his medical results, the cybersecurity system requests facial recognition as multi-factor authentication to secure his data. Upon logging in, his medical record is instantly retrieved from the central database, while AI analyzes doctors' schedules to recommend the best appointment time. Test results are transmitted smoothly between the lab and the app over the secure hospital network, and the software integrates the booking and billing systems to complete the reservation and payment in one tap.
research: #Software, OIDC is used for user authentication (login), while OAuth 2.0 provides authorization.
Resource:(RFC 6749; Sakimura et al., 2014).
#AI, To mitigate AI launch risks, reduce bias, ensure security against attacks, protect privacy, and maintain transparency for auditing.
Resource: National Institute of Standards and Technology. (2023). Artificial Intelligence Risk Management Framework (AI RMF 1.0). U.S. Department of Commerce.
#Mobile: Android restricts sensitive permissions by default, requiring apps to request them interactively at runtime only when needed.
Resource:(Android Open Source Project, 2026).
research: #Networking, DNS over HTTPS (DoH) encrypts DNS queries to prevent eavesdropping and manipulation. However, it does not hide visited IP addresses, encrypt web content, or prevent tracking by the DoH provider.
Resource: IETF. (2018). DNS Queries over HTTPS (DoH) (RFC 8484). Network Working Group. https://doi.org/10.17487/RFC8484.
#Cybersecurity,Phishing-Resistant Authentication
An authentication method is phishing-resistant if it cryptographically binds to the legitimate website’s domain (e.g., physical security keys and FIDO2-based Passkeys). Traditional methods like SMS codes and TOTP authenticator apps do not qualify, as they remain vulnerable to fake websites.
Resource: National Institute of Standards and Technology. (2020). Digital identity guidelines (NIST Special Publication 800-63B). U.S. Department of Commerce.
 FIDO Alliance. (2023). FIDO authentication overview: Phishing-resistant MFA. FIDO Alliance Specifications.
#Data,Under Oman's Personal Data Protection Law, data controllers must secure prior explicit consent, define processing goals, enforce strict security, erase data post-purpose, and instantly report breaches.
Resource : Sultanate of Oman. (2022). Royal Decree No. 6/2022 Promulgating the Personal Data Protection Law. Official Gazette, Issue No. 1429.
 Ministry of Transport, Communications and Information Technology [MTCIT]. (2024). Ministerial Decision No. 34/2024 Issuing the Executive Regulations of the Personal Data Protection Law. Official Gazette, Issue No. 1531.
analysis: 









 
