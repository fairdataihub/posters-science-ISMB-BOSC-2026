[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

# Repository of the Posters.science presentation material for the ISMB/ECCB & BOSC 2026 conference (July 12-16, 2026)

## About

This repository contains the material and information associated with our talk and poster at the joint ISMB/ECCB and Bioinformatics Open Source Conference (BOSC) 2026. We are presenting **Posters.science**, a free and open-source platform for making scientific posters FAIR and AI-ready.

**Abstract**:

Every year, millions of scientific posters are presented at conferences. They are particularly relevant to biomedical research, where conference posters often represent the earliest public glimpse of ideas and findings that will eventually shape clinical guidelines and drug targets. Yet, most posters disappear by the end of conferences, rolled up under chairs or stuffed into recycling bins. Through our investigation of poster-sharing practices, we found only ~150,000 posters online across 86 platforms, and even those lacked basic metadata, like author identifiers, funding sources, and conference information, making them hard to find and reuse. To address this, we are developing Posters.science, a free and open-source platform that simplifies poster sharing. Users only need to upload a PDF of their poster, review auto-extracted metadata, and publish to a repository of their choice, like Zenodo. We developed a custom LLM pipeline that handles the metadata extraction and generates a poster.json file, which is a structured, machine-readable version of the poster that makes it interoperable and AI-ready. The platform also works as a registry, currently indexing over 1,500 posters from Zenodo and Figshare, with more on the way. For the biomedical community specifically, this could open new possibilities for systematically mining early-stage findings on a disease or gene across thousands of posters. In this talk, we will present our analysis of current poster-sharing practices, introduce the poster.json schema design, and give a live demonstration of Posters.science.

## Schedule

| Type       | Date & Time | Authors                    | Session / Location                  | Details |
| ---------- | ----------- | --------------------------- | ------------------------------------ | ------- |
| Short talk | July 15, 2026, 2:40-2:45 pm | Bhavesh Patel (presenter) et al. | Session 5a: FAIR Data & Governance  | [BOSC 2026 schedule](https://www.open-bio.org/events/bosc-2026/) / [ISMB 2026 website](https://www.iscb.org/ismb2026/home) |
| Poster     | July 16, 2026, at 10:00-11:00 am and 4:00-4:40 pm | Bhavesh Patel (presenter) et al. | Poster Session D, Columbia Ballroom | [BOSC 2026 schedule](https://www.open-bio.org/events/bosc-2026/) / [ISMB 2026 website](https://www.iscb.org/ismb2026/home) |

## Meeting material

- `ISMB2026838PatelTalk.pdf`: slides of our talk. *(to be added closer to the event)*
- `ISMB20262153PatelPoster.pdf`: conference poster. *(to be added closer to the event)*
- `BOSC-2026-long-abstract-Posters-science.pdf`: Long abstract submitted for BOSC 2026.

## Resources

We list here major resources relevant to our talk.

| Description                                       | Link                                                          |
| -------------------------------------------------- | -------------------------------------------------------------- |
| Posters.science platform                           | https://posters.science |
| Posters.science GitHub repo                           | https://github.com/fairdataihub/posters-science |
| Posters.science project page                       | https://fairdataihub.org/posters-science |
| poster JSON schema repository                      | https://github.com/fairdataihub/poster-json-schema |
| poster2json (LLM metadata extraction pipeline)      | https://github.com/fairdataihub/poster2json |
| PosterSentry (poster QA classifier, related talk)   | https://huggingface.co/fairdataihub/poster-sentry |
| ISMB/BOSC 2026 event page (FAIR Data Innovations Hub) | https://fairdataihub.org/events/ISMB-2026 |

## CoFest

Following BOSC, our team will also participate in the **[BOSC CoFest](https://www.open-bio.org/events/bosc-2026/collaborationfest/)** (July 17-18, 2026), proposing a collaborative sprint around Posters.science, including biomedical schema extensions to poster.json, benchmarking the poster2json extraction pipeline, and prototyping semantic search over the Posters.science registry. All participants are welcome.

## License

The material in this repository is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

## Contact us

For submitting feedback or getting in touch either:
- Use the GitHub issues on this repository
- Email us: bpatel@calmi2.org
