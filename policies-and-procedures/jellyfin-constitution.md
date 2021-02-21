# Jellyfin Consitution

Draft 1 of Version 1.0, 2021-02

Based on the Debian Constitution, available at https://www.debian.org/devel/constitution

## General Organizational Structure and Principles

1. The Jellyfin Project is organized into a heirarchical structure with the following layers, which shall be defined in more detail below:

      i. The Project Leader
     ii. The Leadership Team
    iii. The Financial Committee
     iv. Subproject Leaders
      v. Technical Committees
     vi. The Contributor Function Teams
    vii. The Contributor Team as a whole

2. In the list above, a person or body is usually listed before any people or bodies whose decisions they can overrule or who they (help) appoint - but not everyone listed earlier can overrule everyone listed later.

3. Nothing in this constitution imposes an obligation on anyone to do work for the Project. A person who does not want to do a task which has been delegated or assigned to them does not need to do it. However, they must not actively work against these rules and decisions properly made under them.

4. A person may leave the Project or resign from a particular post they hold, at any time, by stating so publicly.

5. A person may hold several posts at one time, and be part of as many teams as desired.

## Role Definitions and Powers

### Project Leader

#### Powers

1. The Project Leader is reposible for the overall management of the project direction and releases. They are bound by the terms of the Jellyfin Social Contract as much as any other member, and embody the spirit and goals of this social contract.

2. The Project Leader is the final arbiter in any disputes or decisions raised from lower teams and persons where such a decision cannot be reached by more collaborative means within the teams themselves.

3. The Project Leader shall generally take a hands-off approach to day-to-day project decisions, delegating responsibility for these to the lower teams and persons.

4. The Project Leader shall also function as Release Manager for the core server, handling the coordination and creation of new releases of the Jellyfin server software. Creation of releases for clients or subcomponents is delegated to their respective Function Teams.

5. The Project Leader must always be a member of both the Leadership Team and the Financial Committee.

#### Procedure

1. The first Project Leader (Joshua Boniface) was and is self-appointed, as the original driver of the fork from Emby.

2. The Project Leader shall serve indefinitely at their discretion, but may resign at any time.

3. Upon resignation or indisposal of the Project Leader, one or more candidates for the position shall be proposed by the Leadership Team. A vote shall then be held by all members of the Jellyfin Contrbutor Team to confirm or select the chosen candidate(s). The method of election shall be ranked voting instant runoff until one candidate has secured an absolute majority of the vote. In the event that only a single candidate is proposed, and this candidate does not gain a majority of votes amongst the Contributor Team, the outgoing Project Leader shall cast a deciding vote to confirm or deny the candidate outright. If the outgoing Project Leader does not confirm the candidate, the process shall begin again and the previous candidate is inelligible for further consideration.

4. The Project Leader may at their discretion appoint a temporary Interim Project Leader to handle their duties due to short-term absense or for the duration of a Projet Leader election.

### Leadership Team ("Core")

#### Powers

1. The Leadership Team is responsible for the day-to-day operations of the project and the handling of technical and managerial decisions for the project.

2. The Leadership Team is the only group with "Merge" permissions for the core server repositories, and are responsible for the merging of reviewed and approved Pull Requests into those repositories. All code changes must thus require implicit or explicit approval of a member of the Leadership Team.

3. The Leadership Team should at all times provide a unified front for decisions, working under the principle of democratic centralism - lively debate and disagreement within the team is encouraged during decisionmaking, but decisions should be accepted and promulaged by the team as a unified entity without public disagreement. If internal decisionmaking fails, the decision shall fall to the Project Leader instead.

#### Procedure

1. The initial Leadership Team was appointed by the first Project Leader during the creation of the project and has and shall continue to grow.

2. The Leadership Team should, but is not required to, include an odd number of active members to ensure majority decisions can be decided effectively.

3. New members can be proposed to the Leadership Team when required by the Project Leader. Once proposed, a vote shall be held by the members of the Leadership team to determine whether and which members should be added. The method of election shall be multiple-vote runoff, with each Leadership Team member casting a single vote for any number of proposed members, and the lowest-voted candidate eliminated until the desired number of candidates remain.

4. Members of the Leadership Team shall be removed from their position after 1 year of inactivity with the project, subject to discussion by the remaining Leadership Team members.

### Financial Committee

#### Powers

1. The Financial Committee is a sub-group of the Leadership Team who is in charge of allocating funds from the OpenCollective donation pool.

2. The Financial Committee shall decide which if any expenses are legitimate, as well as handle recurring expenses for the project such as infrastructure.

3. Any member of the Financial Committee shall have the power to approve or veto any expense. If a veto is used, the reasoning must be explained to the Leadership Team.

