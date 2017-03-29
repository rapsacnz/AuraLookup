# Lightning Loookup
An improved version of the original lightning lookup, using new CSS

To use in Salesforce, create a new Component bundle for the lookup, event and svg directory. Create an Apex controller + test from the classes in the apex directory

### Original Readme
Salesforce Lightning Design System Lookup Component
Intended use - embedded in a VF page.

Borrows heavily from Tony Scott's Version (from which this is forked) here:
http://meltedwires.com/2015/10/31/salesforce-lightning-lookup-component-v2/

Changes include:
- a simpler initialization in the Visualforce page
- an init routine on load (to load any pre-existing data)
- A callback method that is called after selection or clearing of data in the lookup.
