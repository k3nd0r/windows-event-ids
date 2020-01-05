# Sysmon

[TOC]

## Event IDs
| Event ID      | Description           |
| ------------- | ------------- |
| [1](1.md) | Process creation |
| [2](2.md) | A process changed a file creation time |
| [3](3.md) | Network connection      |
| [4](4.md) | Sysmon service state changed |
| [5](5.md) | Process terminated |
| [6](6.md) | Driver loaded |
| [7](7.md) | Image loaded |
| [8](8.md) | CreateRemoteThread |
| [9](9.md) | RawAccessRead |
| [10](10.md) | ProcessAccess |
| [11](11.md) | FileCreate |
| [12](12.md) | RegistryEvent (Object create and delete) |
| [13](13.md) | RegistryEvent (Value Set) |
| [14](14.md) | RegistryEvent (Key and Value Rename) |
| [15](15.md) | FileCreateStreamHash |
| [17](17.md) | PipeEvent (Pipe Created) |
| [18](18.md) | PipeEvent (Pipe Connected) |
| [19](19.md) | WmiEvent (WmiEventFilter activity detected) |
| [20](20.md) | WmiEvent (WmiEventConsumer activity detected) |
| [21](21.md) | WmiEvent (WmiEventConsumerToFilter activity detected) |
| [22](22.md) | DNSEvent (DNS query) |
| [225](255.md) | Error |

## Popular Sysmon Configuration Files/Templates

 - [SwiftOnSecurity](https://github.com/SwiftOnSecurity/sysmon-config)
 - [sysmon-modular](https://github.com/olafhartong/sysmon-modular)
 - [ionstorm](https://github.com/ion-storm/sysmon-config)

## Projects using Sysmon

### HELK - [Cyb3rWard0g](https://github.com/Cyb3rWard0g)

 - [HELK GitHub](https://github.com/Cyb3rWard0g/HELK)
 - [Write-up](https://posts.specterops.io/real-time-sysmon-processing-via-ksql-and-helk-part-1-initial-integration-88c2b6eac839)



## Other Documentation and Information
 - [Official Documentation](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) - Microsoft
 - [Getting Started with Sysmon](https://www.blackhillsinfosec.com/getting-started-with-sysmon/) - Black Hills Information Security
 - ["How to Go from Responding to Hunting with Sysinternals Sysmon"](https://onedrive.live.com/view.aspx?resid=D026B4699190F1E6!2843&ithint=file%2cpptx) - Mark Russinovich