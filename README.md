

# Why I created this repository

For a lot of social online activity there are Free (if you don't count paying with private Data) Solutions, that more or less reliably Work. 

It's different with dating Plattforms even though most of my (queer, female and male) Friends are using or have used Dating Apps in the past, all of them more or less hate hate these apps. Basically they want you to pay for every step, they don't reliably work, they sell all your data and allmost all of them belong to to the same few profit over everything parent companies. After a frustrating conversation with a friend I sat down and brainstormed how a good, non-comercial, FOSS (**F**ree **O**pen **S**ource **S**oftware) Dating App could look.
I definetly don't have the capacity for this amount of software development and the experience at this stage in my life to do this on my own. But I can at least share the Ideas I had, with the open source community and with some tons of luck something might emerge.

# Goals
- All GNU Open Source: Server and Client(s)
- All Free
- Protecting personal Data
- Non-Platform, decentralized, like mastodon the rest of the fediverse or email, connecting with people on other servers/nodes
- Compensating for gender roles in our society (Patriarchy exists! Trans Right & Trans Inclusivity!)
- Informing about menteal health risks of online dating, counteracting harmful atractivity and gender based market dynamics in a meaningful way. 
- Sexwork should be allowed on the platform but seperated from the usual Dating stuff

# Ideas and Concepts
Ideas and Cocepts to create a decentrelised Free Open Source user orienrented Dating Software

- Seperating profiles in a private and a public part
  - Public part includes one photo, and a tiny bio
  - Users should be educated, that the public part is visble to the world, and that they should upload or share nothing there by which they could be identified
  - Private profiles includes and arbitrary amount of information
- Every user has a private-public-keypair (only on their devices)
  - All Data saved in the Private Profile part is uploaded encrypted with their public key
- Swiping like everywhere but different:
   - When you are in the swipe screen you see the public information of a person
   - If you swipe right the Person get's a notification and you additionaly encrypt all your private profile information with their public key
   - If they swipe right on you, you can see each others complete profiles. And decide weather you wanna start a conversation.
- Match percentage like on OkCupid?
   - A lot of personal information has to be secured
   - it has to be accessed to choose whom to show to whom
   - Maybe some secure multiparty computation technology?

   
### Conceptional problems so far
   
#### Evil instances:
Ideas how to deal with evil instaced eg. if somone starts an instance with moified code and an infinite amount of fake accounts:
  - Ring of trust between instances?
  - Blockchain with user registrations? Proof of stake validation?

#### Content Moderation
- A different blockchain for flagging users?



# Participating

Mostely I need support from somewhat experienced coders right now, if you're not a programmer you can help by voicing support for the project and generate outreach, just write a tweet etc. Also you can just add suggestions and comments by creating an [issue](https://github.com/foss-non-comercial-dating/ideas/issues/new).



