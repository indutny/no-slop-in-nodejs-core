# Petition to Node.js TSC: No AI code in Node.js Core

We, the undersigned, petition the Node.js Technical Steering Committee (TSC)
to vote **NO** on ["Is AI-assisted development allowed?"][0] and not accept
[LLM generated rewrites of core internals][1].

Node.js is a _critical infrastructure_ running on millions of servers online and
supporting engineers through command-line utilities that they use daily. We
believe that diluting the core hand-written with _care and diligence_ over
the years is against the mission and values of the project and should not be
allowed. Accepting LLM generated changes to Node.js core would break the
reputational bedrock of public contributions that have brought Node.js to its
current public standing and societal value.

## Background

[A 19k lines-of-code Pull Request][1] was opened in January, 2026. The
[author][2] is a well known and long time contributor to Node.js core, but the
Pull Request description has listed this sentence as a disclaimer:

> I've used a significant amount of Claude Code tokens to create this PR.
> I've reviewed all changes myself.

The [blog post][3] that surfaced on [Hacker News][4] that started a debate over
whether a change like that even satisfies the requirements of
[Developer's Certificate of Origin (DCO)][5]:

```text
By making a contribution to this project, I certify that:

 (a) The contribution was created in whole or in part by me and I
     have the right to submit it under the open source license
     indicated in the file; or

 (b) The contribution is based upon previous work that, to the best
     of my knowledge, is covered under an appropriate open source
     license and I have the right under that license to submit that
     work with modifications, whether created in whole or in part
     by me, under the same open source license (unless I am
     permitted to submit under a different license), as indicated
     in the file; or

 (c) The contribution was provided directly to me by some other
     person who certified (a), (b) or (c) and I have not modified
     it.

 (d) I understand and agree that this project and the contribution
     are public and that a record of the contribution (including all
     personal information I submit with it, including my sign-off) is
     maintained indefinitely and may be redistributed consistent with
     this project or the open source license(s) involved.
```

and even though the [legal opinion of OpenJS foundation][6] is that LLM assisted
changes are not in violation of DCO, we believe that this is only a small part of
the issue with large LLM-written changes to the Node.js core.

## Additional Concerns

#### Ethical

Major LLM companies use unethically sourced material for their training. This
includes copyrighted works, and unattributed Open Source code of varying
licensing.

#### Educational

There is evidence that use of LLM hinders learning process for students. Since
Open Source projects frequently on-board new contributors lowering the quality
bar of accepted code could lead to decreased understanding of the Node.js core
and risk project's longevity.

Additionally, the code review process exists not only to identify bugs, security
issues and to make the change conform to the style and architecture of the
project, but also to help the submitter learn and grow as a contributor.
However, LLM has no ability to learn so the time spent on review is repeatedly
wasted without advancing the contributor's skills.

#### Privilege

LLM use requires paid subscription or significant investment into hardware to
run it locally (albeit, with lower quality of output). Submitted generated code
should be reproducible by reviewers without having to go through the paywall of
subscription based LLM tooling.

## Sign the Petition

Your signature is important in making sure our voices are heard and the decision
that TSC makes reflects the opinion of Node.js community.

You can sign this petition by opening a Pull Request and adding your name at the
bottom of this README.md file, opening an issue, or on
[change.org](https://www.change.org/p/no-ai-code-in-node-js-core) if you prefer
to support us anonymously or don't have a github account.

Pull Requests will be merged throughout the day, but might be merged in bulk to
speed up the process.

## Signatures

- Fedor Indutny (Node.js TSC Emeritus Member)
- Jan Lehnardt (CEO Neighbourhoodie Software, PMC Chair Apache CouchDB (still powers parts of npm) & PouchDB, co-organiser JSConf EU, Node.js since Ryan announced it, presenting from my laptop)
- Paolo Fragomeni (Software Engineer)
- Samir Saeedi (Web Developer, Node.js user)
- Jamie Kyle (Open Source Developer, TC39 Invited Expert)
- Ellie Kanning
- Sean Scally (Programmer)
- Yasser Nascimento (Programmer)
- Tiziano Bettio (Programmer)
- Mikalai Birukou (Developer)
- Camden Kirkland (Programmer, Data Scientist, Technical Instructor)
- Daniel Escoz Solana (Programmer, working with Node.js since 2014)
- Andrew Kelley ([package maintainer](https://www.npmjs.com/~superjoe), President of [Zig Software Foundation](https://ziglang.org/zsf/))
- Petr Pechkurov (Developer)
- Ping Lu (Programmer)
- Denys Nykula (JS/TS Programmer)
- Bryan English (Node.js Core Collaborator, user since Ryan announced it)
- Andrew Benbow (Web Developer)
- Reilly Spitzfaden (Programmer, Node.js User)
- James Sumners (Open Source Developer)
- Jeremy Jenkins (Software Engineer)
- Oleg Kvampov (Node.js backend developer)
- Thomas Hunter II (author of Distributed Systems with Node.js)
- Anas Elgarhy (Software Engineer)
- Kęstutis Dambrauskas (Front-end developer)
- Jared White (Web Developer, Open Source Maintainer)
- Nick Asmodeus (Programmer, Node.js user)
- Anagh Pranshu (Web Developer, Open Source Enthusiast)
- Akhil Grandhi (Full Stack Developer)
- Jörn Zaefferer (Software Engineer)
- Claudius Coenen (Software Developer, Professor)
- Ben Vinnerd (Javascript/Typescript Developer)
- Brandon Berg (Systems Engineer)
- Nicolai Kamenzky (SaaS founder, depending on Node.js since 2014)
- Johnathan Stevers (Programmer)
- Dimitri Do Bairro (@Tictactrip founder, depending on Node.js since 2016)
- Stephen Smit (Software Engineering Manager)
- Jakub Żywiec (Software Developer)
- Anas Najaa (University Lecturer \ Software Developer)
- Haris Pasha Dipto (Software Engineer)
- Etienne Rouge (Software Engineer, Open Source Maintainer, depending on Node.js since 2017)
- Rebecca König (Software Developer)
- Christopher Jeffrey (Programmer)
- Noah Hall (Software Engineer, former Elm core team)
- Edward Loveall (Software Developer)
- Diogo Goncalves Silva (Software Engineer)
- Johan Alkstål (Software Developer)
- Niklas Koll (Web Developer)
- Samara Lima (Software Engineer)
- Taha Jumaah (Software Developer)
- Pierre-Olivier Marec (Software Engineer, Node.js user)
- Frazer Smith (Open Source Developer)
- LittleSnow (Front-end Developer)
- Lukas Downes (Software Developer)
- Eirik Berget Haukeland (Software Developer)
- Jēkabs Milbrets (Web Developer)
- Ajeet Pratap Singh (Open Source Developer)
- Shivam Veer (Software Engineer / DIYer)
- Niels Roesen Abildgaard (Staff Software Consultant)
- Jocelyn Badgley (Software Engineer)
- Daniel Fortes (Software Developer)
- Neil Craig (Technical Architect, used Node since 0.13)
- Griffin Johnston (Software Engineer, Node user since the early days)
- Radu "XPilot" Paraschiv (Software Architect, Node user since the 2010)
- Blaine Bublitz (Open Source Developer, Gulp Lead Maintainer)
- Hunter Perrin (Software Engineer, Owner, SciActive Inc / Port87)
- Artur Gawlik (Software Engineer)
- Imran Latif (Software Engineer)
- Jonathan Carle (Software Engineer, Open Source Developer)
- Debagnik Kar (Software Engineer, fullstack, IBM)
- Alexander Praetorius (Peer to Peer Engineer, Open Source Developer)
- Madeline Gurriarán (Programmer, Open Source Maintainer)
- Anthony C Howe (Software Developer)
- Filip Maj (Software Engineer)
- Gabriel Schmitt (Software Engineer)
- Jared Wilcurt (UI Architect, Node Library Developer, used Node since 0.10)
- Rishabh Dhawan (Software Developer)
- Matías Lescano (Software Developer)
- Matthias "Padcom" Hryniszak (Author of Ardupilot/node-mavlink library)
- Eldar Aliyev (Software Engineer)
- Kenneth G. Franqueiro (Software Engineer)
- José Silva (software developer)
- Attila Gonda (Software Engineer)
- Lee Ashmore (Software Engineer)
- Erik Westra (Developer)
- Andrei Mandrican (Developer)

[0]: https://github.com/openjs-foundation/cross-project-council/issues/1509
[1]: https://github.com/nodejs/node/pull/61478
[2]: https://github.com/mcollina
[3]: https://blog.platformatic.dev/why-nodejs-needs-a-virtual-file-system
[4]: https://news.ycombinator.com/item?id=47413195
[5]: https://github.com/nodejs/node/blob/e30928485e20769c1112c56d7bbabff9366f260e/CONTRIBUTING.md#developers-certificate-of-origin-11
[6]: https://github.com/nodejs/node/pull/61478#issuecomment-4077289061
