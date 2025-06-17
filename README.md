This is a master list of all the available open source RuneScape projects. Closed source projects will not be listed here.

# Terminology
* Status:
  * Active - Updated within last 6 months.
  * Inactive - Updated within last 2 years.
  * Abandoned - No updates within 2 years (or otherwise stated).
  * GitLab - Project is hosted on GitLab and mirrored onto GitHub for free advertising.
* (year)Scape - RuneScape ripped from that year.
* OldScape - Old School RuneScape. This is after Jagex added updates to 2007scape.
* NuScape - EoE/LGBTQ+ version of RuneScape.


# 2001Scape
OrginialScape includes many typos and an unrefined playstyle for the truly hardcore. If you failed to log out, your progress was not saved. Thankfully, dial-up is a thing of the past.
## Servers
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [Open-RSC/Core-Framework](https://github.com/Open-RSC/Core-Framework) | #177    | Depends      | Java         | $$\textcolor{green}{\text{Active}}$$       | The original RuneScape Classic was closed down and abandoned after 17 years on August 6th, 2018. Through open source black box reverse engineering, the Open RuneScape Classic project team have brought forth Open RuneScape Classic (Open RSC) so that it may be enjoyed by fans once again. |

## Clients
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [Open-RSC/mudclient38-deob-teavm](Open-RSC/mudclient38-deob-teavm) | #038       | Yes          | Java         | $$\textcolor{yellow}{\text{Inactive}}$$    | A minimally edited deob of mudclient38 with changes made to support TeaVM for web browser use. |
| [Open-RSC/mudclient177-deob-teavm](https://github.com/Open-RSC/mudclient177-deob-teavm) | #177 | Yes | Java   | $$\textcolor{green}{\text{Active}}$$       | A minimally edited deob of mudclient177 with changes made to support TeaVM for web browser use. |

# 2003Scape
RuneScape in the year 2003 was considered the final years of RuneScape Classic before it becomes "RuneScape 2". This refines the rough edges of 2001scape. 
## Servers
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [2003scape/rsc-server](https://github.com/2003scape/rsc-server)  | #204         | Yes          | JavaScript   | $$\textcolor{yellow}{\text{Inactive}}$$     | RuneScape classic private server mmorpg emulator. designed to work with the web-based rsc-client or the java-based mudclient204. |
| [spkaeros/RSCGo](https://github.com/spkaeros/RSCGo)              | #204         | No           | Go           | $$\textcolor{yellow}{\text{Inactive}}$$     | A TCP/IP server written in Go 1.12. This server is designed for a slightly modified RSClassic client based on revision 204 of the official version. |

## Clients
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [2003scape/rsc-c](https://github.com/2003scape/rsc-c)            | #177/#204    | Yes          | C            | $$\textcolor{green}{\text{Active}}$$       | RuneScape Classic client ported to C. |
| [2003scape/mudclient204](https://github.com/2003scape/mudclient204)| #204       | Yes          | Java         | $$\textcolor{green}{\text{Active}}$$       | A mostly-refactored 204 revision of Jagex's abandonware RuneScape classic client. |

# 2004Scape
RuneScape 2, the major graphical update to the original RuneScape, was officially released on March 29, 2004. This launch marked the beginning of what is now known as RuneScape, with the original game being renamed RuneScape Classic.
## Servers
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [LostCityRS/Server](https://github.com/LostCityRS/Server)        | #225         | Yes          | Typescript   | $$\textcolor{green}{\text{Active}}$$    | The most faithful preservation project in this entire list. No custom features. |

## Clients
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [LostCityRS/Client-TS](https://github.com/LostCityRS/Client-TS)  | #225         | Yes          | Typescript   | $$\textcolor{green}{\text{Active}}$$    | Client for LostCityRS. Not really needed as LostCityRS can run in the browser. |

# 2006Scape
2006Scape is two years after "RuneScape 2". This considered the peak RuneScape experience. 2007scape is currently officially hosted by Jagex.
## Servers
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [luna-rs/luna](https://github.com/luna-rs/luna)                  | #317         | Yes          | Java         | $$\textcolor{red}{\text{Abandoned}}$$    | A highly scalable and efficient RuneScape server. Targets revision #317. No longer in development. |
| [dozmus/runesource](https://github.com/dozmus/runesource)        | #317         | Yes          | Java         | $$\textcolor{red}{\text{Abandoned}}$$    | RuneSource is an open-source server for the popular game RuneScape, written in the Java programming language. Please note that this server is not ready for production - it has minimal content implemented. |
| [2006-Scape/2006Scape](https://github.com/2006-Scape/2006Scape)  | #317         | Yes          | Java         | $$\textcolor{green}{\text{Active}}$$       | A 2006 RuneScape Emulation Server. |
| [runejs/server](https://github.com/runejs/server)                | #435         | No           | TypeScript   | $$\textcolor{green}{\text{Active}}$$       | RuneJS is a RuneScape game server written in TypeScript and JavaScript. The goal of the project is to create a comprehensive game engine, while also providing simple and easy to use content development systems and APIs. |


## Clients
* [dozmus/rs317-client](https://github.com/dozmus/rs317-client) - A partially refactored RuneScape client for revision #317.

## Tools
* [dozmus/rsps-stress-tester](https://github.com/dozmus/rsps-stress-tester) - A RSPS stress tester for the 317 protocol.

# 2009Scape
This is after the introduction of the Grand Exchange in 2007. The year after that saw the introduction of PvP Worlds, RuneScape High Detail, Summoning, the first Grandmaster quest, combat minigames, and Distractions and Diversions. 2009 was the year of upgrades, tweaks, improvements, and polishing.
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [2009scape](https://github.com/2009scape)                        | #550         | Yes          | C++          | $$\textcolor{Blue}{\text{GitLab}}$$       | Open source RuneScape 2009 Emulation. |

# OldScape
This version of RuneScape goes back to 2007scape, but then restarts the build numbering scheme from #1.
| Repo                                                             | Build        | Vanilla      | Language     | Status       | About        |
| ---------------------------------------------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ |
| [guthix/OldScape](https://github.com/guthix/OldScape)            | #189         | Yes          | Kotlin       | $$\textcolor{yellow}{\text{Inactive}}$$     | OldScape is an emulator project that simulates the Oldschool RuneScape server. |


# Archive
* [runetech/osrs-gamepacks](https://github.com/runetech/osrs-gamepacks) - Collection of unmodified OldSchool RuneScape gamepacks.
