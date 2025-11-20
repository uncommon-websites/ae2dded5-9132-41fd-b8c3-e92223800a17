<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Institutional-grade deal analysis powered by AI"
	subtitle="Connect with top-tier investors through machine learning models trained on elite investment patterns. Get the credible introductions you need to close your Series A."
	imageSrc="/generated/image-a-close-up-documentary-style-photograph-.webp"
/>
<LogoScroller
	label="Trusted by forward-thinking founders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Leveling the playing field"
	text="We analyze startup investment opportunities using machine learning trained on patterns from top-tier venture firms. Series A founders gain access to institutional-grade deal insights and credible investor introductions—without needing warm connections. Think of it as having a world-class investment analyst and a well-connected partner on your team."
/>

<Testimonials
	testimonials={[
		{
			name: "Arjun Mehta",
			position: "Co-founder & CEO",
			company: "Quantum Health",
			quote:
				"We saved three months of networking time and connected with exactly the right Series A investors. The AI analysis highlighted deal risks we hadn't considered, which strengthened our pitch and helped us close at a 20% higher valuation.",
			image: "/generated/image-documentary-style-professional-headshot-.webp"
		},
		{
			name: "Nia Williams",
			position: "Founder & CEO",
			company: "Zenith Analytics",
			quote:
				"Instead of cold outreach with a 2% response rate, we secured warm introductions to tier-one VCs who actually understood our market. The platform's deal analysis saved us from pursuing three investors with misaligned portfolio strategies—that alone was worth months of wasted effort.",
			image: "/generated/image-documentary-editorial-portrait-of-a-pois.webp"
		},
		{
			name: "Kenji Tanaka",
			position: "Co-founder & CEO",
			company: "Meridian Systems",
			quote:
				"We reduced our fundraising timeline from 8 months to 4 months by targeting investors with proven interest in our space. The institutional-grade analysis gave us credibility we didn't have as first-time founders, and we closed our Series A 30% oversubscribed.",
			image: "/generated/image-editorial-style-professional-headshot-of.webp"
		}
	]}
/>

<Features
	title="Built for founders who demand excellence"
	subtitle="Machine learning models trained on elite investment patterns to connect you with the right capital at the right time"
	features={[
		{
			title: "Elite investor matching",
			description:
				"Connect with top-tier VCs who have invested in companies like yours. Our AI analyzes your business model, traction, and market position to identify investors actively seeking deals in your space."
		},
		{
			title: "Institutional-grade deal analysis",
			description:
				"Get the same level of analysis that Sequoia and a16z use internally. Machine learning models evaluate your startup across 40+ dimensions that correlate with Series A success."
		},
		{
			title: "Investment pattern recognition",
			description:
				"Understand what top investors actually fund versus what they say they fund. Our models learn from thousands of successful deals to identify the characteristics that drive funding decisions."
		},
		{
			title: "Credibility scoring",
			description:
				"Know exactly how investors will perceive your startup before you reach out. We score your company against the patterns that drive partner-level interest at prestige firms."
		},
		{
			title: "Strategic introduction timing",
			description:
				"Reach out when investors are most receptive. Our platform tracks fund cycles, portfolio gaps, and market momentum to optimize your outreach timing."
		},
		{
			title: "Deal flow intelligence",
			description:
				"Stay ahead of market trends with insights into what top VCs are funding right now. Understand competitive positioning and adjust your pitch accordingly."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Ready to close your Series A?"
	subtitle="Join the founders who've already secured their funding"
	description="Stop wasting months on cold outreach and misaligned investors. Get institutional-grade analysis and credible introductions to the VCs who want to fund companies like yours. Your next investor meeting could be your last."
	imageSrc="/generated/image-a-confident-startup-founder-mid-30s-stan.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start your analysis",
			variant: "primary"
		},
		{
			href: "/schedule-demo",
			label: "Schedule a demo",
			variant: "secondary"
		}
	]}
/>
