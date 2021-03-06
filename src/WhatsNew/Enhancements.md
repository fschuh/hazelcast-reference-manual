
### Enhancements

The following are the the enhancements performed for Hazelcast 3.6 release.

- **???**: ???
- **???**: ???
- **???**: ???


The following are the other improvements performed to solve the enhancement issues opened by the Hazelcast customers/team.
 
- `Map.Entry` supplied to Entry Processor is not Serializable any more. <a href="https://github.com/hazelcast/hazelcast/issues/5611" target="_blank">[5611]</a>
- The configuration file `minimal-json` with the provided scope is not picked up by the *shade* plugin. <a href="https://github.com/hazelcast/hazelcast/issues/5543" target="_blank">[5543]</a>
- In Spring configuration, when a boolean property is injected for *hazelcast* bean (`<hz:hazelcast:....</hz:hazelcast`)
a `SAXParse` exception is thrown. <a href="https://github.com/hazelcast/hazelcast/issues/5528" target="_blank">[5528]</a>
- Currently, key/value pairs are deserialized prior to the execution of entry processor by default.  This leads to the need of domain object at the server side, even if entry processor never uses it. <a href="https://github.com/hazelcast/hazelcast/issues/5301" target="_blank">[5301]</a>
- In Spring XML configuration, the attributes of `socket-options` should be of type `xs:string`. <a href="https://github.com/hazelcast/hazelcast/issues/4700" target="_blank">[4700]</a>
- `ClientMembershipEvent` does not need to have the `member` field. <a href="https://github.com/hazelcast/hazelcast/issues/4282" target="_blank">[4282]</a>
- Hazelcast has `lock` with lease time feature but does not support `tryLock` with lease time. <a href="https://github.com/hazelcast/hazelcast/issues/1564" target="_blank">[1564]</a>


