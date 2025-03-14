# OmniRealms Games

This document provides comprehensive specifications for all games within the **OmniRealms** universe. Each entry includes the module name, Java package, description, gameplay features, technical specifications, and how it connects to the broader OmniRealms mythology of **Realms** and **Titans**.

---

## OmniRealm Forge
- **Module Name:** `omnirealms-game-forge`
- **Java Package:** `games.omnirealms.games.forge`

### Description
A voxel-based building and exploration game where players shape vast worlds using 1x1x1 blocks. Players can craft items, build structures, and explore procedurally generated realms. The game features a robust modding system and serves as a foundational platform for accessing other OmniRealms worlds through its unique block-based perspective. Through special portals or crafted devices, players can view and interact with the same realm data that other games access, but rendered in the Forge's voxel style.

### Specifications
- **Rendering Style:** Default Blocky style, with support for marketplace renderers
- **World Structure:** 16x16x16 voxel chunks, procedurally generated on client side
- **Multiplayer Support:** Real-time multiplayer with UDP for position updates, TCP for reliable transfers
- **Core Mechanics:**
  - Block placement, removal, and crafting
  - Resource gathering and inventory management
  - Portal creation for cross-scale and cross-game transitions
  - Custom tool creation and modification
- **Progression System:**
  - Experience-based leveling
  - Achievement tracking for milestones
  - Crafting recipe unlocks tied to exploration and achievements
- **Modding Support:**
  - Java-based mod API for custom blocks, entities, and mechanics
  - Community mod repository integration
  - Runtime mod loading without client restart
- **Portal Mechanics:**
  - Cross-scale portals to navigate between universe scales
  - Cross-game portals to experience other OmniRealms titles
  - Custom portal creation using special resources

---

## Story Book
- **Module Name:** `omnirealms-game-storybook`
- **Java Package:** `games.omnirealms.games.storybook`

### Description
Transforms children's books into interactive adventures using AI technology. Players upload books, enter ISBNs, or purchase from a digital library to bring stories to life, with animated characters and page-by-page gameplay. Maintains a book-like format with age-appropriate interactions, content filtering, and parental controls for kids under 13. Stories save to a digital bookshelf, blending literacy and digital play in a safe environment.

### Specifications
- **Rendering Style:** Storybook style with page-turning animations and 2.5D effects
- **Content Sources:**
  - User-uploaded PDF/EPUB books
  - ISBN lookup for automatic retrieval
  - In-game digital library with free and premium titles
- **AI Integration:**
  - Natural language processing for story understanding
  - Character recognition and animation from static illustrations
  - Adaptive interaction generation based on narrative context
- **Child Safety Features:**
  - Age-appropriate content filters (under 13)
  - Parental controls for time limits and content restrictions
  - Safe social features with pre-approved interaction options
- **Educational Elements:**
  - Reading comprehension activities
  - Vocabulary building through contextual highlighting
  - Interactive story elements that teach concepts from the narrative
- **Progression System:**
  - Digital bookshelf of completed stories
  - Reading achievements and comprehension tracking
  - Collectible characters and items from favorite stories
- **Social Features:**
  - Story sharing with friends (parent-approved)
  - Collaborative reading sessions
  - Custom story creation tools

---

## Frontiers of Mythic Dominion
- **Module Name:** `omnirealms-game-frontiers`
- **Java Package:** `games.omnirealms.games.frontiers`

### Description
A first-person shooter set in a mythic sci-fi universe, featuring large-scale battlefields where futuristic warriors harness the power of ancient **Titans** and traverse vast **Realms**. Includes competitive multiplayer modes, hero-based classes, and cooperative missions.

### Specifications
- **Rendering Style:** High-fidelity sci-fi with mythic elements and Titan-inspired architecture
- **Game Modes:**
  - Competitive team-based warfare (8v8, 16v16, 32v32)
  - Objective-based scenarios (capture points, payload escorts)
  - Cooperative campaign missions (1-4 players)
  - Battle Royale mode across fragmented Realms
- **Hero Classes:**
  - Titan Channelers - Combat specialists who directly channel Titan energies
  - Realm Walkers - Mobility experts who can create temporary portals
  - Technomancers - Support classes merging technology with Titan artifacts
  - Void Stalkers - Stealth operatives who utilize shadow Realm powers
