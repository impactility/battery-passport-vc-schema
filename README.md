# Battery Passport VC Schema

This repository contains Verifiable Credential (VC) schemas for Battery Passport data, designed to comply with Battery Regulation requirements. The schemas are provided in both JSON Schema and JSON-LD formats to support verifiable credentials and semantic web applications.

## Overview

The Battery Passport VC Schema provides structured schemas for representing battery-related information as verifiable credentials. These schemas cover all major categories required for battery passports, enabling standardized data representation and verification.

## Schema Categories

| Category                                        |   Number of Attributes |
|:------------------------------------------------|-----------------------:|
| Battery carbon footprint                        |                      9 |
| Battery materials and composition               |                      5 |
| Circularity and resource efficiency             |                     16 |
| Identifiers and product data                    |                     11 |
| Performance and durability                      |                     42 |
| Supply chain due diligence                      |                      3 |
| Symbols, labels and documentation of conformity |                      7 |
| Total                                           |                     93 |

## Structure

Each schema category is organized in its own directory containing:
- `*.json` - JSON Schema definition (Draft 2020-12)
- `*.jsonld` - JSON-LD context definition for semantic web compatibility

### Available Schemas

- **BatteryCarbonFootprint** - Carbon footprint and environmental impact data
- **BatteryMaterialsAndComposition** - Material composition and sourcing information
- **CircularityAndResourceEfficiency** - Circularity metrics and resource efficiency data
- **IdentifiersAndProductData** - Product identifiers and basic product information
- **PerformanceAndDurability** - Performance characteristics and durability metrics
- **SupplyChainDueDiligence** - Supply chain transparency and due diligence information
- **SymbolsLabelsAndDocumentationOfConformity** - Compliance symbols, labels, and documentation

## Usage

These schemas can be used to:
- Validate battery passport data structures
- Create verifiable credentials for battery information
- Ensure compliance with Battery Regulation requirements
- Enable interoperability between different battery passport systems

### JSON Schema

The JSON Schema files follow the [JSON Schema Draft 2020-12](https://json-schema.org/draft/2020-12/schema) specification and can be used with standard JSON Schema validators.

### JSON-LD Context

The JSON-LD context files provide semantic definitions for use in Linked Data applications and verifiable credential systems.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  
Copyright (c) 2025 Impactility
