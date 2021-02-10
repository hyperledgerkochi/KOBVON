<h1>Things Learnt</h1>
<ul>
<li><p>The user id and password are highly susceptible to attacks. 
Personal information and identifiers we have that we could use to prove our identity are not trusted because it's impossible to tell if the data was actually issued to the person entering it and it requires  in-person delivery of this paper documents. 
All these are highly time consuming, costly and expensive and are highly vulnerable to be misused.</li> <p>
<li><p><b>Decentralized identifiers (DIDs)</b> are a new type of identifier that enables verifiable, decentralized digital identity. 
A DID identifies any subject (e.g., a person, organization, thing, data model, abstract entity, etc.) that the controller of the DID decides that it identifies.</li><p>
<li><p><b>Verifiable credentials</b> are a collection of claims and Meta data that are tamper-resistant and where issuance is cryptographically validated and secured.</li><p> 
<li><p><b>Self-sovereign identity (SSI)</b> is a concept in the digital movement that only the user should own their identity data fully without intervention from outside administration.</li><p>
<li><p><b>Zero-knowledge proof or zero-knowledge protocol</b> is a method by which one party can prove to another party that they know a value x, without conveying any information apart from the fact that they know the value x.</li><p>
<li><p>Websites can use DIDs and verifiable credentials to get enough information about users to establish sessions. Using DIDs and verifiable credentials are a lot easier and safer for users than passwords.</li><p>
<li><p>By the Presentations of claims from verifiable credentials, and knowing who issued the credentials we can trust the claims to be correct. This is based on the four attributes.</li><p> 
•	Who issued the credential?
•	The credential was issued to the entity presenting it.
•	The claims were not tampered with.
•	The credential has not been revoked
.
<li><p>We can use verifiable credentials online instead of paper documents in-person.</li><p>
<li><p>The trust of the claims is in cryptography and knowing about the issuer. People don’t have to be experts at detecting forgeries.</li><p>
<li><p>By using private DIDs and verifiable credentials based on ZKPs, we can radically reduce the online correlation that is happening today.</li><p>
<li><p>If high value data is only accepted when presented as a claim from a verifiable credential, there is no value in having data from breaches.</li><p>
<li><p>You create your own DIDs and those identifiers cannot be taken away by a centralized authority. You control your DIDs, no one else.</li><p>
<li><p><b>Hyperledger Indy</b> : Hyperledger Indy is the first project in the Hyperledger family to build a decentralized identity. Its architecture is based on self-sovereign identity which enables users to have complete control over their identity.</li><p> 
<li><p><b>Hyperledger Ursa</b>: Since Hyperedger Indy is using lots of cryptography libraries which can be reused in other Hyperledger platforms, so the aim of Hyperledger Ursa is to build a modular cryptography tool which can be plugged in any other blockchain technologies. Most of the Ursa code has been migrated from indy.</li><p>
<li><p><b>Hyperledger Aries</b>: Indy is good to build an identity solution but what it lacks is a peer to peer communication which is the heart of identity solution. Aries has filled this part, which enables two users to share identity information over a secured communication channel.</li><p>
<li><p>Aries agents used by individuals and online services exchange DIDs, verifiable credentials and to identify peers each time they connect.<br> Ursa cryptography underlies the exchange.<br>Indy credentials are exchanged as needed.</li><p>
<li><p>Services can use their Aries agent to connect with when collecting information from users, request and receive back proofs of claims from a users Aries agent.</li><p>
<li><p>The cryptographic guarantees from Ursa and Indy inherent in the proving of claims allows for the delivery (via Aries agents) of digital data in place of paper and the verification of claims replace human verification.</li><p>
<li><p>Aries agents use private, secure messaging to enable interactions without monitoring or correlation exposure.<br> Indy credentials use ZKPs to reduce correlation when proving credentials.<br> Ursa provides the necessary cryptographic primitives to support Aries messaging and Indy credentials.</li><p>
<li><p>Aries agents make it easy to decentralize the data, giving it to the subject of the data (us!) to use how and when we want. At the same time, this frees organizations currently managing those repositories from the liability of holding such toxic data.<br> Indy provides the credentials that ensure that the data provided by the subject can be trusted.<br> Ursa provides the cryptography to support the Indy credential model.</li><p>
<li><p>Aries enables you to create (and delete) DIDs that you share with others how and when you want.<br> Indy allows you to put those DIDs on a global ledger for others to access, if that is necessary.<br> Ursa provides the cryptography that allows you to prove control over those identifiers.</li><p>
</ul>
