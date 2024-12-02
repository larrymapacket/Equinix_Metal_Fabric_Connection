# Equinix_Metal_Fabric_Connection
Connect Metal nodes in two different Metros via Equinix Fabric according to the architecture diagram:
Metal vlan in two different Metros.
Two Metal servers in different Metros with the same vlan ID in both metros. Configure vlan interfaces (Hybrid Bonded mode) on both Metal servers, assign private IPs to the interfaces.
Use your Metal project owned Dedicated fabric port to create a VC to connect Metal with Equinix fabric.
Create a fabric VC (fabric billed) request on Metal and use the provided z-side token to create fabric VC in fabric portal.

Architectural Diagram:
![Metal-Fabric-Lab-Arch](https://github.com/user-attachments/assets/d123a6b0-3e87-4edf-ac52-1f106b0363f1)
