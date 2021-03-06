# Moovit is using OpenStreetMap data illegally

This company is using OpenStreetMap data for their Android Application. It is a good news, but unfortunately this company failed to credit authors of this data.

Note that OpenStreetMap data is available for free and there are very limited requirements. And they still failed to follow them, [what is not OK](../README.md). Note that it is also illegal, as ODBL licence used by OpenStreetMap requires proper attribution, and requires it to be properly displayed. Hiding one in place where noone will see it is both against the common sense [and the licence](../README.md).

## Fixing
Can be easily fixed by placing text crediting OSM in bottom right corner, something like `© OpenStreetMap contributors` or something similar.

Missing attribution may be also partially remediated by adding something like "Map powered by OpenStreetMap data" at the startup screen.

There is a deeply hidden and insufficient attribution. It is not in a place ever visited by a typical user.

Currently encountering it requires

- enabling sidebar
- scrolling down sidebar
- selecting "Partners" entry
- as bonus, it shows CC-BY-SA as a licence and it is not clear what is credited to OpenStreetMap

## Reported

Reported on the 13th September 2019 (moovitapp.zendesk.com assigned id 343713).

Moovit was reminded about this issue by emailing them on

- 11th November 2019
- 27th November 2019
- 6th January 2020

On the 2019-12-07 it was reported to OSMF Legal Working Group, report was assigned id 2019120710000072.

On the 2020-03-12 the problem was discussed during OSMF Legal Working Group meeting. The LWG will send a fax message. Hopefully it will be taken more seriously than my emails.

## Reaction of the company

Moovit failed to fix issue, failed to specify when it will be fixed. The company also failed to admit that there is actually something to be fixed.

Their Android application continues to use OSM data illegally two months later (checked on 2020-01-23).

On the 3th October Moovit representative replied claiming that they are consulting with their legal team.

On the 12th November they claimed that it will be fixed "soon", what turned out to be untrue. As of 2020-01-23 it was their last activity.

Note that Moovit is using OSM data also for their website and they are attributing OSM there, so they do not appear to be malicious/evil.

## Problem reproduction

1. Install Moovit on an Android phone, run it.
2. Try to find a required attribution.

## Typical Mooovit interface using OpenStreetMap data

Applies to Android phones, iPhone app is using alternative data provider with a very low data quality.

![Moovit application misssing proper attribution 2019-11-17.png](Moovit_application_misssing_proper_attribution_2019-11-17.png)