- **Weapon Systems:**
  - Conventional projectile weapons with Titan-tech modifications
  - Energy weapons drawing power from Realm energies
  - Melee weapons infused with Titan essences
  - Special abilities unique to each hero class
- **Map Design:**
  - Multi-scale battlefields spanning different Realm types
  - Dynamic environment changes based on player actions
  - Destructible elements and terrain modification
  - Vertical gameplay with anti-gravity zones
- **Progression System:**
  - Character-specific ability trees
  - Weapon and gear unlocks through achievements
  - Cosmetic customizations reflecting Titan affinity
  - Seasonal ranking system with rewards

---

## Ascendant Racers
- **Module Name:** `omnirealms-game-ascendantracers`
- **Java Package:** `games.omnirealms.games.ascendantracers`

### Description
A futuristic racing game with anti-gravity vehicles, exotic interplanetary tracks, and high-octane tournaments. Players can customize their hovercrafts, leveraging advanced **Titan-derived** technologies for speed, and compete in solo or online leagues for galactic fame.

### Specifications
- **Rendering Style:** Sleek, high-speed futuristic visuals with motion blur and particle effects
- **Vehicle Types:**
  - Interceptors - Lightweight, agile craft with high acceleration
  - Enforcers - Medium-weight balanced vehicles with offensive capabilities
  - Juggernauts - Heavy vehicles with superior shield capabilities
  - Phantoms - Experimental craft with limited phase-shifting abilities
- **Track Environments:**
  - Gas giant atmospheric circuits
  - Asteroid field obstacle courses
  - Volcanic planet lava runs
  - Ancient Titan infrastructure tracks
  - Quantum-unstable ghost tracks
- **Customization System:**
  - Engine modifications affecting speed/acceleration
  - Shield generators with various properties
  - Hover system adjustments for handling
  - Weapon/defense modules for combat racing modes
  - Visual customization with decals and paint jobs
- **Racing Modes:**
  - Traditional circuit races
  - Elimination races with last place elimination intervals
  - Combat races with offensive/defensive capabilities
  - Precision time trials through difficult terrain
  - Team relay races across multiple track segments
- **Progression System:**
  - League-based advancement system
  - Sponsorship system with in-game benefits
  - Vehicle part unlocks through race placement
  - Reputation system affecting AI opponent behavior

---

## Chronoverse Legends
- **Module Name:** `omnirealms-game-chronoverselegends`
- **Java Package:** `games.omnirealms.games.chronoverselegends`

### Description
A Diablo-style action RPG where players traverse shifting timelines to defeat cosmic horrors and manipulate time-based abilities bestowed by the **Titans**. Boasts procedurally generated dungeons, robust loot systems, and cooperative play.

### Specifications
- **Rendering Style:** Isometric view with dynamic lighting and temporal effects
- **Character Classes:**
  - Chronomancer - Masters time manipulation with offensive magic
  - Void Walker - Utilizes dimensional rifts for mobility and control
  - Paradox Knight - Melee specialist with temporal echo abilities
  - Fate Weaver - Support class manipulating probability and timelines
  - Eternity Smith - Crafting specialist with artifact enhancement powers
- **Combat System:**
  - Real-time action with cooldown-based abilities
  - Combo system for chaining attacks and abilities
  - Time manipulation mechanics (slow, rewind, accelerate)
  - Environmental interactions using time powers
- **Procedural Generation:**
  - Dynamically created dungeons with unique layouts
  - Time-shifted versions of the same location
  - Alternate history scenarios affecting environment design
  - Fractal timeline dungeons with branching paths
- **Loot System:**
  - Tiered rarity system (Common to Legendary to Titan-class)
  - Procedurally generated stats with time-based effects
  - Set items with synergistic bonuses
  - Unique artifacts with story-based powers
  - Crafting materials for custom item creation
- **Progression System:**
  - Traditional level-based advancement
  - Skill trees with time manipulation specializations
  - Paragon-style infinite progression
  - Timeline achievement tracking

---

## Eternum Nexus
- **Module Name:** `omnirealms-game-eternumnexus`
- **Java Package:** `games.omnirealms.games.eternumnexus`

### Description
A large-scale, sci-fi shooter reminiscent of classic battlefront titles. Players engage in massive planetary invasions, space battles, and hero-based skirmishes—occasionally tapping into **Titan** powers—to shape the future of the galaxy.

