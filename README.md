# SLA4OAI Technical Committee Wiki

This wiki is the central page for the Technical Committee behind the [SLA4OAI Specification](https://github.com/isa-group/SLA4OAI-Specification): an extension for [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) in order to describe Service Level Agreements (SLA) in RESTFul APIs including elements such as quota, rates or usage plans.

This committee is open to all the different members in OAI and the API developer community in general. If you are interested in participate please subscribe to the following list: [sla@openapi.groups.io](https://openapi.groups.io/g/sla)

In the next sections, you can find the meetings, minutes, material, and the roadmap for future actions. 

## History

 - 2016 - A first draft (v0.9.1) f the specification has evolved from an academic initiative started by [ISA Research Group](http://www.isa.us.es) at [University of Seville](http://www.us.es).
 - 2017 - Extension is presented to OpenAPI Technical Specification Committee that expressed their positive feedback about it. 
 - 2018 - OpenAPI Governance Board aproved the creation of a *Specific Interest Group* to coordinate this extension. This group is originally formed by different members from the OAI consortium.
 - 2018 - The specific interest group starts its activities.
 - 2019 - A [common view](docs/2019_ESEC_FSE_IndustryTrack_The_role_of_SLAs_in_the_API_industry.pdf) on the conceptual model and priorities to be addressed is defined.
 
## Roadmap

Proposed milestones for the specification:
 - **2019Q4** - Proposal of v1 of SLA4OAI
 - **2020Q1** - Open call for tooling/community feedback
 - **2020Q1** - Discuss new v2 features
 - **2020Q3/4** - Work on v2 of SLA4OAI

## Consolidated Material

[The Role of Limitations and SLAs in the API Industry (SLA4OAI-TC)](docs/2019_ESEC_FSE_IndustryTrack_The_role_of_SLAs_in_the_API_industry.pdf) presented at the Industrial Track of the 27th ACM Joint European Software Engineering Conferenceand Symposium on the Foundations of Software Engineering (ESEC/FSE ’19)

## Working Material
[SLA4OAI Manifest](./Manifest.md). This document contains the key foundational decisions to guide SLA4OAI.

[Minimal specification for SLA4OAI v1](FirstMinimalSpecification.md). This document exposes the core elements that will be included in version 1 of the spec.

[Use Cases](UseCases.md) List of *User Stories* to consider for the specification.

[Potential features to include in following versions](PotentialFeatures.md). Set of features grouped in areas that will be discussed in future versions of SLA4OAI.

Perspectives of SLA from the different participants: 
- [Pablo Fernandez (ISA-Group)](https://drive.google.com/open?id=1sBjd8FR4zVqF5wYBzvnWrpncCmO2AJv1) as discussed on the 2018-11-07 call.
- [Isaac Hepworth (Google/Apigee)](docs/API%20Service%20Levels%20and%20OpenAPI.pdf) as discussed on the 2018-12-03 call.

## Calls
This section contains the key content and minutes from the different calls.

### 2019-02-19
*Participants:  Nikhil Kolekar (Paypal), Isaac Hepworth (Google), Mike Ralphson, Pablo Fernandez (ISA Group), and Pedro J. Molina (Metadev & ISA Group)*

In this meeting Nikhil presented his PoV about SLAs and APIs given his experience in operating and creating APIs at scale inside Paypal. Summary of the aspect covered follows:

- API Performance and SLOs
- Drivers for Customer Experience
- SLO for APIs
- Metrics
- Measurement
- Monitoring

[Video recording (42 minutes)](https://drive.google.com/open?id=1DR6z103Q1YU589euhz1BCcd8YXCWD5k1)


### 2018-12-03
*Participants: Madhurranjan Mohaan (Google), Pablo Fernandez (ISA Group), and Pedro J. Molina (Metadev & ISA Group)*

In this meeting Madhurranjan presented his global point of view about SLAs in APIs:

Introduction of the concepts:

Technical concepts:
- **SLO**: Service Level Objective (promise to users, expected limit values)
- **SLI**: Service Level Indication (real measure in the system at a given point in time for a set of users)

Business concepts:
- **SLA**: Service Level Agreement (business contract associated with an API as an *aggregation of services* with specific SLOs and prices)

#### Material
 - [Audio of the call](https://drive.google.com/open?id=17zDfDFmZw8IF_JhWtW7L2qWUofPEkguI)
 
### 2018-11-07
*Participants: Nikhil Kolekar (Paypal), Madhurranjan Mohaan (Google), Isaac Hepworth (Google), Scott Ganyo (Google), Kin Lane (API Evangelist), Mike Ralphson, Jeffrey ErnstFriedman (Linux Fundation), Pablo Fernandez (ISA Group), and Pedro J. Molina (Metadev & ISA Group)*

Pablo Fernandez:
- Presented the global perspective of the SLA4OAI specification including a foundational manifest, the current initial draft and the potential roadmap to follow. 

Presentation of different members and feeback:

Kin Lane: 
- Keep it modular and separate aspects: SL Objectives, Plans, Metrics, etc. (decoupled)
- Aspects than can be referenced externaly for different concerns
- Relation to API Licenses

Nikhil Kolekar:
- Paypal working in SLA for 3 years
- Focus on SLO (Objectives): response times, latencty as warranties.
- Proposes studing different cases on Service subscription (depending on roles) and classes of services

Madhurranjan Mohaan: 
- Experience on Apigee + Google
- Identify roles involved: api developers, api managers, operations, consumers
- Service Level: Indications, Objectives and Agreement
- Grouping levels and use cases:
    - Simple services: SLI and SLO
    - Group of services: SLA as an combined contract
- Declarative SLI and SLO
- Runtime measuring + integrating with alerting tools
- Identify roles and use cases for each role

Mike Ralphson:
- Keep separate concerns and modular

Pedro J. Molina:
- Call to action:
    - Goal define a neutral extension for SLA usable by the industry
    - Enroll anyone interested
    - Define scope, be pragmatic, keep it as siple as possible


#### Material
 - [Video of the call](https://drive.google.com/open?id=1R7TNYZQruRXmaIJuREls9lRslapptNFY)
 - [Slides](https://drive.google.com/open?id=1sBjd8FR4zVqF5wYBzvnWrpncCmO2AJv1)



