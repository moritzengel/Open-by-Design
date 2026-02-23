# Open by Design
## The Limits of Translating Bits to Atoms

### 1. Introduction: The Divergence of Bits and Atoms

In 1980, a programmer named Richard Stallman at a Massachusetts Institute of Technology(MIT) Lab encountered an ordinary but infuriating problem. The lab's new laser printer jammed frequently. In the previous iteration, Stallman would have simply modified the code to send an alert to the users, but this time, the manufacturer refused to share the source code. The machine was a "black box," creating a dependency that left the user powerless to fix a simple error.<sup>1</sup> This frustration set off a revolution. Stallman went on to found the Free Software movement, establishing a philosophy that knowledge, specifically the code that makes our tools work, should remain free to share and modify.

Forty years later, this philosophy has become common in the digital world. "Open Source" is no longer a niche concept; it is the scaffolding of the internet's infrastructure. From the 71% of smartphones worldwide running Android (a derivative of Linux),<sup>2</sup> to WordPress, the content management system powering over 43% of all websites,<sup>3</sup> we live in an era defined by the collaborative sharing of "bits." However, when we look away from our screens and at the physical objects in our homes, this revolution seems to have circumnavigated them. 

Our physical objects, from furniture to smartphones, are increasingly closed, proprietary, and unrepairable. While the software industry has figured out how to commercialise open source, the industrial design world has struggled to translate these principles into "atoms". This disconnection forms the core of the research.

Strictly speaking, open source product design, often referred to as "Open Source Hardware" (OSHW), involves sharing the "source code" of physical objects, including 3D files, bills of materials (BOMs), and assembly instructions.<sup>5</sup> It promises a shift in power dynamics: repairability, collaborative innovation, right to repair and freedom from planned obsolescence. However, the reality is often much bleaker. Open hardware projects frequently suffer from short lifespans and inadequate documentation, as evidenced by the "Focal Camera" project by Mathijs van Oosterhoudt, which struggles with accessibility despite its open status.<sup>6</sup> Furthermore, many projects lack financial sustainability. Projects like the "Audioberry" audio amplifier or the "Air-It-Yourself" air purifier by Newtab-22 garnered significant press attention but are now nowhere to be found.<sup>7</sup>

This memoire investigates a critical divergence: Why is the open model thriving in software but struggling in hardware? Is it possible to create "open-source" products that are financially sustainable in a capitalist society, or does the obstacle of manufacturing require a fundamentally different philosophy than the one Stallman established for code? To answer this, the movement's history and related approaches were analysed, a conversation with a project founder was held, as well as both failed and successful projects were examined.

### 2. Open Source in Hardware: The Friction of Reality

#### Design follows full ownership

If the definition of Open Source in software is the sharing of code, its translation to product design is the sharing of build plans. In theory, Open Source Hardware offers a radical inversion of the traditional industrial model. It proposes a shift from the passive consumer to the active participant, empowering users to understand, adapt and repair the objects that inhabit their lives. This philosophy forces a reimagining of the traditional design priority: "form follows function." In the open model, the design priority should be form follows full ownership. A genuinely open object must be designed not just for its end use, but for its reconstruction, adaptation and repair. 

This implies a new set of principles: 
* Design follows approachability
* Design follows necessity
* Design follows ownership
* Design follows participation
* Design follows production
* Design follows maintenance
* Design follows repairability
* Design follows sourcing

Arduino, the open-source ecosystem for prototyping programmable electronic circuits, best exemplifies this needed approachability. Before 2005, microcontrollers were the exclusive domain of engineers. Arduino did not just open the source code; it designed a physical language: The friendly blue boards with intuitive connectors, a comprehensive reciprocity that allowed designers to prototype without an engineering degree. It has proven that openness acts as a translation layer between complex technology and creative application.<sup>21</sup> This shows that Open Design is driven by communication and requires an aesthetic. 

An object is truly "open" only if it looks like it can be opened. If a device has an open licence but is glued shut, it is legally open but physically closed. True Open Design signals its repairability through visual cues such as exposed fasteners, modular joints, and standard materials. It is the visual communication of the right to modify and repair. 