### Specifications
- **Rendering Style:** Large-scale cinematic sci-fi with emphasis on massive battle scenes
- **Battle Scales:**
  - Ground combat with up to 64 players per team
  - Vehicle-based warfare with tanks, walkers, and aircraft
  - Space combat with fighters, bombers, and capital ships
  - Combined arms operations across multiple theaters
- **Faction System:**
  - The Eternal Dominion - Power-focused imperial force
  - Nexus Collective - Technology-driven democratic alliance
  - Void Cultists - Titan worshippers with mystical abilities
  - Independent Mercenaries - Neutral faction for hire
- **Hero System:**
  - Unique hero units for each faction
  - Special abilities tied to faction philosophy
  - Titan-empowered ultimate abilities
  - Strategic support powers affecting battlefield conditions
- **Game Modes:**
  - Conquest - Territory control across massive maps
  - Supremacy - Multi-objective combined arms warfare
  - Infiltration - Small-scale strategic objective missions
  - Titan Fall - Special mode where players can temporarily embody Titan powers
- **Progression System:**
  - Class-based advancement with specialization trees
  - Weapon and equipment unlocks through experience
  - Cosmetic progression showing veteran status
  - Command card system for strategic ability unlocks

---

## Celestial Safari
- **Module Name:** `omnirealms-game-celestialsafari`
- **Java Package:** `games.omnirealms.games.celestialsafari`

### Description
A creature-collecting and exploration adventure aimed at players of all ages. Features vibrant, alien biomes; friendly critters; and discovery-focused gameplay centered on peaceful interaction, scientific cataloging, and hidden nods to **Titan** lore.

### Specifications
- **Rendering Style:** Vibrant, stylized visuals with emphasis on creature personalities
- **Gameplay Loop:**
  - Exploration of procedurally generated biomes
  - Creature discovery and cataloging
  - Non-violent interaction and bonding mechanics
  - Habitat creation and ecosystem management
  - Scientific research and knowledge collection
- **Creature System:**
  - Over 200 base creature types with variants
  - Procedurally generated attributes and behaviors
  - Evolutionary adaptation to player actions
  - Creature bonding system with friendship levels
  - Special Titan-influenced legendary creatures
- **Biome Types:**
  - Crystal forests with bioluminescent flora
  - Floating islands with unique aerial ecosystem
  - Underwater caverns with pressure adaptations
  - Ancient Titan gardens with unusual physics
  - Quantum flux zones with phasing creatures
- **Research System:**
  - Field research through observation and interaction
  - Laboratory equipment for studying specimens
  - Knowledge tree unlocking new research tools
  - Titan lore discoveries hidden throughout biomes
- **Progression System:**
  - Explorer rank advancement
  - Creature collection completion rewards
  - Habitat development and ecosystem health tracking
  - Research breakthrough achievements

---

## Tactical Imperium
- **Module Name:** `omnirealms-game-tacticalimperium`
- **Java Package:** `games.omnirealms.games.tacticalimperium`

### Description
A strategy experience where players command vast armies across interstellar frontiers. From resource management to planetary conquests, Tactical Imperium blends RTS elements with a grand strategy twist, allowing leaders to forge alliances—and invoke **Titanic** forces—across multiple Realms.

### Specifications
- **Rendering Style:** Detailed strategic map view with zoomed tactical battle scenes
- **Game Scales:**
  - Galactic view for empire management
  - System view for planetary development
  - Tactical view for battle management
  - Timeline view for historical analysis
- **Faction Characteristics:**
  - Unique architectural styles and unit designs
  - Special abilities reflecting cultural philosophies
  - Economic and technological specializations
  - Titan affinity determining special powers
- **Resource Systems:**
  - Traditional resources (minerals, energy, food)
  - Strategic resources with special properties
  - Influence as diplomatic currency
  - Titan essence for powerful abilities
- **Combat System:**
  - Real-time tactical battles with pause functionality
  - Unit formations and terrain considerations
  - Special abilities and counter systems
  - Titanic interventions as strategic options
- **Diplomacy System:**
  - Complex AI negotiations
  - Alliance formation and management
  - Trade agreements and resource sharing
  - Espionage and sabotage operations
