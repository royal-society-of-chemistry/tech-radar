# Royal Society of Chemistry Technology Radar #
View the [June-August 2023 Tech Radar](https://radar.thoughtworks.com/?documentId=https%3A%2F%2Froyal-society-of-chemistry.github.io%2Ftech-radar%2F2023-08.csv)

We ran our initial tech radar sessions in October and November 2022 based on the [Thoughtworks Technology Radar](https://www.thoughtworks.com/radar), using it as a way for our software teams to share perspectives on a range of tools, techniques and technologies that we use now, that interest us, and that we want to move away from. We refreshed the tech radar in 2023 and 2024.

We've stuck to Thoughtworks' metaphor with little adaptation for this first pass. We used the same rings, _hold_, _assess_, _trial_ and _adopt_, and found it useful to frame their definitions with, "_If we started a new project today, how would we view this blip?_" Here are the definitions we worked with:

* **Hold**: Proceed with caution; phase out or wait to mature.
* **Assess**: Things we believe are promising and worth exploring.
* **Trial**: We’ve seen this used in production and recommend it.
* **Adopt**: The single best choice for a given use case.

We also kept the original quadrants, _techniques_, _tools_, _languages & frameworks_ and _platforms_.

## Radar history ##

* [June-August 2024](https://radar.thoughtworks.com/?documentId=https%3A%2F%2Froyal-society-of-chemistry.github.io%2Ftech-radar%2F2024-08.csv)
* [June-August 2023](https://radar.thoughtworks.com/?documentId=https%3A%2F%2Froyal-society-of-chemistry.github.io%2Ftech-radar%2F2023-08.csv)
* [October-November 2022](https://radar.thoughtworks.com/?documentId=https%3A%2F%2Froyal-society-of-chemistry.github.io%2Ftech-radar%2F2022-11.csv)

## Command centre ##

These are blips that would be unlikely to move from the _Adopt_ ring for several years, such as our core programming languages. We've chosen to drop these from the radar and move them into a "command centre" that we can review on each iteration. These are:

| Blip | Category | Notes |
| - | - | - |
| .NET (Core) | Languages & frameworks | The successor to the .NET Framework, this open-source platform is our preferred choice for development of server and back-end applications. |
| C# | Languages & frameworks | Our preferred language for the application development teams; with most of our codebase in C#, we benefit from having a significant body of experience and tooling to support writing, building and deploying software written in C# and .NET. |
| GitHub Enterprise | Platforms | A git source repository provider with integrated CI/CD pipelines, NuGet package registries and dependency scanning. Provides a choice of cloud-hosted build platforms (Windows, Linux & MacOS) and allows self-hosted runners to be installed on internal infrastructure. |
| JavaScript | Languages & frameworks | The programming language supported by all major Web browsers; also supported in some AWS use cases that do not offer support for .NET, especially Lambda@Edge functions. |
| OAuth/OIDC | Techniques | OAuth is an open standard for delegated access to protected resources; OpenID Connect (OIDC) adds an authentication layer to OAuth; many login and SSO systems such as Okta are built using implementations of these standards. |
| REST | Languages & frameworks | Representational state transfer; an architectural style applied to machine-machine interfaces with the goal of promoting performance, reliability and scalability. |
| Terraform | Languages & frameworks | An open-source Infrastructure as Code (IaC) tool; the cloud infrastructure is defined in a YAML-like language called HashiCorp Configuration Language (HCL); used extensively at the RSC to define infrastructure for internal business applications as well as externally-facing services and databases. |