"Design follows Necessity" is best displayed by "Precious Plastic." Dave Hakkens designed a suite of machines to combat plastic pollution globally, which are built locally to recycle plastic waste.<sup>23</sup> But it is not only by solving urgent problems with products that consumption is forced solely out of 'necessity'; the visually open design also helps to rethink ignorant consumerism. By prompting the user to reflect and requiring them to invest labour to obtain the product, the impulse to buy is checked by the necessity of building. As the "IKEA Effect" demonstrates, individuals place a higher value on products they partially create.<sup>8</sup> This labour creates a stronger emotional connection; the user begins to respect the resources involved and values the object more, ultimately leading to a longer product lifespan through repair. Furthermore, this contributes to full ownership, which one also takes advantage of. 

However, this participation possibility in the product must be communicated and designed so that the consumer feels motivated to start the project and is confident to be able to complete it. Thus, the entry barrier must be as low as possible. This can be achieved by making production, maintenance and repair instructions as accessible as possible and by designing mainly for domestic manufacturing tools, such as simple hand tools and 3D printers. However, it is also possible today to develop for more advanced machines, such as CNC routers and laser cutters, through the vast and expanding global network of FabLabs (over 2,300 today<sup>10</sup>). Consumers can reclaim ownership and self-efficacy of production through these spaces. 

What is also important for participation is easy sourcing of components; otherwise, repair and participation are made impossible. A prime example is the Re:Mix kitchen mixer by Open Funk. Marketed as a circular, repairable, and open-source alternative to standard appliances, it promises empowerment. However, a closer inspection of their repository reveals that the "Lid Assembly", the most important, complex and R&D-heavy component, is missing.<sup>24</sup> When pressed by the community, the creators admitted that financial instability forced them to keep sensitive files closed to protect their competitive advantage.<sup>11</sup> However, the Re:Mix by Open Funk is much easier to repair than any other mixer on the market, but this comes at a higher purchase price. This high price is justified by higher production costs, because it is not industrially produced as a closed construction, to maximise profit margins, as well as by additional R&D to design an "open" product. If one is really strict, the missing "Lid Assembly" renders the Mixer not truly open source under most open-source definitions. 

The most common definition is provided by the Open Source Hardware Association (OSHWA). The OSHWA provides the gold standard: for a project to be certified, it must share not only all of the design files but also the bill of materials (BOM) and schematics, and permit unrestricted modification and commercial sale.<sup>5</sup> This "commercial sale" clause is the breaking point, and that is when good intentions collide with the rigid definitions required for certification. If one allows anyone to sell one's work, how does one survive as a designer? This fear leads to a phenomenon one might call "Openwashing," in which projects use the marketing allure of "Open Source" while retaining proprietary control over critical elements. As seen with the kitchen blender by Open Funk. 

Not an isolated incident: OpenDesk, launched in 2013, began with a vision of open furniture making. Users could download CNC files openly and OpenDesk connected corporate customers with producers worldwide. As the platform attempted to scale, presumably, the need for revenue, quality control, and brand protection forced a pivot. By 2019, OpenDesk effectively ceased public file sharing and had transformed into a standard decentralised B2B furniture brand.<sup>12</sup>

Another challenge of open source is that collaboration is difficult when working with atoms. The answer lies in the fundamental economic divergence between software and hardware. In software, the cost of distribution is zero. If a developer publishes code on GitHub, a million users can use and modify it without costing a cent. In hardware, one must invest before being able to participate and understand the assembly, materials, shipping, and labour. These investments create a "Participation Barrier." In software, copying is instantaneous. 

In hardware, replication requires:
* Financial Investment: The participant must invest in material and production.
* Skill: The participant must possess craftsmanship (e.g. how to: saw, glue, sand, paint, solder, assemble, or debug).
* Infrastructure: The participant requires access to workshops and specific tools (e.g., 3D printers, laser cutters).
* Availability: The participant must be able to source specific components and raw materials easily.

An example of how this barrier is often kept artificially high, whether intentionally or not, is OpenStructures. It is turning "Openness" into a mere marketing tool. While it seeks to achieve openness through a modular grid system to foster "collaborative compatibility," most projects on the platform are difficult to replicate due to the absence of documentation (e.g., BOMs or CAD files). A notable example are the projects by Packbag, which utilise the grid only for one part: an ordinary belt.<sup>13</sup> Consequently, the platform becomes a gallery or online shop rather than a repository, beautiful to look at, but impossible to use.<sup>9</sup>