- **Progression System:**
  - Technology research trees
  - Leader development and traits
  - Empire traditions and policies
  - Historical achievement tracking

---

## Paragon Spheres
- **Module Name:** `omnirealms-game-paragonspheres`
- **Java Package:** `games.omnirealms.games.paragonspheres`

### Description
A puzzle-platformer and racing hybrid featuring spherical worlds, physics-based challenges, and an arcade-like progression system. Some spheres may even be remnants of **Titan** influence, testing reflexes and creativity across a series of colorful environments.

### Specifications
- **Rendering Style:** Colorful, smooth visuals with emphasis on sphere physics and momentum
- **Level Types:**
  - Racing spheres with time trial challenges
  - Puzzle spheres requiring specific movement solutions
  - Combat spheres with enemy obstacles
  - Collection spheres with hard-to-reach objects
  - Titan trial spheres with altered physics rules
- **Movement Mechanics:**
  - Momentum-based rolling physics
  - Jump and boost abilities
  - Surface adhesion for 360-degree traversal
  - Special abilities unique to different sphere types
- **Sphere Customization:**
  - Material properties affecting physics
  - Visual customization with patterns and effects
  - Special ability loadouts for different challenges
  - Size and weight modifications
- **Game Modes:**
  - Story mode with progressive challenges
  - Time Attack for speedrunning
  - Multiplayer races with up to 8 players
  - Custom sphere creator mode
- **Progression System:**
  - Star ratings for level completion
  - Unlockable sphere types and abilities
  - Challenge medal system for difficult feats
  - Paragon ranking for competitive players

---

## Ricochet Nexus
- **Module Name:** `omnirealms-game-richochet`
- **Java Package:** `games.omnirealms.games.ricochet`

### Description
A social-action simulation where players engage with the "Ricochet" app - a **Titan**-powered gig economy platform that matches users with missions based on their experience level and skills. Players start with simple tasks and gradually unlock higher-tier opportunities, building their reputation from Level 1 to 30. Each player adopts a unique handle (like "Nkl-n-D1med" or "Ashes2Ashes") and navigates a complex web of procedurally generated missions ranging from mundane courier jobs to high-stakes corporate infiltration. The game features a dual economy where players balance regular work with Ricochet contracts, each affecting their standing in both worlds. The **Realms**' influence manifests through a mysterious AI system that seems to have its own agenda, using the platform to orchestrate elaborate scenarios across the city. Features dynamic mission generation, branching narratives, and a robust reputation system where actions in one mission cascade into future opportunities.

### Specifications
- **Rendering Style:** Urban cyberpunk with augmented reality interface elements
- **Mission Categories:**
  - Courier - Package delivery across the city
  - Extraction - Retrieving objects or people from locations
  - Protection - Guarding assets or individuals
  - Investigation - Gathering information or evidence
  - Infiltration - Accessing restricted areas
  - Sabotage - Disrupting operations or systems
- **Progression Tiers:**
  - Street Level (1-5): Basic local missions
  - District Fixer (6-10): Area-wide operations
  - City Operator (11-15): Cross-district contracts
  - Shadow Agent (16-20): Corporate-level missions
  - Nexus Elite (21-25): High-risk, high-reward contracts
  - Titan Touched (26-30): Reality-bending special assignments
- **Reputation System:**
  - Success rating affecting future contract availability
  - Faction standings with various organizations
  - Specialization reputation in different mission types
  - Client relationship tracking with recurring characters
- **Economy System:**
  - Dual currency (regular credits and Ricochet tokens)
  - Equipment purchases and upgrades
  - Safe house property acquisition
  - Investment opportunities affecting passive income
- **Character Development:**
  - Skill tree focusing on different approaches
  - Equipment loadouts for mission specialization
  - Augmentation system for character enhancement
  - Contact network building for mission advantages

---

## Cosmoria Tales
- **Module Name:** `omnirealms-game-cosmoriatales`
- **Package:** `games.omnirealms.games.cosmoriatales`

### Description
A whimsical, family-friendly adventure in a hand-drawn magical world. Players undertake story-driven quests, meet friendly NPCs, and explore **Realms**-inspired lore, including tales of legendary **Titans**, in a safe setting for children and casual players.

