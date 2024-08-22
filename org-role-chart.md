# Akatsuki Organizational Chart

```mermaid
stateDiagram-v2
    state "Director" as director
    state "cmyui" as director
    state "Niotid" as director
    state "tsunyoku" as director
    state "Flame" as director
    director --> coreDevelopment
    director --> coreDesign
    director --> eventManager
    director --> cheatAnalysis
    director --> accountManagement
    director --> nominationQualityAssurance
    director --> scorewatch
    director --> socialMediaManager

    state "Core Developer" as coreDevelopment
    state "cmyui" as coreDevelopment
    state "tsunyoku" as coreDevelopment
    state "Flame" as coreDevelopment
    state "lenforiee" as coreDevelopment

    state "Core Designer" as coreDesign
    state "Strawberry" as coreDesign

    state "Event Manager" as eventManager
    # TODO: we need event managers

    state "Cheat Analysis" as cheatAnalysis
    state "Good Morning" as cheatAnalysis
    state "Flame" as cheatAnalysis
    state "kippy" as cheatAnalysis
    state "Riffee" as cheatAnalysis
    state "Niotid" as cheatAnalysis

    state "Account Management" as accountManagement
    state "kippy" as accountManagement
    state "Good Morning" as accountManagement
    state "henry" as accountManagement
    state "cmyui" as accountManagement
    state "lawtron" as accountManagement
    state "Niotid" as accountManagement
    state "Riffee" as accountManagement
    state "tsunyoku" as accountManagement
    accountManagement --> communitySupport

    state "Community Support" as communitySupport
    state "awsumturtle" as communitySupport
    state "CursorDance" as communitySupport
    state "henry" as communitySupport
    state "kaden" as communitySupport
    state "kieran" as communitySupport
    state "lawtron" as communitySupport
    state "nagatoro" as communitySupport
    state "PlayWithMeow" as communitySupport
    state "Yoruba" as communitySupport

    state "Nomination Quality Assurance" as nominationQualityAssurance
    state "Aetrian" as nominationQualityAssurance
    state "Agent5d" as nominationQualityAssurance
    state "lawtron" as nominationQualityAssurance
    state "kaden" as nominationQualityAssurance
    nominationQualityAssurance --> beatmapNominator
    nominationQualityAssurance --> probationaryBeatmapNominator

    state "Beatmap Nominator" as beatmapNominator
    state "basilvt" as beatmapNominator
    state "lawtron" as beatmapNominator
    state "DarkWolfyChan" as beatmapNominator
    state "hotgayfurryfeet" as beatmapNominator
    state "kevaca" as beatmapNominator
    state "kaden" as beatmapNominator
    state "nagatoro" as beatmapNominator
    state "Niotid" as beatmapNominator
    state "quantumvortex" as beatmapNominator
    state "Scottie" as beatmapNominator
    state "TritoBandito" as beatmapNominator
    state "murmurtwins" as beatmapNominator

    state "Probationary Beatmap Nominator" as probationaryBeatmapNominator

    state "Scorewatch" as scorewatch
    state "abssttract" as scorewatch
    state "fyta" as scorewatch
    state "Niotid" as scorewatch
    state "kippy" as scorewatch

    state "Social Media Manager" as socialMediaManager
    state "kippy" as socialMediaManager
```