The fear of commercial copying might justify these barriers: in software, a derivative usually remains free, and a commercial entity gains advantage only through service or adaptation. In hardware, a company like Bambu Lab builds its machines upon years of open research from the RepRap Project,<sup>15</sup> Prusa Research, and Voron Design.<sup>16</sup> They are using open-source foundations to power proprietary machines, without contributing back. Their 3D printers rely on R&D derived from open projects, yet the printers themselves remain closed.<sup>14</sup> That is also what Cohen from DIYR argues: Open Source is often romanticised, stating that in reality, it is "a jungle" where "the big one eats the small one" (Nitzan Cohen, 2025, own translation).<sup>9</sup>

Given these realities, we may need to look beyond the strict OSHWA definition and identify projects and alternative models that achieve the goals of openness without the label. History offers precedents. Enzo Mari's 1974 project Autoprogettazione was arguably an open-source furniture project before the definition existed, even though he specified non-commercial use only.<sup>17</sup> By providing free manuals to build furniture using simple timber and nails, Mari prioritised learning over the final object.<sup>18</sup> Similarly, Louise Brigham's 1909 book Box Furniture offered DIY instructions to democratise furniture making, using standard wooden shipping crates.<sup>19</sup>

A good contemporary example is the platform DIYR.dev, led by Nitzan Cohen at the Free University of Bozen-Bolzano, which provides high-quality, free instructions for electronic home accessories like fans and lamps.<sup>20</sup> For the time being, the project can run through funding by the university. Similarly, on platforms for 3D printing, such as Printables or MakerWorld, designers primarily publish 3D-printable designs that can be downloaded. Since 2021, Printables has implemented an incentive model that rewards designers for downloads and for projects that are successfully replicated.<sup>22</sup> To incentivise sharing designs, pushing for the growth and the social medialisation of the platform.

### 3. Conclusion: Beyond the Binary of Open and Closed

This research began with a simple question: Can the digital success of Open Source be translated to the physical world of product design? After analysing the history, the economic realities, and the current landscape, the answer appears to be a "No", at least not in the way originally hoped. The attempt to copy the roadmap of software, applying licenses like the General Public License (GPL) to chairs and blenders, expecting that a "Linux of Furniture" would naturally emerge, which was a wrong assumption. The fundamental difference between "bits" and "atoms" is not just physical; it is economic.<sup>4</sup> In software, sharing is frictionless; in hardware, sharing is an invitation to physical labour.

The rigid definition of Open Source creates a binary that often stifles the very innovation it seeks to foster. The analysis of projects such as OpenDesk and Re:Mix reveals a recurring pattern: "pure" openness is often financially detrimental for independent designers. When the source files are the product, giving them away destroys the revenue stream. However, recognising this failure does not mean abandoning the philosophy. 

The key is to understand Open Source as a spectrum, rather than a toggle switch:
* On one end is the "Pure Open" (RepRap), sustained by selling tools.
* In the middle is the "Accessible" (DIYR.dev), where repair manuals and spare parts are available.
* On the other end lies the "Closed," the black boxes Stallman fought against.

A Hybrid Solution might be the answer, as the research suggests that financial sustainability requires decoupling "commercial usage rights" from "access to knowledge." A viable solution for the modern designer could be a tiered purchasing model. 

In this ecosystem, a customer could choose to buy:
* The digital plans (plans and 3D-files).
* The kit (parts, hardware, 3D files, and plans).
* The finished product (product, 3D-files, and plans).

All tiers include the "Source Code": the instructions, bill of materials (BOM), 3D files, and code. Providing the user with complete transparency and the ability to modify or repair the object. However, unlike the strict OSHWA definition, this license would restrict commercialisation. The user owns the data to fix their device, but they can not become competitors. While purists might argue this diminishes the collaborative aspect of Open Source, it protects the designer's livelihood while preserving the user's agency. 

This definition and goal of "Full Ownership" is possibly the right approach for objects, and perhaps "Open Source" is not really the right term for hardware. If we return to the broken printer that initiated the movement, Stallman did not necessarily want to collaborate with the printer's manufacturer; he wanted the agency to fix and adapt it. For the average consumer, the highest value is not downloading a CAD file to CNC-mill a chair. The value lies in the Right to Repair, the right to modify, independent access to spare parts, and the prolongation of the object's lifespan. 

This matters because the closed model is ecologically unsustainable. We can no longer afford to design "Black Boxes" that become waste the moment a component breaks. The "Open" philosophy is the only viable path toward a circular economy. Whether it is called "Open Source" or "Right to Repair,"<sup>4</sup> the core principle is still: an object that cannot be opened, cannot be saved. As designers and as the industry, our responsibility is to move away from the ignorance of "Consumerism" and toward the "WE", we have as "earthlings". We must design objects that invite the user to repair and modify them. We may not reach the utopia of a world where every object is open-source. However, we can certainly build a world where every object is understandable, repairable, adaptable, and enduring. 