### Specifications
- **Rendering Style:** Hand-drawn, storybook aesthetic with watercolor-like environments
- **Story Structure:**
  - Episodic adventures in the world of Cosmoria
  - Character-driven narratives with moral lessons
  - Progressive difficulty suitable for growing skills
  - Gentle introduction to Titans and Realms mythology
- **Gameplay Mechanics:**
  - Simple puzzle-solving for all ages
  - Light platforming elements with forgiving controls
  - Collection-based objectives with meaningful rewards
  - Non-violent conflict resolution mechanics
- **Character System:**
  - Customizable protagonist with age-appropriate options
  - Companion creatures with helpful abilities
  - Friendly NPC mentors guiding the journey
  - Legendary figures inspired by Titan mythology
- **World Design:**
  - Safe, enclosed exploration zones
  - Interactive environments with hidden surprises
  - Day/night cycle affecting available activities
  - Seasonal events with special quests
- **Educational Elements:**
  - Reading comprehension through story progression
  - Problem-solving skills through puzzles
  - Emotional intelligence through character interactions
  - Basic mythology and storytelling concepts
- **Family Features:**
  - Co-play mode for parent-child gaming
  - Adjustable difficulty settings
  - Reading assistance for younger players
  - Progress tracking for parents

---

## Quantum Drift
- **Module Name:** `omnirealms-game-quantumdrift`
- **Package:** `games.omnirealms.games.quantumdrift`

### Description
A puzzle-exploration game at the quantum scale. Players manipulate superposition and entanglement to navigate microscopic realms, uncovering **Titan** secrets embedded in the fabric of reality.

### Specifications
- **Rendering Style:** Abstract, particle-based visuals with quantum wave functions
- **Quantum Mechanics:**
  - Superposition puzzles requiring multiple states
  - Entanglement mechanics linking distant objects
  - Observer effect changing environments when viewed
  - Quantum tunneling for bypassing barriers
  - Probability manipulation affecting outcomes
- **Scale Progression:**
  - Atomic level exploration with electron puzzles
  - Subatomic adventures requiring quantum mechanics
  - Quantum foam navigation at Planck scales
  - Theoretical multi-dimensional spaces
- **Puzzle Types:**
  - Wave-particle duality challenges
  - Uncertainty principle navigation
  - Quantum computing simulations
  - Reality fabric repair scenarios
- **Discovery System:**
  - Titan micro-inscriptions hidden at quantum scales
  - Fundamental force manipulation records
  - Reality creation experiment documentation
  - Quantum communication networks
- **Progression System:**
  - Quantum understanding levels
  - Observation tool upgrades
  - Probability manipulation abilities
  - Reality anchoring techniques

---

## Titan's Legacy
- **Module Name:** `omnirealms-game-titanslegacy`
- **Package:** `games.omnirealms.games.titanslegacy`

### Description
A narrative-driven adventure tracing the fall of the **Titans**. Players explore ancient **Realms**, solve mysteries, and wield fading **Titanic** powers to restore or reshape history.

### Specifications
- **Rendering Style:** Ancient, ethereal aesthetics with remnants of advanced technology
- **Narrative Structure:**
  - Multi-era storyline across Titan civilization periods
  - Memory fragment collection revealing historical truth
  - Branching storylines based on player choices
  - Multiple endings affecting the OmniRealms universe
- **Power System:**
  - Diminishing Titan abilities requiring careful usage
  - Ancient artifacts amplifying specific powers
  - Power restoration through historical correction
  - Reality manipulation with consequences
- **Exploration Mechanics:**
  - Archaeology-like investigation of ruins
  - Environmental puzzles revealing hidden areas
  - Timeline analysis showing cause and effect
  - Reality fracture navigation
- **Character Development:**
  - Memory recovery affecting available abilities
  - Relationship building with Titan echoes
  - Moral choices defining legacy interpretation
  - Specialization in different Titan disciplines
- **World Design:**
  - Ancient Titan homeworlds
  - Reality engineering laboratories
  - Dimension intersection nexus points
  - Time-fractured battlefields
- **Progression System:**
  - Legacy understanding levels
  - Titan discipline mastery
  - Historical accuracy rating
  - Reality stability metrics

---

## Galactic Forge
- **Module Name:** `omnirealms-game-galacticforge`
- **Package:** `games.omnirealms.games.galacticforge`

