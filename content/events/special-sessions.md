---
menu:
  main:
    parent: "events"
title: "Special Sessions"
weight: 4
---

# Introduction
In early 2020, when the pandemic just was kicking off, DASH-IF replaced its f2f meetings with a series of Special Sessions. This was setup in order to provide a platform for DASH-IF members and external companies to present new ideas. DASH-IF typically invites colleagues from other organizations such as MPEG, 3GPP, DVB, SCTE, CTA WAVE or ATSC. This makes these presentations lively and interesting and we have identified relevant new topics for which some of them have been moved into work streams. If you are interested to give a presentation as well, please contact us.

- [Special Sessions 2022](#special-sessions-2022)
- [Special Sessions 2021](#special-sessions-2021)
- [Special Sessions 2020](#special-sessions-2020)

# Special Sessions 2022

## October 21, 2022: Ad slot signalling in DASH according to DVB and SCTE
- Presenter: Presenters: [Rufael Mekuria](https://www.linkedin.com/in/rufael-mekuria-652b4828/) (Unified Streaming), [Yasser Syed](https://www.linkedin.com/in/yasser-syed-734198/) (Comcast)
- Abstract: Signalling of ad slots in DASH is a feature that is increasingly popular. SCTE-35 was popular n MPEG-2 TS based workflows and is increasingly used in DASH and HLS streaming to enable ad insertion and substitution. Signalling ad breaks consistently between MPEG-2 TS and streaming workflows, and for server and client side ad insertion are key to harmonize workflows and increase interoperability. To this extent, DVB developed DVB-TA suite, including a recommendation for signalling ad slots in MPEG-2 TS and  DVB-DASH, while SCTE has updated specifications of SCTE 214 and SCTE 35 to better account for usage in streaming environments. We detail some of the problems addressed in using SCTE-35 ad slot signalling in DASH in a consistent and optimized manner for different use cases, and detail some of the timing relationships between the SCTE-35 payload and the DASH signalling and the use of single vs multi period.  Last we also present some example streams available, and some of the open topics remaining in this space. 
- Slides
- Recording

## April 13, 2022: Watermarking
- Presenter: Presenters: [Gwenaël Doërr](https://www.linkedin.com/in/gdoerr/) (Synamedia), [Nicolas Weil](https://www.linkedin.com/in/nicolasweil/) (AWS), [Marcelo San Martin](https://www.linkedin.com/in/msanmartin/) (Akamai)
- [Slides](https://github.com/Dash-Industry-Forum/Dash-Industry-Forum.github.io/files/8912655/DASH-IF.Server.Side.Watermarking.pdf)
- Recording

## June 5, 2022: Next Steps in ATSC and DASH

### Overview and Background:
- Presenter: [Thomas Stockhammer](https://www.linkedin.com/in/stockhammer/) (DASH-IF IOP Chair)
- Recording

### Presentation 1: Introduction to ROUTE RFC 9223
- Presenter: [Waqar Zia](https://www.linkedin.com/in/waqarzia/)
- [Slides](https://github.com/Dash-Industry-Forum/Dash-Industry-Forum.github.io/files/8912514/ROUTE.Overview.pdf)

### Presentation 2: ATSC ROUTE/DASH Introduction
- Presenter: [Michael Dolan](https://www.linkedin.com/in/michael-dolan-50872355/) (ATSC TG3-6 Chair)
- [Slides](https://github.com/Dash-Industry-Forum/Dash-Industry-Forum.github.io/files/8912507/ATSC-ROUTE-DASH-20220603.pdf)

### Presentation 3: ROUTE/DASH/CMAF - Design options and opportunities
- Presenter: [Thomas Stockhammer](https://www.linkedin.com/in/stockhammer/) (DASH-IF IOP Chair)
- [Slides](https://github.com/Dash-Industry-Forum/Dash-Industry-Forum.github.io/files/8912495/DASH-IF-ROUTE-Session-Thomas.pdf)

### Presentation 4: LL-DASH over ROUTE: Implementation in GPAC
- Presenter: [Romain Bouqueau](https://www.linkedin.com/in/rbouqueau/) (GPAC)
- [Slides](https://github.com/Dash-Industry-Forum/Dash-Industry-Forum.github.io/files/8912491/DASH-IF.2022.LL-DASH.over.ROUTE.in.GPAC.pdf)

# Special Sessions 2021

## January 20, 2021
### Presentation: Modern content replacement workflows based on SCTE Specifications
- Slides
- Abstract: The presentation will introduce on new standards and workflows for SCTE 35, 224 and more.  We will discuss how SCTE has upgraded workflows to address modern content replacement in new media.  We will provide insight on how SCTE is addressing targeted content replacement within an OTT and or broadband distribution network.  The presentation should also help to explore how this new approach might be used in different application-based environments to create a “broadcast” quality experience for ad insertion and content replacement.
- Speaker Bio: Gary Hughes has been a long-time member of and contributor to the SCTE’s Digital Video Subcommittee.  He is particularly active in Working Group 5 which is focused on Digital Program Insertion.  He also participates in working groups focused on Advanced Coding Technologies and MPEG-DASH, among others.  An independent consultant, media technologist, and innovator, Gary is experienced in digital media delivery, broadband IPTV, video on demand, HDTV, compression and transcoding, editing and stream manipulation.  In addition to his work with SCTE, he has participated in various standards organizations and industry groups such as DASHIF, IAB, DLNA and MPEG. His previous work includes service with industry leaders such as DTS, Switch Media, SeaChange, Motorola, Broadbus, Avid and Sarnoff. Gary holds multiple patents related to video server design, adaptive bitrate streaming, trick mode operations, splicing/ad insertion, use of scalable coding in on demand a
Ad insertion group will discuss issues around interop/test vectors/reference clients

## April 9, 2021

### Presentation 1: Brief Overview on CTA-5004: Common Media Client Data (CMCD)
- Slides
- Presenter: Will Law (Akamai)
- Abstract: This presentation provides a brief overview on CTA-5004: Common Media Client Data (CMCD)

## Presentation 2: Use of CMCD in HTTP Adaptive Streaming: Initial Findings
- Slides
- Presenter: Ali C. Begen et al.
- Abstract:  In September 2020, the Consumer Technology Association (CTA) published the CTA-5004: Common Media Client Data (CMCD) specification. Using this specification, a media client can convey certain information to the content delivery network servers with object requests. This information is useful in log association/analysis, quality of service/experience monitoring and delivery enhancements. This paper is the first step toward investigating the feasibility of CMCD in addressing one of the most common problems in the streaming domain: efficient use of shared bandwidth by multiple clients. To that effect, we implemented CMCD functions on an HTTP server and built a proof-of-concept system with CMCD-aware dash.js clients.We show that even a basic bandwidth allocation scheme enabled by CMCD reduces rebuffering rate and duration without noticeably sacrifycing the video quality.

## Presentation 3 LC-EVC - Principles and Application to Adaptive Streaming and the Web (part 1 V-Nova) (part 2 Streaming Media)
- Presenter: Simone Ferrara (V-Nova), Fabio Murra (V-Nova), Guendalina Cobianchi (V-Nova), Jan Ozer (Streaming Media)
- Abstract: ISO/IEC 23094-2 – Low Complexity Enhancement Video Coding (LCEVC) is in the final development stages in ISO. LCEVC is fundamentally different to other compression standards by virtue of being a complement to all video codecs, existing and forthcoming. This presentation will provide an overview of the principles of LC-EVC as well as two aspects related to DASH-IF efforts
Usage for Adaptive Streaming: Independent evaluation of the effectiveness of applying LCEVC enhancement in adaptive streaming use cases from a forthcoming report conducted by Streaming Media’s analyst Jan Ozer show improved QoE, compatibility with DASH and HLS as well as reduced costs due to CDN optimization
Integration into HTML-5, for example into hls.js based on information here: https://docs.v-nova.com/v-nova/lcevc/integrations/html5-integration

## May 28, 2021: WebRTC-based Premium Streaming Ecosystem
- For details, please go [here](https://dashif.org/news/webrtc/)
- Abstract: WebRTC is the foundational technology for real-time streaming online and as such has widespread support across browsers. It is used widely across many applications.  However, the use of real-time streaming for professionally-produced content is highlighting gaps in WebRTC, creating the need for industry collaboration.  This talk will explore some of these key areas and sketch out possible ways forward for the industry.
- Presenters:
  - Bill Wishon is the Chief Product Officer for Phenix Real Time Solutions, leading the company's product strategy and roadmap for real-time video streaming at scale. Bill has 20+ years of experience in the media industry working on business and technology innovation to improve the quality, scale and reliability of online video delivery. Prior to Phenix, Bill held leading technical and product roles at Akamai, Kontiki, VeriSign, LightSurf, and Adobe Systems.
  - Ofer Shem Tov is a distinguished video architect in Verizon Media Platform, working on the latest video streaming technologies. Ofer was the development leader for VocalTec’s Internet Phone that started the VoIP revolution in 1995. Ofer later co-founded RayV that developed efficient P2P based video broadcasting and was acquired by Yahoo in 2014.

# Special Sessions 2020

## May 22, 2020: DASH over SRT
- Title: DASH over SRT, by Haivision (Recording pwd: DashIf2020)
- https://members.dashif.org/wg/DASH/document/4455

## June 5, 2020 

### Presentation 1: A advertising  Working Group: Ad monitoring End to End
- Presenter: Mourad Kioumgi, Sky

### Presentation 2: A new approach to DRM
- Title: A new approach to DRM
- Presenter: Sander Saares, Axinom

## June 19, 2020

### Presentation 1: Haptics Media in DASH 
- Presenter: Yeshwant Muthusamy, Chris Ullrich 

### Presentation 2: 5G Media Streaming Status Update
- Presenter: Thomas Stockhammer

## July 17, 2020: Video HRD conformance and DASH
- Presenter: Yuriy Reznik

## July 31, 2020

### Presentation 1: An overview of the High Efficiency Streaming Protocol
- Presenter: Pieter-Jan Speelmans
- Abstract: With HESP, a new streaming protocol standard is becoming available. It's focussed on delivering media with ultra low latency, ultra fast zapping with low bandwidth at scale. In this talk, we'll provide some insights in the why and how of HESP and the compatibility profile for other streaming protocols such as MPEG-DASH and HLS.

### Presentation 2: W3C DataCue API Introduction
- Presenter: Chris Needham (BBC, co-chair W3C Media & Entertainment Interest Group)
- Abstract: DataCue is a proposed W3C API to support media-timed events in HTML, which is being developed in collaboration with the DASH-IF Event TF. I'll give an introduction to the API, covering the use cases, history, and API design, and how it can be used to deliver DASH emsg and MPD events to web applications.

## August 14, 2020

### Presentation: MPEG Network-Based Media Processing and 5G Media Edge Processing
- Presenter: Iraj Sodagar
- Abstract: This talk provides a quick overview of MPEG’s NBMP standard, as well as 3GPP’s activities on 5G media processing on edge. It covers the NBMP standard and its current status, including its recent activities on media workflow splits and split-rendering. It also covers various ongoing 3GPP SA4 study items on network media processing and edge processing.

## September 11, 2020
### Presentation: A primer to VVC with focus on High-Level Syntax
- Presenter: [Ye-Kui Wang](https://www.linkedin.com/in/yekui/) (ByteDance), Co-Editor of VVC/H.266 Specification
- Abstract: Versatile Video Coding (VVC), a.k.a ITU-T H.266 | ISO/IEC 23090-3,  is the video coding standard that has just been finalized by the Joint Video Experts Team (JVET) of ITU-T VCEG and ISO/IEC MPEG at its 19th meeting ended on July 1st, 2020. This presentation will give a brief overview of the new video coding standard, focusing on its designs on various aspects of high-level syntax, the systems and transport interface of a video codec.
- for details please go to https://dashif.org/news/vvc-yk

## October 9, 2020
### Presentation: Ingest Task Force with special session
- Presentation: Ali Begen
  - Slides
  - LoL video presentation: https://www.youtube.com/watch?v=9xU582WomTg
  - John Bartos/Twitch evaluation video: https://www.youtube.com/watch?v=rcXFVDotpy4
  - LoL+ paper: Under review, email acbegen if interested
- Presentation Theo
  - (slides)
  - Player discussion

## November 20, 2020

### Presentation: ISO/IEC 23009-8
