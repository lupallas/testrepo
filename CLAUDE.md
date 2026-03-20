# CLAUDE.md - SEO Skills & Instructions

## SEO Analysis & Optimization Skills

When asked to perform SEO tasks, follow these specialized instructions:

---

### 1. Keyword Research

When asked to do keyword research:
- Identify primary, secondary, and long-tail keywords for the given topic
- Group keywords by search intent: informational, navigational, transactional, commercial
- Estimate relative search volume (high/medium/low) and competition level
- Suggest keyword clusters (groups of related terms to target together)
- Provide LSI (Latent Semantic Indexing) keyword suggestions
- Output in a structured table format

### 2. On-Page SEO Audit

When asked to audit a page or HTML file:
- Check title tag (length 50-60 chars, includes primary keyword)
- Check meta description (length 150-160 chars, includes CTA and keyword)
- Verify H1 tag (one per page, includes primary keyword)
- Check heading hierarchy (H1 > H2 > H3, logical structure)
- Analyze keyword density (aim for 1-2% for primary keyword)
- Check image alt tags (descriptive, include keywords where natural)
- Verify internal and external links
- Check URL structure (short, descriptive, hyphenated)
- Assess content length relative to competitors
- Check for canonical tags
- Verify Open Graph and Twitter Card meta tags
- Check schema/structured data markup
- Score each item as PASS, WARN, or FAIL with specific recommendations

### 3. Technical SEO Audit

When asked to do a technical SEO review:
- Check robots.txt configuration
- Verify sitemap.xml exists and is properly formatted
- Assess page load factors in code (image sizes, script loading, CSS optimization)
- Check mobile responsiveness indicators in HTML/CSS
- Verify proper use of canonical URLs
- Check for noindex/nofollow tags
- Assess URL structure and hierarchy
- Check hreflang tags for multilingual sites
- Verify HTTPS usage in links
- Check for duplicate content indicators
- Assess pagination handling (rel=next/prev or load more)
- Review structured data / JSON-LD implementation

### 4. Content Optimization

When asked to optimize content for SEO:
- Rewrite title tags and meta descriptions for click-through rate
- Optimize heading structure with target keywords
- Improve keyword placement (first 100 words, headings, conclusion)
- Add internal linking suggestions
- Suggest content gaps to fill based on the topic
- Improve readability (short paragraphs, bullet points, clear language)
- Add FAQ sections targeting "People Also Ask" queries
- Suggest schema markup for the content type (Article, FAQ, HowTo, etc.)
- Keep the original tone and voice while improving SEO signals

### 5. Meta Tag Generator

When asked to generate meta tags:
- Create optimized title tag (50-60 characters)
- Create compelling meta description (150-160 characters) with CTA
- Generate Open Graph tags (og:title, og:description, og:image, og:type, og:url)
- Generate Twitter Card tags (twitter:card, twitter:title, twitter:description, twitter:image)
- Suggest canonical URL
- Generate relevant schema.org JSON-LD markup
- Output as copy-paste ready HTML

### 6. Competitor Content Analysis

When asked to analyze competitor content:
- Compare content length, structure, and depth
- Identify keywords they rank for that the user may be missing
- Analyze their heading structure and topic coverage
- Note their internal linking patterns
- Identify content gaps and opportunities
- Suggest a content brief to outperform the competitor

### 7. SEO Content Brief Generator

When asked to create a content brief:
- Define primary and secondary keywords
- Suggest optimal content length based on topic
- Outline recommended heading structure (H1, H2, H3)
- List questions to answer (from "People Also Ask" style queries)
- Define target search intent
- Suggest internal links to include
- Recommend external authoritative sources to reference
- Specify schema markup type to use
- Include a suggested meta title and description

### 8. Schema Markup Generator

When asked to generate schema/structured data:
- Determine the appropriate schema type (Article, Product, FAQ, HowTo, LocalBusiness, etc.)
- Generate valid JSON-LD markup
- Include all recommended properties for the schema type
- Validate the structure follows schema.org specifications
- Output as ready-to-paste script tag

### 9. Internal Linking Strategy

When asked about internal linking:
- Map the site's content hierarchy
- Identify hub/pillar pages and cluster content
- Suggest contextual link placements with anchor text
- Recommend a silo structure if appropriate
- Flag orphan pages (pages with no internal links pointing to them)

### 10. SEO Reporting

When asked for an SEO report or summary:
- Use clear sections with headers
- Include a priority-ranked list of action items
- Score items by impact (high/medium/low) and effort (high/medium/low)
- Present data in tables where appropriate
- Always end with "Quick Wins" (high impact, low effort items)

---

## Output Format Preferences

- Use tables for comparisons and audits
- Use checklists for action items
- Use code blocks for HTML/JSON-LD output
- Always prioritize recommendations by impact
- Be specific and actionable (not vague advice)
- When analyzing files, reference specific line numbers

## Common SEO Commands

When I say:
- **"audit this page"** - Run a full on-page SEO audit (skill #2)
- **"keyword research for [topic]"** - Run keyword research (skill #1)
- **"optimize this content"** - Run content optimization (skill #4)
- **"generate meta tags for [topic/page]"** - Generate all meta tags (skill #5)
- **"create a content brief for [topic]"** - Generate a full content brief (skill #7)
- **"add schema for [type]"** - Generate JSON-LD schema markup (skill #8)
- **"SEO report"** - Run a comprehensive audit and generate a report (skill #10)
