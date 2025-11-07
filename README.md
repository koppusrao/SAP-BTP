# SAP-BTP
**Overview**

The POCs in this repository cover various integration patterns and technical use cases — from simple encoding/decoding operations to complex data transformations, filtering, and inter-iFlow communication.

**Each scenario folder includes:**

    📄 Step-by-step documentation
    
    🖼️ Snapshots of configuration and runtime results


**🧩 Scenarios Implemented
Scenario 1: Encoder or Decoder**

    Demonstrates how to use the Encoder/Decoder feature within Cloud Integration to handle Base64 or other encoding schemes.

**Scenario 2: Combine and Enrich using OData Protocol (iFlow)**

    Explores the Combine and Enrich functionalities with OData adapter to merge or enhance messages during integration processing.

**Scenario 3: CSV to XML Conversion**

    Shows how to convert CSV input data into XML format using Message Mapping and Content Modifier.

**Scenario 4: Filtering**
    Illustrates message filtering capabilities based on specific conditions or field values.

**Scenario 5: Filter by Specific Tag or Field**
  
    Extends Scenario 4 by filtering and displaying only records containing the “contact” field (or any other specific field/tag) in the input payload.

**Scenario 6: Capture Source and Target Logs via Groovy Script**

    Demonstrates how to use Groovy scripting in iFlows to capture and log source and target payloads for debugging and audit purposes.

**Scenario 7: Data Store and Fetch**

    Covers how to use Data Store Operations to persist and retrieve messages within Cloud Integration.

**Scenario 8: Calling One iFlow from Another**

    Explains how to design two iFlows and invoke one iFlow from another using process direct or HTTP adapter.

**Scenario 9: XPath in Cloud Integration**

    Shows how to apply XPath expressions to extract or manipulate XML data within integration flows.

**Scenario 10: Converter (JSON to XML)**

    Demonstrates message transformation using the JSON to XML converter, handling data structure mapping between the two formats.

📂 Repository Structure
**SAP-BTP-Integration-POC/**

├── Scenario-1_Encoder-Decoder/

├── Scenario-2_Combine-Enrich-OData/

├── Scenario-3_CSV-to-XML/

├── Scenario-4_Filtering/

├── Scenario-5_Field-Filtering/

├── Scenario-6_Groovy-Log-Capture/

├── Scenario-7_DataStore-Fetch/

├── Scenario-8_iFlow-to-iFlow/

├── Scenario-9_XPath/

└── Scenario-10_JSON-to-XML/