#### Procedure

1. The initial and current Financial Committee consists of Joshua Boniface, Andrew Rabert, and Anthony Lavado.

2. The Financial Committee shall always include exactly 3 members to ensure transparency in all funds allocations.

3. New members shall be proposed by the existing Financial Committee should the need arise, by direct nomination by the departing member. The new member must be confirmed unanimously by the remaining members.

### Subproject Leaders

#### Powers

1. Subproject Leaders are those members of the team with a leadership role in guiding a particular subproject. While the Project Leader guides the project as a whole, Subproject Leaders guide individual subprojects in a similar fashion. A subproject is any component of the Jellyfin ecosystem, under the Jellyfin Organization, which is not a part of the core server itself. This includes clients, libraries for 3rd party projects, or other similar repositories for which the Project Leader delegates this responsbility.

2. Subproject Leaders are responsible for the day-to-day operations of their subproject and the handling of technical and managerial decisions for the subproject. For the purposes of all decisions pertaining to the subproject exclusively, the Subproject Leader shall be responsible for the final decision, in consultation with the Project Leader if necessary.

3. Subproject Leaders shall have Admin privileges to the subproject repositories they manage and have the power to assign permissions on the subproject to other team members, for instance merge permissions, at their discretion.

4. Subproject Leaders should seek consensus wherever possible with other contributors to the subproject, however they are empowered to make decisions as required. Disputes may be escalated to the Leadership Team or Project Leader if desired for further decision and resolution. As outlined in power #2, the Subproject Leader shall have the final say in any decision reached here.

#### Procedure

1. The initial Subproject Leader for a subproject shall be determined depending on the source of the subproject.

     i. For subprojects that originate amongst the existing Jellyfin Project, for instance split-out libraries, or are forks of other projects, the subproject leader shall be determined by the Project Leader in consultation with the Leadership Team at the time the project is integrated into the Jellyfin Organization.

    ii. For subprojects that originate as the sole work of an existing Jellyfin Team member, that person shall become Subproject Leader at the time the project is transferred to the Jellyfin Organization.

   iii. For subprojects that originate as the sole work of an outside contributor who desires to make the project a subproject of the Jellyfin Organization, that person shall become a member of the Jellyfin Team, subject to standard nomination rules for Team Members, and shall become Subproject Leader at the time the project is transferred to the Jellyfin Organization. If nomination of the member fails for any reason, the project shall not be integrated into the Jellyfin Organization and shall remain a 3rd-party project.

    iv. For subprojects that, at the time of the adoption of this consitution, do not already have a clear Subproject Leader, elections shall be held by the existing contributors to select the Subproject Leader. The method of election shall be ranked voting instant runoff until one candidate has secured an absolute majority of the vote.

2. There shall always be exactly one Subproject Leader for any given project.

3. New Subproject Leaders shall be selected by the Project Leader, in consultation with the Leadership Team and existing subproject contributors, as required.

### Technical Committees

#### Powers

1. Technical Committees exist to facilitate day-to-day decisions on technical matters within the Jellyfin Project, and are empowered to make technical decisions related to their area of expertise.

2. Technical Committees shall consist of exactly 3 members, 1 of of whom shall be a member of the Leadership Team, and 2 of whom shall be chosen from the entire pool of Team Members based on technical proficiency, seniority, and proven decision-making skill.

3. Technical Committees shall make all decisions by consensus, and a consensus opinion shall be considered binding. In the case that a consensus cannot be reached, the decision shall be escalated to the Project Leader for a final decision. The Project Leader shall take into consideration the technical merits of the opposing sides when making this decision.

4. The exact list and nature of the Technical Committees shall be subject to decision by the Project Leader and Leadership Team as required, and Technical Committees shall be created or disolved as needed by the project as a whole.

### Contributor Function Teams

#### Powers

1. The Contributor Function Teams constitute the bulk of project members, and all new members in the Jellyfin Organization must be a member of at least one Function Team. A member may be a part of any number of Function Teams based on their skill-set and experience.

2. Members of Function Teams are responsible for the review of code Pull Requests and maintenance of Issues within their designated subprojects.

#### Procedure

1. Contributor Function Team members may be added to the project subject to the procedure outlined in [the New Team Member Nominations document](new-team-member-nominations.md).

### Contributor Team (whole)

#### Powers

1. The general group of project contributors consists of those who are members of the Jellyfin Organization on GitHub.

2. As a collective body, the contributors are responsible for performing whatever actions they deem necessary for the project to continue and improve, including writing code, triaging issues, proposing and managing feature requests, and supporting users and other team members with questions or assistance.
