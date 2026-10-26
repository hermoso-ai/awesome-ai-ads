# Awesome AI Ads [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for researching, making and running ads with AI: free ad libraries, official ads APIs
> and MCP servers for agents, agent skills, platform creative specs, open-source marketing tools and AI ad creative
> tools.

Every link was checked by hand when it was added. Commercial tools are labelled; nothing here pays to be listed.

## Contents

- [Ad libraries](#ad-libraries)
- [Creative inspiration](#creative-inspiration)
- [Official ads MCP servers](#official-ads-mcp-servers)
- [Ads APIs](#ads-apis)
- [Agent skills for marketing](#agent-skills-for-marketing)
- [Platform creative specs](#platform-creative-specs)
- [Open-source marketing tools](#open-source-marketing-tools)
- [AI ad creative tools](#ai-ad-creative-tools)
- [Learning](#learning)

## Ad libraries

Official, free transparency tools that show the ads running on each platform. The longest-running ads are usually the
ones that work.

- [Meta Ad Library](https://www.facebook.com/ads/library/) - Every active ad on Facebook, Instagram, Messenger and Threads, with start dates; reach and targeting for ads shown in the EU.
- [Google Ads Transparency Center](https://adstransparency.google.com/) - Search, Display and YouTube ads by advertiser or domain, with first and last shown dates.
- [TikTok Ad Library](https://library.tiktok.com/ads) - Every ad shown in the EU, searched by the advertiser's registered legal name.
- [TikTok Creative Center: Top Ads](https://ads.tiktok.com/business/creativecenter/inspiration/topads/pc/en) - Top-performing TikTok ads by region, industry and objective.
- [LinkedIn Ad Library](https://www.linkedin.com/ad-library/) - B2B ads by company or keyword, with impressions by country.
- [Microsoft Advertising Ad Library](https://adlibrary.ads.microsoft.com/) - Ads served on Bing and the Microsoft network in the EU.
- [Snap Political and Advocacy Ads Library](https://www.snap.com/political-ads) - Political and issue ads on Snapchat, with spend.

## Creative inspiration

- [TikTok Creative Center](https://ads.tiktok.com/business/creativecenter) - Trending hashtags, songs, creators and top ads on TikTok.
- [Think with Google](https://www.thinkwithgoogle.com/) - Google's research and case studies on search, YouTube and creative.
- [Ads of the World](https://www.adsoftheworld.com/) - Archive of agency campaigns from around the world.

## Official ads MCP servers

Servers run or published by the ad platforms themselves, so an AI agent can read and manage campaigns. Most are in beta;
check each page for access.

- [Google Ads MCP server](https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server) - Open-source and read-only, from the Google Ads API team.
- [Google Analytics MCP server](https://github.com/googleanalytics/google-analytics-mcp) - Read GA4 reports and account data from an agent.
- [Meta Ads AI connectors](https://www.facebook.com/business/news/meta-ads-ai-connectors) - Meta's hosted connector for reading and managing Meta ad accounts from AI assistants.
- [TikTok Agentic Hub](https://ads.tiktok.com/business/en/blog/tiktok-agentic-hub-ai-agents-skills-mcp) - TikTok's hub of skills and MCP access for agents working with TikTok for Business.
- [Amazon Ads MCP server](https://advertising.amazon.com/library/news/amazon-ads-mcp-server-open-beta) - Open beta for partners with Amazon Ads API access.
- [Microsoft Advertising MCP server](https://about.ads.microsoft.com/en/solutions/technology/agentic-commerce/mcp-server) - Pilot of an MCP server for Microsoft Advertising.

## Ads APIs

The APIs underneath, for building your own tools.

- [Google Ads API](https://developers.google.com/google-ads/api/docs/start) - Full campaign management for Search, Display, YouTube and Performance Max.
- [Meta Marketing API](https://developers.facebook.com/docs/marketing-apis/) - Campaigns, ad sets, ads, audiences and insights on Facebook and Instagram.
- [TikTok API for Business](https://business-api.tiktok.com/portal/docs) - Campaign management and reporting for TikTok ads.
- [LinkedIn Marketing API](https://learn.microsoft.com/en-us/linkedin/marketing/) - Campaigns, creatives, reporting and lead sync for LinkedIn ads.
- [Microsoft Advertising API](https://learn.microsoft.com/en-us/advertising/guides/) - Campaign management and reporting for Bing ads.
- [Reddit Ads API](https://ads-api.reddit.com/docs/) - Campaigns, ad groups, ads and reporting on Reddit.
- [Pinterest API](https://developers.pinterest.com/docs/api/v5/) - Pins, boards, ad campaigns and analytics.
- [Apple Ads API](https://developer.apple.com/documentation/apple_ads) - App Store search ads campaigns and reports.

## Agent skills for marketing

Agent Skills are folders of instructions an AI agent loads when a task matches.

- [Agent Skills specification](https://agentskills.io) - The open format, supported by Claude, Codex, Gemini CLI, Cursor and others.
- [marketing-skills](https://github.com/hermoso-ai/marketing-skills) - Standalone skills for ad hooks, UGC scripts, ad copy frameworks, ad-library research, competitor teardowns, campaign analysis and social specs.
- [marketingskills](https://github.com/coreyhaines31/marketingskills) - Skills for CRO, copywriting, SEO, analytics and growth.
- [skills.sh](https://skills.sh) - Directory and CLI (`npx skills add`) for installing skills into any agent.
- [ClawHub](https://clawhub.ai) - Registry of skills for OpenClaw and other agents.

## Platform creative specs

Sizes, ratios, lengths and file limits, from the platforms.

- [social-media-specs](https://github.com/hermoso-ai/social-media-specs) - Every platform's caption, ad-copy, image and video limits as sourced JSON, with a counting library and CLI.
- [Meta Ads Guide](https://www.facebook.com/business/ads-guide/update) - Specs for every Facebook and Instagram ad placement.
- [Google Ads responsive search ads](https://support.google.com/google-ads/answer/7684791) - Headline and description rules.
- [TikTok video ad specs](https://ads.tiktok.com/help/article/video-ads-specifications) - In-Feed ad sizes, lengths and text.
- [LinkedIn ad specs](https://www.linkedin.com/help/lms/answer/a426534) - Sponsored Content text and image limits.
- [X ad creative specs](https://help.x.com/en/business-and-advertising/creative-ad-specifications) - Image, video and text specs for X ads.
- [Pinterest product specs](https://help.pinterest.com/en/business/article/pinterest-product-specs) - Pin and ad formats.
- [Reddit image ad specs](https://business.reddithelp.com/s/article/image-ad-specifications) - Image ad sizes and headline length.

## Open-source marketing tools

- [Postiz](https://github.com/gitroomhq/postiz-app) - Self-hosted social media scheduling with an AI assistant.
- [Mixpost](https://github.com/inovector/mixpost) - Self-hosted social media management.
- [Mautic](https://github.com/mautic/mautic) - Marketing automation: email, landing pages, segments and campaigns.
- [listmonk](https://github.com/knadh/listmonk) - Self-hosted newsletter and mailing list manager.
- [Dub](https://github.com/dubinc/dub.link) - Link management and attribution for marketing links.
- [PostHog](https://github.com/PostHog/posthog) - Product analytics, session replay, feature flags and experiments.
- [Plausible Analytics](https://github.com/plausible/analytics) - Lightweight, privacy-friendly web analytics.
- [Umami](https://github.com/umami-software/umami) - Simple, privacy-focused web analytics.

## AI ad creative tools

Commercial products that generate ad images or videos. Listed alphabetically; descriptions are what each product says it
does.

- [AdCreative.ai](https://www.adcreative.ai/) - Generates ad creatives and banners with a predicted performance score.
- [Arcads](https://www.arcads.ai/) - UGC-style video ads with AI actors reading your script.
- [Creatify](https://creatify.ai/) - Turns a product URL into video ads with AI avatars.
- [HeyGen](https://www.heygen.com/) - AI avatar videos, voice cloning and video translation.
- [Higgsfield](https://higgsfield.ai/) - AI video generation with camera-motion presets and marketing templates.
- [Pencil](https://www.trypencil.com/) - Generative ad creative with brand kits and performance predictions.
- [Predis.ai](https://predis.ai/) - AI social media posts, carousels and video ads from a prompt.
- [Zeely](https://zeely.app/) - AI ads and landing pages for small businesses.

## Learning

Free, official courses from the platforms.

- [Meta Blueprint](https://www.facebook.com/business/learn) - Courses and certifications for Meta ads.
- [Google Skillshop](https://skillshop.withgoogle.com/) - Google Ads and Analytics training and certifications.
- [TikTok Academy](https://ads.tiktok.com/business/en/academy) - Courses on TikTok ads and creative.
- [LinkedIn Marketing Labs](https://training.marketing.linkedin.com/) - Courses on LinkedIn advertising.
- [Microsoft Advertising Learning Lab](https://learninglab.about.ads.microsoft.com/) - Training and certifications for Microsoft ads.

## Contributing

Suggestions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first: one link per pull request, a short
factual description, and no affiliate links.

---

Maintained by [Hermoso](https://hermoso.ai). Released under [CC0](LICENSE): to the extent possible under law, the
maintainers have waived all copyright and related rights to this list.
