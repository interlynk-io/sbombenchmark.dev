# SBOM Benchmark - Build Better SBOM

### What is SBOM Benchmark?
A crucial aspect of software security and supply chain risk management is the emergence of a [Software Bill Of Materials" (SBOM)](https://ntia.gov/sites/default/files/publications/ntia_sbom_framing_2nd_edition_20211021_0.pdf).

To encourage widespread adoption of SBOM, it is essential to maintain high-quality tools for generating and utilizing SBOMs. To this end, CISA has released [The Minimum Elements for a Software Bill of Materials (SBOM)](https://www.ntia.doc.gov/files/ntia/publications/sbom_minimum_elements_report.pdf) document, while OWASP Software Component Verification Standard (SCVS) is developing the [BOM Maturity Model](https://scvs.owasp.org/bom-maturity-model/), which provides guidelines for improving SBOM quality that can be applied towards any SBOM examples.

If you want to check the quality of your SBOMs, you can use [sbomqs - SBOM Quality Score](https://github.com/interlynk-io/sbomqs). This tool uses the NTIA Minimum Elements checks along with other common-sense checks to determine the quality of SBOMs. You can use this tool to assess the quality of your SBOM samples.

SBOM Benchmark is a collection of sbom examples in CycloneDX and SPDX formats. These examples are generated for common repositories and docker images using open-source SBOM tools. Additionally, they are evaluated against the SBOM Quality Score. You can use these SBOM samples to improve your understanding of how SBOMs work in practice.

#### Project Goals

1.  Automate quality assessment and accuracy of SBOMs generated with open source projects.

1.  Use underlying data to help improve SBOM generators and thereby the ecosystem.

### Supported SBOM Generators

SBOM benchmark started with identifying and fixing issues with most commonly used SBOM generators and the list will continue to grow.

-   [Aqua Trivy ](https://github.com/aquasecurity/trivy)
-   [Anchore Syft](https://github.com/anchore/syft)
-   [Bom](https://github.com/kubernetes-sigs/bom)
-   [CycloneDX CDXGEN](https://github.com/CycloneDX/cdxgen)

### Adding an SBOM Generator

If you'd like to recommend including an SBOM generator, please create an issue with [New Tool template](https://github.com/interlynk-io/sbombenchmark.dev/issues/new?assignees=surendrapathak&labels=&template=1_sbom-tool-request.md&title=%5BNew+Tool%5D).
