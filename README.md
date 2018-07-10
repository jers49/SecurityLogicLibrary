# SecurityLogicLibrary
SecurityLogiLibrary was designed to be a threat based Security Use Case Library

The purpose of this git is to develop into an exhaustive opensource, threat-based, use case library for any security professional or team wanting to detect threat techniques, tactics and procedures using various methods and mechanisms. 

Originally the scope was to focus on SIEM technologies and logic but gradually that scope grew due the sheer dependencies SIEM has on underlying technologies and other forms of input for correlating and creating logic. 
The scope of this goes beyond SIEM technologies and also dives into the dependent technologies and methodologies that are required for the use cases to be implemented.

When creating the Security Use case library, there are several objectives that require to be met for this library to be usable.

1. The library needs to map to a Framework needs to map to multiple industry frameworks
2. The library needs to cater for use cases outside these framweworks but should be able to support them
3. The library should both be technical, and managerial in order to assist


This framework will map use cases to multiple detection logic, dependencies (both data dependencies and configuration dependencies), severity, Processes to MITRE PRE&POST ATT&CK frameworks, along with the Cyber Kill Chain.

Project Pipeline:
1. Documentation of Use Cases in the Library
2. Review Framework and Add/Remove additional information depending on requirements
3. Create a modular library which alows for the creation and customization of seucrity use case development roadmaps based on scores/metrics such as 'difficulty to implement', 'impact(of the threat)','return on investment (value,coverage and effectiveness)
3. Port Library into a format for integration into open source SIEM platform
4. Create Code that Automatically integrates/update Use case library into existing SIEM deployment
       
