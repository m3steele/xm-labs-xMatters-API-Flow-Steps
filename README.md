# xMatters REST API Flow Steps

This xMatters communication plan contains ~40 xMatters REST API Endpoints as Custom Flow Designer Steps.

<kbd>
  <img src="https://github.com/xmatters/xMatters-Labs/raw/master/media/disclaimer.png">
</kbd>

# Pre-Requisites

Add a Comment to an Event - xMatters Rest API Flow Steps-ORIGNIAL

- xMatters account - If you don't have one, [get one](https://www.xmatters.com)!

# Files

- [xMatters Rest API Flow Steps Communication Plan](xMattersRestAPIFlowSteps.zip)

# How it works

Import this communication plan and set Usage Permissions to give access to xMatters users or groups.

# Included Custom Steps

**AUDITS API** [link](https://help.xmatters.com/xmapi/index.html#audits)

- Get Event Audit Info

**DECIVES API** [link](https://help.xmatters.com/xmapi/index.html#devices)

- Get a Device
- Create a Device
- Modify a Device
- Delete a Device

**DEVICE NAMES API** [link](https://help.xmatters.com/xmapi/index.html#device-names)

- Get Device Names

**EVENTS API** [link](https://help.xmatters.com/xmapi/index.html#events)

- Get an Event
- Get Event Annotations
- Add a Comment to an Event
- Change the Status of an Event

**GROUPS API** [link](https://help.xmatters.com/xmapi/index.html#groups)

- Get a Group
- Create a Group
- Modify a Group
- Delete a Group
- Get a Groups Supervisors

**GROUP ROSTER API** [link](https://help.xmatters.com/xmapi/index.html#group-roster)

- Get the Group Roster
- Add Member to Group Roster
- Remove a Member from the Group Roster

**ON-CALL API** [link](https://help.xmatters.com/xmapi/index.html#on-call)

- Get Who is On Call

**PEOPLE API** [link](https://help.xmatters.com/xmapi/index.html#people)

- Create a Person
- Get a Persons Devices
- Get a Person
- Modify a Person
- Delete a Person

**SHIFTS API** [link](https://help.xmatters.com/xmapi/index.html#shifts)

- Get a Shift
- Get Members in a Shift
- Get shifts in a Group
- Create a Shift (DAILY)
- Create a Shift (EVERY_WEEKDAY)
- Create a Shift (EVERY_WEEKEND_DAY)
- Create a Shift (MONTHLY)
- Create a Shift (ONCE)
- Create a Shift (WEEKLY)
- Create a Shift (YEARLY)
- Delete a Shift
- Add Member to a Shift

**SITES API** [link](https://help.xmatters.com/xmapi/index.html#sites)

- Get a Site
- Get Sites
- Create a Site
- Modify or update a Site

**Misc Custom Functions for working with Results**

- Parse Array []
- Parse Object {} containing an Array []
- Print to Log

# xMatters Configuration

## Import the xMatters Communication Plan

1. Download the [xMatters Rest API Flow Steps Communication Plan](xMattersRestAPIFlowSteps.zip)

2. Follow instructions for [importing a communication plan](https://help.xmatters.com/ondemand/xmodwelcome/communicationplanbuilder/exportcommplan.htm)

## Set Usage Permissions on the Steps you would like to share

1. On the Developer tab, click Edit beside the **xMatters Rest API Flow Steps** communication plan and go to **Flows**.

2. Click on **API Form for Flow**.

3. Follow instructions for [Sharing a Custom Flow Step](https://help.xmatters.com/ondemand/xmodwelcome/flowdesigner/share-steps.htm)

## Use the steps

1. Drag the xMatters API step on the canvas and configure the step.
   [Get help using Flow designer](https://help.xmatters.com/ondemand/xmodwelcome/flowdesigner/flow-designer.htm)

The xMatters Rest API documentation will help you understand the inputs and outputs for each step.
[Get help with the xMatters API](https://help.xmatters.com/xmapi/index.html)

# Troubleshooting

[Get help using Flow designer](https://help.xmatters.com/ondemand/xmodwelcome/flowdesigner/flow-designer.htm)

[Get help with the xMatters API](https://help.xmatters.com/xmapi/index.html)
