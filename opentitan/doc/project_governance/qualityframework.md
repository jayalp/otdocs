# Quality Framework

The quality framework is how [lowRISC](./lowRISC.md) and OpenTitan partners develop open silicon for commercial use

It combines best practices from both open source software and commercial silicon development, including:
- A clear governance structure
- Development in the open (and embargoed work where required) using permissive licensing (Apache 2.0 typically)
- Code review and the requirement that all changes go through an approval process
- Emphasis on quality documentation and accessible verification collateral
- Continuous integration testing

## Quality standards for open hardware IP

In order to gauge the quality of the different IP that is in our repository, we define a series of [Hardware Development Stages](./development_stages.md) to track the designs.
The current status of different IP is reflected in the [Hardware Dashboard](../../hw/README.md).

The final state for developed IP is *Signed Off*, indicating that design and verification is complete, and the IP should be bug free.

To make it to that stage, a [Hardware Signoff Checklist](./checklist/README.md) is used to confirm completion.
[Here](https://github.com/lowRISC/opentitan/blob/master/util/uvmdvgen/checklist.md.tpl) is a template that can be used as a checklist item.
