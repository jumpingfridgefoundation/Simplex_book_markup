# SimplexBook Community Access License (SCAL) Version 2.0

**Copyright (c) 2025 JumpingFridge Foundation**

**Permission is hereby granted, free of charge, to any person obtaining a copy of the SimplexBook Markup (SBM) Specification and associated documentation files (the "Specification"), to use, modify, merge, publish, distribute, sublicense, and sell copies of the Specification, and to permit persons to whom the Specification is furnished to do so, subject to the following conditions:**

**The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Specification.**

**THE SPECIFICATION IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SPECIFICATION OR THE USE OR OTHER DEALINGS IN THE SPECIFICATION.**

---

## SimplexBook Community Access License (SCAL) - Terms and Conditions

### 1. PREAMBLE

This license governs the use, modification, and distribution of the SimplexBook Markup (SBM) Specification. The primary intent is to foster a broad, accessible ecosystem for end-user reading applications while permitting commercialization of parsing infrastructure.

### 2. DEFINITIONS

**2.1 Specification**: The SimplexBook Markup (SBM) Language Specification, including MABF and RABF formats, documentation, and related materials.

**2.2 Licensor**: The JumpingFridge Foundation, an independent volunteer non-profit organization under the laws of the People's Democratic Republic of Algeria.

**2.3 Licensee**: Any individual or entity exercising rights under this license.

**2.4 Parser**: Software component whose primary function is to ingest and process SBM content into intermediate formats, excluding display-ready applications.

**2.5 Reader/Player**: Any software or hardware application whose primary function is to present SBM content to end-users for consumption, including but not limited to dedicated reader applications, mobile apps, web readers, Braille tablet devices, and multi-format reading platforms.

**2.6 Derivative Work**: Any work that incorporates, builds upon, or significantly relies upon the SBM specification.

### 3. GRANT OF RIGHTS

Subject to the terms of this license, the Licensor grants Licensees a worldwide, royalty-free, non-exclusive, perpetual license to:

a) Use, reproduce, and distribute the Specification  
b) Create derivative works of the Specification  
c) Develop and commercialize Parsers  
d) Use the Specification for any lawful purpose

### 4. COMMERCIALIZATION & ACCESSIBILITY

**4.1 Open Commercialization**  
Licensees are explicitly permitted to sell, license, and charge fees for Reader/Player applications built on SBM content consumption. This includes dedicated reading apps, mobile applications, web-based readers, Braille tablet software, and multi-format reading platforms. Commercial development and distribution of Reader/Player applications is encouraged and fully supported under this license.

**4.2 No "Accessibility Tax"**  
Accessibility features must be included in the base price of all Reader/Player applications. Developers cannot charge extra fees, require premium subscriptions, or create paid tiers specifically to unlock accessibility features including but not limited to: text-to-speech functionality, high contrast modes, screen reader compatibility, keyboard navigation, Braille display support, and magnification features. All accessibility capabilities must be available to end-users at no additional cost beyond the standard application price.

**4.3 DRM Restriction**  
Licensees are strictly prohibited from implementing Digital Rights Management (DRM) systems, encryption methods, or any technical barriers that prevent screen readers, Braille displays, or other assistive technologies from accessing the text stream of SBM content. Content protection mechanisms must not interfere with accessibility technologies or create barriers for users with disabilities. This restriction applies regardless of commercial licensing arrangements.

**4.4 Accessibility Compliance Requirement**  
All commercial Reader/Player applications must maintain WCAG 2.1 Level AA compliance as a condition of using the SBM specification. Applications that fail to meet accessibility standards are in violation of this license regardless of commercial arrangements.

### 5. DERIVATIVE WORKS REQUIREMENTS

**5.1 Mandatory Specification Fidelity**  
Any derivative work that modifies or extends the SBM specification must maintain 100% fidelity to mandatory accessibility requirements, including but not limited to all `disc:` tag requirements, WCAG 2.1 Level AA compliance features, screen reader compatibility elements, and accessibility metadata structures. Derivative works that do not maintain these mandatory accessibility features cannot use the names "SBM" or "SimplexBook" in their branding or documentation. Alternative naming is required for modified specifications that do not maintain full accessibility compliance.

**5.2 Attribution Requirements**  
All derivative works must include appropriate attribution to the SBM specification and JumpingFridge Foundation.

**5.3 Scope of Derivatives**  
This requirement applies to:  
- SBM implementations and extensions  
- SBM-compatible tools and utilities  
- SBM educational materials  
- SBM-based services  
- Conversion systems working with SBM

### 6. WARRANTY DISCLAIMER

THE SPECIFICATION IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE LICENSOR DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT.

### 7. LIMITATION OF LIABILITY

IN NO EVENT SHALL THE LICENSOR BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SPECIFICATION OR ITS USE. THE TOTAL LIABILITY SHALL NOT EXCEED USD $100.

### 8. TERMINATION

**8.1 Automatic Termination**  
This license terminates automatically upon material breach of its terms.

**8.2 Survival**  
Upon termination, Licensees must cease all use of the Specification and derivative works.

**8.3 Survival of Provisions**  
Sections 2, 6, 7, 8.3, 11, and 13 survive termination.

### 9. EXPORT CONTROL

Licensees must comply with all applicable export control laws and regulations in their jurisdictions.

### 10. INTELLECTUAL PROPERTY

**10.1 Retained Rights**  
The Licensor retains all rights not expressly granted under this license.

**10.2 Trademark Use**  
Use of "SimplexBook" and "SBM" marks must comply with trademark guidelines and not imply endorsement without permission.

**10.3 Patents**  
This license grants no patent rights. Licensees are responsible for ensuring patent compliance.

### 11. GENERAL PROVISIONS

**11.1 License Version**  
This license may be updated. New versions apply to new distributions.

**11.2 Governing Law**  
This license shall be interpreted according to the laws of the People's Democratic Republic of Algeria.

**11.3 Severability**  
If any provision is invalid, remaining provisions continue in effect.

**11.4 Entire Agreement**  
This license constitutes the entire agreement between parties.

**11.5 Notices**  
All notices must be in writing and delivered as specified in the license.

**11.6 Assignment**  
License rights may not be assigned without consent, except in connection with asset transfers.

**11.7 Community Governance**  
The Licensor welcomes community input on specification development and license terms.

### 15. ORGANIZATIONAL INFORMATION

**12.1 Foundation Structure**  
The JumpingFridge Foundation operates as an independent volunteer team organized as a non-profit under Algerian law, composed entirely of volunteers dedicated to advancing accessible digital reading technologies.

**12.2 Contact**  
For questions regarding this license or the SBM specification, contact the JumpingFridge Foundation through official channels.

### 13. TECHNICAL SPECIFICATIONS

**13.1 MIME Type Definitions**  
The SBM specification defines the following MIME types for operating system and application compatibility:

- `application/x-sbm` - For .mabf (Monolithic Accessible Book Format) files
- `application/x-sbm-archive` - For .rabf (Rich Accessible Book Format) zip archives

Licensees implementing SBM support in operating systems, browsers, or applications should register and handle these MIME types appropriately to ensure seamless integration with the SBM ecosystem.

### 14. ACKNOWLEDGMENT

By exercising any rights under this license, Licensees acknowledge they have read, understood, and agree to be bound by its terms. This license reflects the Foundation's commitment to balancing innovation in digital reading technologies with free and open access for end-users.
