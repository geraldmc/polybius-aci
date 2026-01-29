# Polybius

**A democratic health index, powered by political science**

Polybius is an experimental tool that generates a score for how well a political system is adhering to democratic principles. It's named after the ancient Greek historian who first theorized checks and balances in his analysis of the Roman Republic.

> ⚠️ **This project is under active development.** Expect rough edges, evolving methodology, and breaking changes.

## What It Does

Polybius pulls live news, reports, and polling data via Anthropic's API, then analyzes them across ten factors:

| Factor | What it measures |
|--------|------------------|
| **Judicial Independence** | Can courts check executive power? |
| **Federalism / Regional Resistance** | Are subnational governments pushing back? |
| **Political Competition** | Is meaningful opposition possible? |
| **Media Capture** | Who controls the information environment? |
| **Civil Society** | How dense and free are non-state organizations? |
| **Public Opinion** | What does the public actually support? |
| **Mobilizational Balance** | Can the opposition mobilize as effectively as the regime? |
| **State Capacity** | What coercive and bureaucratic power can the regime deploy? |
| **Corporate Compliance** | Are business elites resisting or accommodating? |
| **Election Interference** | Is the electoral process being manipulated? |

## Theoretical Models

Rather than relying on a single framework, Polybius runs the data through **eleven different theoretical models** drawn from political science and historiography—each weighing the factors differently.

A few examples:

- **Tocquevillean** — emphasizes civil society and associational life
- **Marxian** — focuses on capital-labor relations and class dynamics
- **Linzian** — looks at regime type transitions and democratic breakdown patterns

The full list of models and their weightings is available in [MODELS.md](./docs/MODELS.md).

## Historical Analogies

Polybius draws on data from [V-Dem](https://v-dem.net/), the [Polity Project](https://www.systemicpeace.org/polityproject.html), and [Freedom House](https://freedomhouse.org/) to surface historical parallels—moments when other democracies faced similar conditions.

## Social Signals

A real-time module that assesses the current state of play:

- **Party coordination** — how unified is the regime's political coalition?
- **Media alignment** — are major outlets and figures supporting or resisting?
- **Market constraints** — is capital acting as a brake on executive action?

## Tech Stack

Built with [Next.js](https://nextjs.org/). Setup instructions are in [SETUP.md](./docs/SETUP.md).

## Contributing

This is a research project in progress, and contributions are welcome—especially from people with backgrounds in political science, democratic theory, or data journalism. See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to get involved.

## License

[MIT](./LICENSE)