---
uid: Connector_help_Globecast_France_Enhanced_Single_Destination_Transport_Service
---

# Globecast France Enhanced Single Destination Transport Service

The Globecast France Enhanced Single Destination Transport Service is an enhanced service protocol. It oversees both the source and destination nodes of NetInsight Nimbra V3, retrieving active alarms associated with these nodes and determining the overall severity of the channel.

## About

### Version Info

| Range              | Features                                                                                          | Based on | System Impact |
|--------------------|---------------------------------------------------------------------------------------------------|----------|---------------|
| 1.0.0.x [SLC Main] | Initial version: Calculates the severity of the service based on the state of its child elements. | -        | -             |

### System Info

| Range   | DCF Integration | Cassandra Compliant | Linked Components | Exported Components |
|---------|-----------------|---------------------|-------------------|---------------------|
| 1.0.0.x | No              | Yes                 | -                 |                     |

## Configuration

### Connections

This connector is an enhanced service protocol and uses a virtual connection. It can be applied to a service that includes a NetInsight Nimbra V3 source and destination node.

## How to use

On the **Service Status** page, the computed severity is displayed as the standalone parameter **Severity**. By activating alarm monitoring on this parameter only, you can align the calculated severity with the overall severity of the service.

The two tables on this same page illustrate the health of the nodes associated with the service. The **Service Alarms** table itemizes the active alarms, while the **Service Element Status** table provides a list of monitored general information.

## Notes

This enhanced service protocol was designed for a specific project and is not expected to be reused in general.