### Bibliography

1. Sam Williams, Free as in Freedom (2.0): Richard Stallman and the Free Software Revolution, Free Software Foundation (Boston, 2010), p. 4.
2. "Mobile Operating System Market Share Worldwide", Gs.statcounter.com, 1.1.2025 https://gs.statcounter.com/os-market-share/mobile/worldwide (last visited 8.1.2026)
3. "Usage statistics of content management systems", W3Techs.com, 6.1.2024 https://w3techs.com/technologies/overview/content_management (last visited 6.1.2026)
4. IFIXIT, "Self-repair manifesto", https://www.ifixit.com/Manifesto (last visited 11.1.2026)
5. "Definition of free and open source hardware (OSHW)", Oshwa.org, 26.5.2012 https://www.oshwa.org/definition/ (last visited 6.1.2026)
6. Mathijs van Oosterhoudt, "Focal Camera", Wikifactory.com, 2021 https://wikifactory.com/@botler/focal-camera (last visited 8.1.2026)
7. Jennifer Hahn, "Everyone from children to the elderly" can build DIY air purifier, 11.11.2022 https://www.dezeen.com/2022/11/11/air-it-yourself-purifier-jihee-moon-newtab-22/(last visited 8.1.2026)
8. Michael I. Norton, Daniel Mochon, Dan Ariely, "The IKEA Effect: When Labor Leads to Love", Journal of Consumer Psychology, Vol. 22, No. 3 (July 2012), pp. 20.
9. Nitzan Cohen, "Interview with the Founder of DIYR", Personal Communication, Interview on the 29.12.2025.
10. "Fab Foundation: Labs", Fabfoundation.org, https://fabfoundation.org/#page-top (last visited 8.1.2026)
11. Kenrofunk, "Re:Mix Kitchen Mixer - Issues #2", 2.3.2025 https://github.com/openfunkHQ/reMix/issues/2 (last visited 6.1.2026)
12. "OpenDesk: About", En.wikipedia.org, 25.12.2025 https://en.wikipedia.org/wiki/Opendesk (last visited 6.1.2026)
13. Packbags Studio, "A.933.1 - Sling bag S with handle, Open Structures, 2024 https://www.openstructures.net/apps/a933 (last visited 4.1.2026)
14. Josef Prusa, "The state of open source in 3D printing", Blog.prusa3d.com, 29.3.2023 https://blog.prusa3d.com/the-state-of-open-source-in-3d-printing-in-2023_76659/ (last visited 6.1.2026)
15. Rhys Jones, et al., "RepRap – the replicating rapid prototyper", Robotica, No. 29 (January 2011), p. 2.
16. "Voron Design: About", vorondesign.com, https://vorondesign.com (last visited 8.1.2026)
17. Enzo Mari, Autoprogettazione?, Corraini Edizioni (Mantua, 2002), p. 35
18. Enzo Mari, Autoprogettazione?, Corraini Edizioni (Mantua, 2002), p. 45.
19. Louise Brigham, Box Furniture: How to Make a Hundred Useful Articles for the Home Classic Reprint) (English Edition), The Century Co. (New York, 1909), Preface. https://archive.org/details/boxfurniture00brig/page/n19/mode/2up (last visited 4.1.2026)
20. DIYR "DIYR Products", https://diyr.dev/products/ (last visited 8.1.2026)
21. "Arduino", En.wikipedia.org, 8.1.2026: https://en.wikipedia.org/wiki/Arduino (last visited 11.1.2026)
22. Mikoláš Zuza, "Introducing a new reward system and badges for PrusaPrinters!", https://blog.prusa3d.com/introducing-a-new-reward-system-and-badges-for-prusaprinters_60073/, 16.12.2021 (last visited 9.1.2026)
23. Precious Plastic, "We are on a mission", preciousplastic.com, https://www.preciousplastic.com/ (last visited 9.1.2026)
24. Open Funk, "reMix 3D-Printed components", https://github.com/openfunkHQ/reMix/tree/main/3D-printed components/STEP (last visited 11.1.2026)

*For some parts of this memoire Google Gemini Version 3 (January 2026) was used for aid of the wording and as a translation and proofreading tool.* *Translation and proofreading were also done using DeepL, Grammerly and LanguageTool.*
