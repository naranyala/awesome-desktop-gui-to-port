# Awesome Desktop GUIs to Port

A curated inspiration catalog of desktop apps, system interfaces, and developer tools worth **reimagining with JavaFX**. Use these projects to study workflows and interaction design—not to copy proprietary code, branding, or assets. “Port” means an independent adaptation or implementation.

> Licensing, pricing, and supported platforms change. Verify upstream terms before using code, assets, or APIs. Commercial products are included as design references, not as claims of free availability.

## Contents

- [How to use this catalog](#how-to-use-this-catalog)
- [Real desktop apps to study](#real-desktop-apps-to-study)
  - [Productivity, writing, and knowledge](#productivity-writing-and-knowledge)
  - [Files, system, and utilities](#files-system-and-utilities)
  - [Creative and media](#creative-and-media)
  - [Developer, data, and operations tools](#developer-data-and-operations-tools)
  - [Communication and collaboration](#communication-and-collaboration)
  - [More categories to explore](#more-categories-to-explore)
- [JavaFX implementation toolbox](#javafx-implementation-toolbox)
- [Project ideas by difficulty](#project-ideas-by-difficulty)
- [Research and contribution notes](#research-and-contribution-notes)

## How to use this catalog

Pick a workflow, not an entire product. Recreate one coherent slice—such as a Git staging view, audio selection tool, or library filter—then validate it before expanding. Strong JavaFX exercises include keyboard navigation, accessible controls, background work, data virtualization, persistence, and cross-platform packaging.

Entries span different languages and business models. “Open source” does not automatically mean unrestricted reuse; commercial/proprietary applications can still be valuable interaction references.

## Real desktop apps to study

### Productivity, writing, and knowledge

| App | What makes it worth studying | JavaFX adaptation | Availability / notes |
|---|---|---|---|
| [Obsidian](https://obsidian.md/) | Local vault model, backlinks, graph, plugin ecosystem | Markdown workspace with backlinks and optional graph | Proprietary; free for personal use, commercial services/licensing vary |
| [Joplin](https://joplinapp.org/) | Notebooks, Markdown, attachments, sync status | Local-first notes with editor/preview, tags, import/export | Open source; check repository license and third-party components |
| [Logseq](https://logseq.com/) | Outliner-first notes, journals, block references | Daily journal with nested blocks and reference navigation | Open source; verify current license and project status |
| [Zettlr](https://www.zettlr.com/) | Academic writing, citations, project organization | Markdown research writer with bibliography and export | Open source; verify current licensing |
| [Zotero](https://www.zotero.org/) | Collection trees, metadata, attachments, citation workflows | Reference manager for local BibTeX/RIS with item inspector | Free/open-source application; check current license and connector terms |
| [Calibre](https://calibre-ebook.com/) | Large-library management, metadata editing, batch operations | E-book catalog with filters, cover grid, and bulk edit | Open source; check license and format-related terms |
| [KeePassXC](https://keepassxc.org/) | Vault state, credential editing, security cues | Vault UI prototype or vetted-library-backed password manager | Open source; security-critical—never invent cryptography |
| [Things](https://culturedcode.com/things/) | Calm task hierarchy, shortcuts, polished empty states | Focused task manager with projects, areas, and scheduling | Commercial, Apple platforms; excellent UX reference |
| [Microsoft OneNote](https://www.microsoft.com/microsoft-365/onenote/) | Freeform pages, inking, notebook navigation | Structured notebook with page tree and canvas-like editor | Proprietary; availability and included features vary |
| [ProjectLibre](https://www.projectlibre.com/) | Scheduling grids, dependencies, Gantt chart | Task scheduler with timeline, dependency links, zoom | Open-source and commercial offerings; verify edition/license |
| [Freeplane](https://www.freeplane.org/) | Mind-map navigation, keyboard editing, folding | Mind map with node creation, folding, and export | Open source; check current license |

### Files, system, and utilities

| App | What makes it worth studying | JavaFX adaptation | Availability / notes |
|---|---|---|---|
| [KDE Dolphin](https://apps.kde.org/dolphin/) | Split views, locations, tabs, previews, operation feedback | Two-pane file browser with safe operation queue | Open source; KDE project |
| [GNOME Files](https://apps.gnome.org/Files/) | Breadcrumb navigation and approachable file operations | Browser with location bar, bookmarks, and clear error states | Open source; GNOME project |
| [Double Commander](https://doublecmd.sourceforge.io/) | Configurable dual panes and power-user commands | Keyboard-first file manager with synchronized navigation | Open source; verify current license |
| [FreeCommander](https://freecommander.com/) | Dense dual-pane file operations | File-operation prototype with queue and shortcuts | Proprietary freeware/commercial editions; Windows |
| [LocalSend](https://localsend.org/) | Nearby transfer trust, device selection, progress | LAN transfer UI with explicit device confirmation | Open source; verify platform support and license |
| [ShareX](https://getsharex.com/) | Capture history, annotation, repeatable workflows | Screenshot organizer with crop/markup/export presets | Open source; Windows-focused |
| [Microsoft PowerToys](https://learn.microsoft.com/windows/powertoys/) | Utility suite, settings hub, discoverability | Launcher plus one module, e.g. bulk rename or color picker | Open source; Windows |
| [KDE Connect](https://kdeconnect.kde.org/) | Device pairing and cross-device actions | Device dashboard, starting with one capability | Open source; platform integration varies |
| [BleachBit](https://www.bleachbit.org/) | Explainable cleanup categories and preview | Disk-usage analyzer with preview-first recommendations | Open source; destructive cleanup needs special care |
| [Raycast](https://www.raycast.com/) | Launcher, fuzzy search, actions, extensions | Keyboard-first command palette with pluggable actions | Proprietary; free and paid plans/features vary |

### Creative and media

| App | What makes it worth studying | JavaFX adaptation | Availability / notes |
|---|---|---|---|
| [Krita](https://krita.org/) | Brush/tool organization, layers, dockers | Layered image viewer with selection, crop, undo | Open source |
| [GIMP](https://www.gimp.org/) | Image operations and dockable panels | Batch image processor with preview and operation stack | Open source |
| [Inkscape](https://inkscape.org/) | Vector selection, handles, layers, path editing | SVG diagram editor with shapes, alignment, inspector | Open source |
| [darktable](https://www.darktable.org/) | Photo catalog and non-destructive develop pipeline | Photo catalog or smaller filter-stack editor | Open source |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | Professional editing pages, media bins, color workflow | Media-bin or timeline interaction prototype | Proprietary; free and paid Studio editions; platform support varies |
| [Kdenlive](https://kdenlive.org/) | Multitrack editing, effects, project bins | Timeline mockup or media-bin organizer | Open source |
| [Shotcut](https://shotcut.org/) | Timeline editing, filters, job feedback | Simple video assembly UI with trim and reorder | Open source |
| [Ableton Live](https://www.ableton.com/live/) | Session/arrangement views and performance controls | MIDI clip launcher or timeline interaction prototype | Commercial; strong design reference |
| [Ardour](https://ardour.org/) | Track routing, mixer strips, transport controls | Audio session dashboard or waveform annotator | Open source; commercial support options |
| [MuseScore Studio](https://musescore.org/) | Score layout, part navigation, playback | Music library or score annotation interface | Open-source application; verify current licensing and service terms |
| [HandBrake](https://handbrake.fr/) | Presets, job queue, progress reporting | Conversion queue UI backed by installed encoder | Open source |
| [Subtitle Edit](https://www.nikse.dk/subtitleedit) | Timestamp editing and waveform alignment | Subtitle editor with synchronized timeline and validation | Open source; platform/runtime requirements vary |

### Developer, data, and operations tools

| App | What makes it worth studying | JavaFX adaptation | Availability / notes |
|---|---|---|---|
| [IntelliJ IDEA](https://www.jetbrains.com/idea/) | Refactoring, inspections, navigation, tool windows | Java project explorer or focused IDE feature | Proprietary; free and paid editions, terms differ |
| [Visual Studio Code](https://code.visualstudio.com/) | Editor layout, command palette, extension model | Lightweight editor shell using an existing editor component | Source available under a separate license; product distribution terms differ |
| [Visual Studio](https://visualstudio.microsoft.com/) | Solution explorer, debugging, workload-based setup | Project/task dashboard or debugger interaction prototype | Proprietary; editions and eligibility vary |
| [Git Extensions](https://gitextensions.github.io/) | Commit browsing, staging, history, conflict workflows | Git status/stage/commit/log client | Open source |
| [Fork](https://git-fork.com/) | Fast diff review and branch navigation | Diff viewer with staged/unstaged sections and hunk actions | Commercial; trial/terms may vary |
| [DBeaver](https://dbeaver.io/) | Connection navigator, schema tree, data grids | JDBC database explorer with query tabs and result export | Community edition is open source; commercial editions available |
| [DataGrip](https://www.jetbrains.com/datagrip/) | SQL assistance, schema navigation, result editing | SQL workbench with saved connections and query history | Commercial subscription; check current licensing |
| [Postman](https://www.postman.com/) | Request composition, environments, response inspection | HTTP client with collections and formatted response tabs | Proprietary; plans and account requirements vary |
| [Bruno](https://www.usebruno.com/) | File-based API collections and request editing | HTTP client storing collections as plain files | Open source core; verify license and paid features |
| [Wireshark](https://www.wireshark.org/) | Display filters and packet list/detail/bytes panes | Structured log explorer with filters and expandable details | Open source; packet capture can require privileges |
| [Podman Desktop](https://podman-desktop.io/) | Container lifecycle and extension surfaces | Runtime dashboard for status, logs, start/stop | Open source; runtime/platform requirements apply |
| [Docker Desktop](https://www.docker.com/products/docker-desktop/) | Container overview and resource controls | Container dashboard backed by supported APIs | Proprietary; licensing terms depend on use |
| [Jenkins](https://www.jenkins.io/) | Pipeline stages, build history, streamed logs | CI monitor with job list and stage view | Open source |
| [Grafana](https://grafana.com/oss/grafana/) | Dashboard composition, time ranges, alert states | Local metrics dashboard with reusable chart cards | Open-source core plus commercial offerings |
| [VisualVM](https://visualvm.github.io/) | JVM discovery and diagnostic tabs | JMX monitor for heap/thread metrics | Open source; do not imply full profiler parity |
| [WinSCP](https://winscp.net/) | Remote/local panes and transfer queues | SFTP manager using established SSH library | Freeware; Windows |
| [Beyond Compare](https://www.scootersoftware.com/) | File/folder comparison and merge workflow | Side-by-side diff and conflict-resolution UI | Commercial; trial and license terms vary |

### Communication and collaboration

| App | What makes it worth studying | JavaFX adaptation | Availability / notes |
|---|---|---|---|
| [Thunderbird](https://www.thunderbird.net/) | Unified inbox, folder trees, message triage | Mail viewer/client slice with search and message details | Open source |
| [Element](https://element.io/) | Room navigation, unread state, message composition | Matrix room list and history using a supported SDK | Open source client; service and hosting options vary |
| [Mattermost](https://mattermost.com/) | Channels, search, notification hierarchy | Team-chat client prototype against documented APIs | Open-source and commercial offerings; verify edition terms |
| [Nextcloud Desktop](https://nextcloud.com/install/#install-clients) | Sync state, conflict handling, selective sync | Sync-status manager with visible, recoverable conflicts | Open source client; server/service options vary |
| [Remmina](https://remmina.org/) | Saved connections and remote-session organization | Connection manager for SSH/RDP/VNC via existing clients | Open source; protocol support varies |
| [Slack](https://slack.com/) | Channel navigation, threads, search, notification controls | Team-chat UX prototype, not a Slack clone/service | Proprietary; plan and API terms apply |
| [Zoom Workplace](https://www.zoom.com/) | Pre-call setup, meeting controls, device selection | Meeting launcher/status dashboard; media transport is out of scope | Proprietary; free and paid plans vary |

### More categories to explore

These areas broaden the catalog beyond the usual notes/editor/file-manager examples. Add representative apps from different operating systems and business models, and focus on distinctive desktop workflows.

| Category | Workflow/design patterns to study | JavaFX project seed |
|---|---|---|
| **Finance and personal accounting** | Reconciliation, transaction categorization, budgets, audit trails | CSV/OFX transaction importer with rules, review queue, and budget views |
| **Maps, GIS, and navigation** | Layer controls, legends, coordinate search, measurement | Offline-friendly map annotation tool with layer toggles and imported GeoJSON |
| **Email, feeds, and personal information management** | Inbox triage, message threading, feed subscriptions, calendar/task integration | Unified local dashboard for mail/feed metadata with saved searches and triage queue |
| **E-commerce and product catalog management** | Faceted product search, comparison, image galleries, stock/pricing state | Product catalog browser with filters, comparison tray, and CSV import |
| **Photography and asset management** | EXIF metadata, culling, ratings, contact sheets, color labels | Photo culling desk with fast thumbnail grid, ratings, and metadata inspector |
| **Typography and font management** | Font preview, family grouping, specimen pages, activation state | Font library browser with searchable families and custom specimen canvas |
| **Screen recording and live streaming** | Scene/source hierarchy, audio meters, recording state, transitions | Recording-session control panel or scene layout editor; media capture is a separate integration |
| **Digital forensics and data recovery** | Case structure, evidence chain, scan progress, recoverable-file review | Read-only media image browser with hashes and audit log; avoid modifying evidence |
| **Password, identity, and authentication management** | Vault organization, autofill trust, passkeys, recovery UX | Credential vault UI prototype; use reviewed standards/libraries and threat modeling |
| **Language learning and translation** | Parallel text, lookup, spaced repetition, offline dictionaries | Vocabulary review app with spaced repetition and imported dictionaries |
| **Travel planning and itinerary management** | Day-by-day timeline, map context, reservations, offline documents | Itinerary planner with timeline, attachments, and printable/exportable trip pack |
| **Recipe and meal planning** | Ingredient scaling, timers, shopping lists, dietary filters | Recipe organizer that scales quantities and compiles a shopping list |
| **Smartphone device management** | Device discovery, backup state, file browsing, update workflows | Local device inventory and photo/file import queue using supported protocols |
| **Accessibility testing and UI inspection** | Tree inspection, contrast checks, keyboard traversal, audit reports | JavaFX accessibility inspector or contrast/keyboard audit companion tool |
| **3D, CAD, and technical design** | Viewport navigation, object trees, property inspectors, constraints | 2D technical drawing or 3D model inspector before attempting a full CAD system |
| **Home automation and IoT** | Device grouping, live state, automations, connection health | Dashboard for a documented Home Assistant API, with clear stale/offline states |
| **Virtualization and remote machines** | VM lifecycle, snapshots, resource graphs, console access | Local VM inventory and status dashboard using an existing runtime API |
| **Backup, sync, and archival** | Job definitions, retention policies, verification, restore flows | Backup planner with dry-run preview, job history, and restore browser |
| **Disk, storage, and partition management** | Device hierarchy, capacity visualization, destructive-action safeguards | Read-only storage explorer with usage treemap and explicit risk labeling |
| **Security and forensics** | Evidence handling, findings, provenance, safe defaults | Local hash/checksum and file-inspection workbench; avoid building offensive tooling |
| **Accessibility and assistive technology** | Magnification, speech, contrast, input alternatives | Accessible reading/annotation tool with keyboard-first controls and configurable display |
| **Education and scientific visualization** | Lessons, notebooks, plots, parameter exploration | Interactive lab notebook or simulation dashboard with exportable results |
| **Reference and technical documentation** | Offline search, navigation trees, cross-reference browsing | Offline documentation library with indexed search and code snippets |
| **Personal knowledge dashboards** | Feeds, widgets, saved views, information density | Customizable start page combining local tasks, calendar, and project status |
| **Calendar, scheduling, and time tracking** | Multiple calendars, drag/drop, recurrence, time zones | Appointment planner or time tracker with timeline and reports |
| **Print, scan, and document workflows** | Device setup, page preview, batch jobs, status/errors | Scan intake and document organizer with metadata and export queue |
| **Package and software management** | Search, version comparison, install state, trust/source info | Read-only package inventory and update checker before adding install actions |
| **Music libraries and DJ workflows** | Crate organization, waveform, cue points, playlist transitions | Music collection manager with metadata cleanup and cue-point editor |
| **Podcast and audiobook tools** | Episode queues, chapter navigation, playback position | Local audiobook/podcast library with transcript and chapter navigation |
| **Workflow automation and node editors** | Triggers, conditions, graph execution, run logs | Visual workflow designer for a small safe set of local actions |
| **Diagramming and whiteboards** | Infinite canvas, connectors, alignment, export | Architecture diagram editor with snapping, grouping, and SVG export |
| **Point-of-sale and inventory** | Fast keyboard/touch entry, stock state, receipts | Offline inventory console with barcode-input support and transaction history |
| **Scientific and engineering instruments** | Live charts, device connection, calibration, data capture | Instrument dashboard using a documented serial/USB protocol or simulated data |
| **Game launchers and mod managers** | Library cards, compatibility, profiles, install progress | Local game-library organizer or mod-profile manager, keeping game-specific APIs out of scope |
| **Window/workspace management** | Workspace switching, layouts, per-app rules | In-app workspace/layout manager; OS-wide window control requires native APIs |

#### Linked examples by category

| Category | Real desktop apps and project pages |
|---|---|
| Finance and accounting | [GnuCash](https://www.gnucash.org/) · [KMyMoney](https://kmymoney.org/) · [Moneydance](https://moneydance.com/) (commercial) |
| Maps and GIS | [QGIS](https://qgis.org/) · [GRASS GIS](https://grass.osgeo.org/) · [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview) (commercial) |
| CAD and 3D design | [FreeCAD](https://www.freecad.org/) · [Blender](https://www.blender.org/) · [SketchUp](https://www.sketchup.com/) (free and paid plans) · [Autodesk Fusion](https://www.autodesk.com/products/fusion-360/overview) (commercial) |
| Home automation and IoT | [Home Assistant](https://www.home-assistant.io/) · [openHAB](https://www.openhab.org/) · [OpenRGB](https://openrgb.org/) |
| Virtualization and remote machines | [VirtualBox](https://www.virtualbox.org/) · [GNOME Boxes](https://apps.gnome.org/Boxes/) · [Proxmox VE](https://www.proxmox.com/en/proxmox-virtual-environment/overview) (web-managed platform) |
| Backup and archival | [Restic](https://restic.net/) · [Vorta](https://vorta.borgbase.com/) · [Kopia](https://kopia.io/) |
| Disk and storage | [KDE Partition Manager](https://apps.kde.org/partitionmanager/) · [GNOME Disks](https://apps.gnome.org/DiskUtility/) · [GParted](https://gparted.org/) |
| Security and forensics | [KeePassXC](https://keepassxc.org/) · [Autopsy](https://www.autopsy.com/) · [EnCase](https://www.opentext.com/products/encase-forensic) (commercial) |
| Accessibility | [NVDA](https://www.nvaccess.org/) · [AccessNote](https://www.accessnote.org/) · [JAWS](https://www.freedomscientific.com/products/software/jaws/) (commercial) |
| Education and science | [GeoGebra](https://www.geogebra.org/) · [Stellarium](https://stellarium.org/) · [GNU Octave](https://octave.org/) · [MATLAB](https://www.mathworks.com/products/matlab.html) (commercial) |
| Documentation and reference | [Zeal](https://zealdocs.org/) · [DevToys](https://devtoys.app/) · [Dash](https://kapeli.com/dash) (commercial, macOS) |
| Calendar and time tracking | [Thunderbird Calendar](https://www.thunderbird.net/) · [Etar](https://github.com/Etar-Group/Etar-Calendar) · [Timeular](https://timeular.com/) (commercial) |
| Printing and scanning | [NAPS2](https://www.naps2.com/) · [Skanpage](https://apps.kde.org/skanpage/) · [VueScan](https://www.hamrick.com/) (commercial) |
| Package management | [Synaptic](https://www.nongnu.org/synaptic/) · [Discover](https://apps.kde.org/discover/) · [Chocolatey GUI](https://github.com/chocolatey/ChocolateyGUI) |
| Music and DJ workflows | [Mixxx](https://mixxx.org/) · [LMMS](https://lmms.io/) · [rekordbox](https://rekordbox.com/) (free and paid plans) · [Ableton Live](https://www.ableton.com/live/) (commercial) |
| Podcasts and audiobooks | [gPodder](https://gpodder.github.io/) · [AntennaPod](https://antennapod.org/) · [Audiobookshelf](https://www.audiobookshelf.org/) |
| Automation and node editors | [Node-RED](https://nodered.org/) · [n8n](https://n8n.io/) · [ComfyUI](https://github.com/comfyanonymous/ComfyUI) |
| Diagramming and whiteboards | [draw.io / diagrams.net](https://www.diagrams.net/) · [Excalidraw](https://excalidraw.com/) · [Miro](https://miro.com/) (commercial plans) · [Microsoft Visio](https://www.microsoft.com/microsoft-365/visio/flowchart-software) (commercial) |
| POS and inventory | [Odoo](https://www.odoo.com/) · [uniCenta](https://unicenta.com/) · [Square Point of Sale](https://squareup.com/us/en/point-of-sale) (commercial/service-dependent) |
| Scientific instruments | [LabPlot](https://labplot.kde.org/) · [KiCad](https://www.kicad.org/) · [LabVIEW](https://www.ni.com/en/shop/labview.html) (commercial) |
| Games and mod management | [Lutris](https://lutris.net/) · [Heroic Games Launcher](https://heroicgameslauncher.com/) · [Mod Organizer 2](https://github.com/ModOrganizer2/modorganizer) |
| Window/workspace management | [Microsoft PowerToys](https://learn.microsoft.com/windows/powertoys/) · [KDE KWin](https://invent.kde.org/plasma/kwin) · [Rectangle](https://rectangleapp.com/) (macOS; free and paid editions) |
| Email and feeds | [Mozilla Thunderbird](https://www.thunderbird.net/) · [RSS Guard](https://github.com/martinrotter/rssguard) · [Mailspring](https://www.getmailspring.com/) |
| E-commerce/catalogs | [Odoo](https://www.odoo.com/) · [Shopify POS](https://www.shopify.com/pos) (commercial) · [Snipe-IT](https://snipeitapp.com/) (asset inventory) |
| Photography and assets | [digiKam](https://www.digikam.org/) · [Eagle](https://eagle.cool/) (commercial) · [Adobe Lightroom Classic](https://www.adobe.com/products/photoshop-lightroom-classic.html) (commercial) |
| Fonts and typography | [FontBase](https://fontba.se/) · [NexusFont](https://www.xiles.app/) · [MainType](https://www.high-logic.com/font-manager/maintype) (commercial) |
| Screen recording/streaming | [OBS Studio](https://obsproject.com/) · [Camtasia](https://www.techsmith.com/camtasia/) (commercial) · [ScreenFlow](https://www.telestream.net/screenflow/) (commercial, macOS) |
| Device management | [KDE Connect](https://kdeconnect.kde.org/) · [LocalSend](https://localsend.org/) · [scrcpy](https://github.com/Genymobile/scrcpy) |
| Language learning | [Anki](https://apps.ankiweb.net/) · [GoldenDict-ng](https://github.com/xiaoyifang/goldendict-ng) · [LingQ](https://www.lingq.com/) (service/app) |
| Travel planning | [GPXSee](https://www.gpxsee.org/) · [Organic Maps](https://organicmaps.app/) · [TripIt](https://www.tripit.com/) (service/app) |
| Recipes and meal planning | [Mealie](https://mealie.io/) · [Paprika](https://www.paprikaapp.com/) (commercial) · [Tandoor Recipes](https://tandoor.dev/) |
| Backup and recovery utilities | [Rescuezilla](https://rescuezilla.com/) · [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec) · [R-Studio](https://www.r-studio.com/) (commercial) |

Links are starting points, not a verified license or maintenance audit. Some products are web-first, web-managed, platform-specific, or require separate services; check the official project information before choosing an inspiration target.

## JavaFX implementation toolbox

These are **building blocks**, not endorsements or a promise that every library is actively maintained. Check the current release, Java/JDK compatibility, platform support, and license before adoption. Prefer a small number of well-understood dependencies over a large stack.

### UI, layout, and visual controls

| Library | Useful for | Notes |
|---|---|---|
| [AtlantaFX](https://github.com/mkpaz/atlantafx) | Modern CSS themes and controls for JavaFX | Theme layer; confirm supported JavaFX versions and license |
| [Ikonli](https://github.com/kordamp/ikonli) | Icon packs and icon fonts | Check each icon pack's own license, not only the library license |
| [ControlsFX](https://github.com/controlsfx/controlsfx) | Extra controls such as notifications, dialogs, and builders | Check module and JavaFX compatibility |
| [FormsFX](https://github.com/dlsc-software-consulting-gmbh/FormsFX) | Form construction and validation | Useful for settings and metadata editors |
| [TilesFX](https://github.com/HanSolo/tilesfx) | Dashboard tiles and gauges | Consider performance and accessibility for dense dashboards |
| [RichTextFX](https://github.com/FXMisc/RichTextFX) | Styled text areas and editor foundations | Not a complete IDE/editor; pair with parser/language tooling as needed |
| [Flowless](https://github.com/FXMisc/Flowless) | Virtualized scrolling layouts | Useful for large logs, lists, and timelines |
| [FXGL](https://github.com/AlmasB/FXGL) | Game loops, input, and 2D game UI | For game-like tools/canvases; assess whether standard JavaFX is simpler |

### Data, persistence, and formats

| Library | Useful for | Notes |
|---|---|---|
| [Jackson](https://github.com/FasterXML/jackson) or [Gson](https://github.com/google/gson) | JSON serialization | Choose one; define schema/versioning and safe file handling |
| [SQLite JDBC](https://github.com/xerial/sqlite-jdbc) | Embedded local database | Plan migrations, backups, and native packaging considerations |
| [H2](https://www.h2database.com/) | Embedded or server database | Check mode and license for your use case |
| [Apache Commons CSV](https://commons.apache.org/proper/commons-csv/) | CSV parsing/writing | Handle encodings, quoting, and large-file streaming |
| [Apache POI](https://poi.apache.org/) | Microsoft Office document formats | Large dependency surface; confirm supported formats and memory behavior |
| [PDFBox](https://pdfbox.apache.org/) | PDF reading and creation | For advanced rendering/OCR, additional tools may be required |
| [Flexmark](https://github.com/vsch/flexmark-java) | Markdown parsing/rendering | Check extensions and output-sanitization requirements |
| [jsoup](https://jsoup.org/) | HTML parsing and sanitization | Not a browser engine; sanitize untrusted content appropriately |
| [JGit](https://www.eclipse.org/jgit/) | Git operations from Java | Git CLI can offer better compatibility with unusual Git setups; evaluate both |

### Networking, platform integration, and diagnostics

| Library / API | Useful for | Notes |
|---|---|---|
| [Java HttpClient](https://docs.oracle.com/en/java/javase/21/docs/api/java.net.http/java/net/http/HttpClient.html) | HTTP APIs and asynchronous requests | Included in modern JDKs; manage cancellation, timeouts, and secrets |
| [OkHttp](https://square.github.io/okhttp/) | HTTP client features and connection management | Check current license and Java compatibility |
| [SSHJ](https://github.com/hierynomus/sshj) or [Apache MINA SSHD](https://mina.apache.org/sshd-project/) | SSH/SFTP features | Verify host keys; never silently trust unknown hosts |
| [JNA](https://github.com/java-native-access/jna) | Calling native OS APIs | Platform-specific, adds deployment/testing burden |
| [JNA Platform](https://github.com/java-native-access/jna) | Common OS structures and native APIs | Keep native integration behind interfaces and provide fallback behavior |
| [JNA / OS APIs](https://github.com/java-native-access/jna) | Global shortcuts, notifications, file associations | These are OS-specific; JavaFX itself does not provide all shell integrations |
| [SLF4J](https://www.slf4j.org/) with a backend | Application logging | Avoid logging credentials, tokens, or sensitive document contents |
| [Micrometer](https://micrometer.io/) | Application metrics | Useful for monitoring tools; keep instrumentation optional |

### Packaging and quality

- Use **Maven** or **Gradle** with pinned versions and dependency verification where practical.
- Use **jlink/jpackage** to build runtime images and installers; test on each target OS rather than assuming portability.
- Consider **TestFX** for JavaFX UI tests, while keeping most logic testable without launching a UI.
- Keep blocking disk/network/database operations off the JavaFX Application Thread; report progress and support cancellation.
- Audit transitive dependencies, licenses, native libraries, update mechanisms, and platform permissions before shipping.

## Project ideas by difficulty

**Beginner:** Markdown/JSON notes organizer; image batch renamer with preview; CSV viewer; subtitle validator; color palette manager.

**Intermediate:** Git status/diff client; JDBC schema browser; SFTP transfer queue; audio waveform annotator; local media catalog; searchable log explorer.

**Advanced:** Multitrack timeline editor; node-based workflow canvas; plugin host; multi-device sync client; IDE-like editor using language-server protocol; container dashboard with live event streams.

## Research and contribution notes

This is a discovery catalog, not a live audit of maintenance, pricing, licenses, or OS support. Product pages are starting points; inspect the project's repository, documentation, current terms, and third-party component licenses before committing to a port.

To add an entry, include an official link, the distinctive desktop interaction, a bounded JavaFX adaptation, and availability/license notes where known. Flag platform-specific or security-sensitive requirements. Favor useful workflow details over name-only lists.