### Description
An expanded sandbox at cosmic scale. Players craft planets, stars, and galaxies using voxel tools, guided by **Titan** blueprints, with multiplayer collaboration or competition.

### Specifications
- **Rendering Style:** Cosmic-scale voxels with astronomical lighting effects
- **Creation Tools:**
  - Celestial body formation tools
  - Galaxy structure manipulation
  - Star system arrangement interfaces
  - Planetary surface detailing
  - Life seeding mechanisms
- **Scale System:**
  - Galaxy-level editing with cluster tools
  - Star system detailed manipulation
  - Planetary surface voxel placement
  - Seamless zooming between scales
- **Cosmic Physics:**
  - Gravity simulation affecting creations
  - Star lifecycle management
  - Planetary orbit stability mechanics
  - Galaxy collision simulation
- **Blueprint System:**
  - Titan-derived templates for stable creations
  - Discoverable blueprints from exploration
  - Blueprint modification and customization
  - Blueprint sharing with other players
- **Multiplayer Features:**
  - Collaborative universe building
  - Competitive galaxy contests
  - Shared universe persistent states
  - Creation attribution and history
- **Progression System:**
  - Cosmic architect ranking
  - Tool unlocks through achievements
  - Material discovery from cosmic events
  - Creation complexity challenges

---

## Echoes of the Void
- **Module Name:** `omnirealms-game-echoesvoid`
- **Package:** `games.omnirealms.games.echoesvoid`

### Description
A survival horror game in abandoned **Realms**. Players face cosmic entities tied to **Titan** experiments, scavenging resources and unraveling a dark legacy.

### Specifications
- **Rendering Style:** Dark, atmospheric visuals with reality distortion effects
- **Horror Elements:**
  - Psychological horror based on reality uncertainty
  - Cosmic entities defying comprehension
  - Environmental storytelling through decay
  - Limited resources increasing tension
  - Sanity system affected by encounters
- **Gameplay Loop:**
  - Resource scavenging in hostile environments
  - Safe zone creation and fortification
  - Entity avoidance and distraction
  - Research to understand encounters
  - Reality anchoring to prevent dissolution
- **Enemy Types:**
  - Failed Titan experiments
  - Reality fracture manifestations
  - Corrupted Realm guardians
  - Void-touched former inhabitants
  - The Nameless (primary antagonist force)
- **Equipment System:**
  - Reality anchoring devices
  - Perception filters for entity avoidance
  - Memory recorders for information preservation
  - Makeshift weapons with limited effectiveness
  - Titan artifacts with powerful but corrupting effects
- **Narrative System:**
  - Journal fragments revealing backstory
  - Environmental storytelling through scenes
  - Audio logs from previous explorers
  - Vision sequences triggered by locations
- **Progression System:**
  - Knowledge level of Void phenomena
  - Equipment upgrades through scavenging
  - Safe zone expansion and improvement
  - Survival skills enhancement

---

## Nexus Arena
- **Module Name:** `omnirealms-game-nexusarena`
- **Package:** `games.omnirealms.games.nexusarena`

### Description
A MOBA-style game with **Titan**-infused champions. Teams battle across procedurally shifting arenas, leveraging unique abilities and **Realms**-based objectives.

### Specifications
- **Rendering Style:** Vibrant, strategic view with distinctive character designs
- **Match Structure:**
  - 5v5 team competition
  - 3-lane shifting arenas
  - 20-30 minute match duration
  - Objective-based victory conditions
- **Champion System:**
  - 50+ unique champions at launch
  - Each tied to a specific Titan aspect
  - 4 active abilities plus passive
  - Ultimate ability channeling Titan power
  - Role-based design (Tank, Support, Carry, etc.)
- **Realm Interaction:**
  - Arena shifts during matches
  - Environmental hazards and benefits
  - Neutral objectives tied to Realm properties
  - Resource nodes with strategic value
- **Progression System:**
  - In-match leveling and itemization
  - Account progression with unlocks
  - Seasonal ranking with rewards
  - Champion mastery tracking
- **Competitive Features:**
  - Ranked ladder system
  - Tournament support
  - Spectator mode with analytics
  - Replay system for match analysis
- **Champion Customization:**
  - Visual skins reflecting alternate realities
  - Ability effect modifications
  - Voice line sets and animations
  - Champion-specific quests and achievements
