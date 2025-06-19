Active directory is directory service tha stores, list and organizes the informationabout element in microsoft environment such as applications users and user account details, suchas
as names phone numbers and passwords with all the informations, actove directory provides an authentication and authoroization system to the metwork resources. 
once the authentication is done, the user can the access the requisted  resource and data he is permitted to view or use(this is the authorization part means AD he[ls to control 
who can access which resources.
The information stored in tactive directory, is refered to us 'Ad objects' 
They are primarly catagorized in to 3 types
1 users
2 resources: represent hardware elements ont he company
3 groups: designed to create lists of users for assigning them rights or services. 
                Active Directory Objects
             A. users
             B. Printers
             C. Computers,
             D File-sharing servers
users and resoiurces are organized into groups and subgroups
                                           Domain
 AD objects ar econtained within Domains: w/c are authonomus management entities.
 Domains are represented using a triangle. 
                                      Organizational units(OU)
 Objects are classified into OU. OU's Can represent various aspects of a company such as departmnets subsidiaries IT resource, users, geographical areas, & mpore.
                                    Group policy Objects(GPOs)
GPOs are a collection of a policy settings that ensble the restrivtion of actions like restricting access to a ccetain resources or foolders, disabling the use pf specific
exectables and more. GOPs can be applied to domains or OUs. THis is WHy Ad is essential for system administrorators. It is administrationa & network management tool that 
simplifies the management of users and security policies
                                       Tree
Ad tree coresponds to a domain, which we just discussed, along with all its subdomains, known as child domains. It is part of more extensive structure reffered to as a 
Forest.
                                     Forest
Means that the forest encompasss the trees. to enable userfrom one domain to Access resources in another,AD employs  a mechanism called 'trust relationship' to grant permission
in a different domain from the one containing the user's domain. This trust relationshios can take various forms, such as intra-forest, inter forest or inter sundomain relationships
between meultiple forests. A user fdrom one domain can have permissions in anyb domain wihtin the forest. It a also means that each domain is aware of the relationship it has
with the other domains in the forest. 
Example:
                            Forest-company
                              Tree- Fance
                                Domqin- Paris
                                Domain- Bordeaux
                              Tree-United States
                                Domain- New york
                                Domain- chicago
                                  OU-Marketing
                                    . James
                                  OU- Human resources
                                    .Jessica
                                    .Sarah
      Physical structure of AD
AD architecture relies on DOmain controller. AD structure is based on multiple domain controllers that synchronize sirectory data between them, ensuring information consistency
thriugh out the forest, domain controllers handles the communication users and domains, including user login processes, authentiation,a nd directory searches
         READ only DOMAIN Controller(RODC)
on a remote site it allew users to access network resource much faster while ensuring the security and integrity of the AD.


         


















                                          
             
