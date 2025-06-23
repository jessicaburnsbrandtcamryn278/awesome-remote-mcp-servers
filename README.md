# Awesome Remote MCP Servers

> 📧 **Subscribe to the Newsletter** Stay informed about new MCP servers and updates:
> [Subscribe](https://remotemcp.substack.com/subscribe)

> Not a developer & looking for ChatGPT Custom Integrations or Claude Custom Connectors? [Check out the Remote MCP Server List](https://www.remote-mcp.com/)

A curated, opinionated list of high-quality **remote** Model Context Protocol (MCP) servers. This repository focuses on listing official and well-maintained MCP servers that can be accessed over the internet, helping developers discover reliable and production-ready services for their AI applications.

## What is MCP?

[Model Context Protocol](https://modelcontextprotocol.io/) (MCP) is a protocol that enables AI models to interact with external tools and resources. Remote MCP servers allow clients to securely connect to these services over the internet. 

### What are Custom Integrations?

This is Claude's branding for connecting to remote MCP servers.

### What are Custom Connectors?

This is OpenAI's branding for connecting to remote MCP servers.

## Why Remote only?

Remote MCP servers are a more secure and easier way to use MCP. 
- Security wise, if you trust the provider's URL, and you are authenticated, then the security model is the same as using the Web.
- Ease of use wise, you can copy & paste the server URL and you're away. No installing NPM packages etc.
- They are the ONLY way to use MCP servers with Web based clients.

## How can I use an MCP server listed here?

There are two main ways to use remote MCP servers on this list. 

1. [Using a MCP ready client](#mcp-client) (Claude, ChatGPT, Cursor, etc.)
2. [In an API request to an LLM provider](#api-request) (OpenAI, Anthropic, Gemini, etc.)

## Authentication options

This list has a mix of authentication options, different methods are better suited to certain use cases:

- **OAuth 2.0**: This is an industry standard for authentication and is supported by MCP Clients like Claude. Adoption amongst clients is growing, but not yet widespread.
 For this all you need to connect is the server URL, and the client will guide you through the authentication flow.
- **API Key**: An alternative to OAuth 2.0, this required to have an API key for the server. This is useful when using an API request to an LLM provider, rather than an MCP client.
- **Open**: Easy to copy and paste and get started, but not as secure. This is the easiest way to get started, but not the most secure.


## Quality Criteria

This is not an exhaustive list of all remote MCP servers. We maintain high standards for inclusion:

- **Official Support**: Servers that are maintained by their underlying companies are preferred
- **Production Ready**: Must be stable and suitable for production use
- **Active Maintenance**: Regular updates and bug fixes
- **Security**: Proper authentication and security measures, with OAuth 2.0 or API Key support required
- **Reliability**: Proven track record of uptime and performance
- **Community**: Active user community and support channels

## Remote MCP Server List

| Name | Category | URL | Authentication | Maintainer |
|------|----------|-------------|----------------|------------|
| Asana | Project Management | `https://mcp.asana.com/sse` | OAuth2.1 | [Asana](https://asana.com) |
| Atlasian | Software Development | `https://mcp.atlassian.com/v1/sse` | OAuth2.1 | [Atlassian](https://atlassian.com) |
| Cloudflare Workers | Software Development | `https://bindings.mcp.cloudflare.com/sse` | OAuth2.1 | [Cloudflare](https://cloudflare.com) |
| Cloudflare Observability | Observability | `https://observability.mcp.cloudflare.com/sse` | OAuth2.1 | [Cloudflare](https://cloudflare.com) |
| Dialer | Outbound Phone Calls | `https://getdialer.app/sse` | OAuth2.1 | [Dialer](https://getdialer.app) |
| GitHub | Software Development | `https://api.githubcopilot.com/mcp` | OAuth2.1 | [GitHub](https://github.com) |
| Globalping | Software Development | `https://mcp.globalping.dev/sse` | OAuth2.1 | [Globalping](https://globalping.io/) |
| Intercom | Customer Support | `https://mcp.intercom.com/sse` | OAuth2.1 | [Intercom](https://intercom.com) |
| Linear | Project Management | `https://mcp.linear.app/sse` | OAuth2.1 | [Linear](https://linear.app) |
| Neon | Software Development | `https://mcp.neon.tech/sse` | OAuth2.1 | [Neon](https://neon.tech) |
| Octagon | Market Intelligence | `https://mcp.octagonagents.com/mcp` | OAuth2.1 | [Octagon](https://octagonai.co) |
| OneContext | RAG-as-a-Service | `https://rag-mcp-2.whatsmcp.workers.dev/sse` | OAuth2.1 | [OneContext](https://onecontext.ai) |
| PayPal | Payments | `https://mcp.paypal.com/sse` | OAuth2.1 | [PayPal](https://paypal.com) |
| Plaid | Payments | `https://api.dashboard.plaid.com/mcp/sse` | OAuth2.1 | [Plaid](https://plaid.com) |
| Prisma Postgres | Database |  `https://www.prisma.io/docs/postgres/integrations/mcp-server#remote-mcp-server` | OAuth2.1 | [Prisma Postgres](https://prisma.io/postgres)
| Scorecard | AI Evaluation | `https://scorecard-mcp.dare-d5b.workers.dev/mcp` | OAuth2.1 | [Scorecard](https://scorecard.io) |
| Sentry | Software Development | `https://mcp.sentry.dev/sse` | OAuth2.1 | [Sentry](https://sentry.io) |
| Square | Payments | `https://mcp.squareup.com/sse` | OAuth2.1 | [Square](https://square.com) |
| Turkish Airlines | Airlines | `https://mcp.turkishtechlab.com/mcp` | OAuth2.1 | [Turkish Technology](https://mcp.turkishtechlab.com/) |
| Webflow | CMS | `https://mcp.webflow.com/sse` | OAuth2.1 | [Webflow](https://webflow.com) |
| Wix | CMS | `https://mcp.wix.com/sse` | OAuth2.1 | [Wix](https://wix.com) |
| Kollektiv | Documentation | `https://mcp.thekollektiv.ai/sse` | Oauth2.1 | [Kollektiv](https://github.com/alexander-zuev/kollektiv-mcp) |
| Simplescraper | Web Scraping | `https://mcp.simplescraper.io/mcp` | OAuth2.1 | [Simplescraper](https://simplescraper.io) |
| WayStation | Productivity | `https://waystation.ai/mcp` | OAuth2.1 | [WayStation](https://waystation.ai) |
| Cloudflare Docs | Documentation | `https://docs.mcp.cloudflare.com/sse` | Open | [Cloudflare](https://cloudflare.com) |
| DeepWiki | RAG-as-a-Service | `https://mcp.deepwiki.com/sse` | Open | [Devin](https://devin.ai/) |
| Hugging Face | Software Development | `https://hf.co/mcp` | Open | [Hugging Face](https://huggingface.co) |
| Semgrep | Software Development | `https://mcp.semgrep.ai/sse` | Open | [Semgrep](https://semgrep.dev/) |
| Remote MCP | MCP Directory | `https://mcp.remote-mcp.com` | Open | [Remote MCP](https://remote-mcp.com/) |
| Bitte | Blockchain Data Analysis | `https://mcp.bitte.ai/sse` | Open | [Bitte](https://bitte.ai) |
| McPoogle | MCP Server Search Engine | `https://mcp.mcpoogle.com/sse` | Open | [McPoogle](https://www.mcpoogle.com) |
| LLM Text | Data Analysis | `https://mcp.llmtxt.dev/sse` | Open | [LLM Text](https://llmtxt.dev) |
| GitMCP | Software Development | `https://gitmcp.io/docs` | Open | [GitMCP](https://gitmcp.io) |
| HubSpot | CRM | `https://app.hubspot.com/mcp/v1/http` | API Key | [HubSpot](https://hubspot.com) |
| Stripe | Payments | `https://mcp.stripe.com/` | API Key | [Stripe](https://stripe.com) |
| Needle | RAG-as-a-service | `https://mcp.needle-ai.com/mcp` | API Key | [Needle](https://needle-ai.com) |
| Zapier | Automation | `https://mcp.zapier.com/api/mcp/mcp` | API Key | [Zapier](https://zapier.com) |
| Apify | Web Data Extraction Platform | `https://mcp.apify.com` | API Key | [Apify](https://apify.com) |
| Mercado Pago | Payments | `https://mcp.mercadopago.com/mcp` | API Key | [Mercado Pago MCP Server](https://mcp.mercadopago.com/) |

### MCP Clients

A complete list of MCP clients can be found [here](https://modelcontextprotocol.io/clients). Here are some examples of installation with Claude.

### Claude

#### Custom Integrations

Anthropic has added [native support for Remote MCP into Claude](https://www.anthropic.com/news/integrations). It's currently available on Pro plans.

Add these servers as *Custom Integrations* in the integrations section of your Claude app settings.

##### Step-by-Step Instructions

1. Navigate to Settings > Profile
2. Locate the "Integrations" section
3. Click "Add more"
4. Add your integration's remote MCP server URL
5. Finish configuring your integration by clicking "Add"

Full instructions can be found [here](https://support.anthropic.com/en/articles/11175166-about-custom-integrations-using-remote-mcp).

### ChatGPT

#### Custom Connectors 

OpenAI's support for remote MCP is currently in beta. It's integrated into the Deep Research function. 

Full instructions can be found [here](https://help.openai.com/en/articles/11487775-connectors-in-chatgpt#h_d2a53d4230).

##### Step-by-Step Instructions

1. Navigate to Settings > Profile
2. Locate the "Connectors" section
3. Click "Add Connector"
4. Add your connector's remote MCP server URL
5. Finish configuring your connector by clicking "Save"

### Other MCP Clients 

Note: As the MCP spec is still in development, not all clients may support all features. In particular client support of OAUTH is not yet widespread.

For desktop clients the configuration you need to add to your client's config file will be 

```json
{
  "mcpServers": {
    "<REMOTE_MCP_SERVER_NAME>": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "<REMOTE_MCP_SERVER_URL>"
      ]
    }
  }
}
```

### API Libraries

Official support for MCP in API requests is supported by the following LLM providers:

- [Anthropic](https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector)
- [OpenAI](https://platform.openai.com/docs/guides/tools-remote-mcp)
- [Gemini](https://ai.google.dev/gemini-api/docs/function-calling?example=meeting#model_context_protocol_mcp)

Note that it's easier to get started with API Token, based authentication for these servers. See the [FAQs](#faqs) section for more details.


## FAQs

### Can I use an Oauth MCP server in an API request to an LLM provider?

Yes, but you will need to manage your own OAuth authentication flow, in order to obtain an access token.
A quick way to obtain an access token to test a server is to follow the instructions in Anthropic's guide [Obtaining an access token for testing](https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector#obtaining-an-access-token-for-testing) section.
This is not generally recommended for production use, as it is not a secure way to authenticate users.

### Why do some servers have a `/sse` and others a `/mcp`?

The `/sse` endpoint is for the Server Sent Events (SSE) protocol. It is being slowly deprecated in favor of the `/mcp` endpoint.
The `/mcp` endpoint is for the Streamed HTTP protocol. 
In the future some clients may only support adding servers by the prefix preceding the 'sse' or 'mcp' and self-discovering full URL.
We will update this list as we see this happening.

## Contributing

We welcome contributions! Please follow these guidelines:

1. Fork the repository
2. Add your remote MCP server to the appropriate category
3. Include the following information:
   - Server name
   - Category
   - URL
   - Authentication requirements (Only OAuth 2.0, following the MCP spec is supported)
   - Example usage
4. Submit a pull request

## Acknowledgments

- Inspired by the [Model Context Protocol](https://modelcontextprotocol.io/)

## Community

Join the MCP community to stay updated and connect with other developers:

- [Reddit Community](https://www.reddit.com/r/mcp/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
