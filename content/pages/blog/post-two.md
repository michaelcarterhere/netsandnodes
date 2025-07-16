---
type: PostLayout
title: Are Zombies Coming for the Smart City?
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
date: '2025-06-07'
author: content/data/team/michael-carter.json
excerpt: >-
  What happens when IoT devices don't power off?
featuredImage:
  type: ImageBlock
  url: /images/20250607 zombies-smartcity.png
  altText: Post thumbnail image
media:
  url: /images/20250607 zombies-smartcity.png
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
  type: ImageBlock
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        textAlign: left
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: 'Stay up-to-date with my words ✍️'
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---

I often picture smart cities as networks of sensors, streetlights, traffic signals, and devices all seamlessly talking to each other. But there’s one problem that hides in plain sight—power. Not processing power. Not bandwidth. Electrical power. Behind every IoT sensor quietly tracking air quality or counting cars in a smart parking lot is a basic, unsolved question: How do we keep this thing powered, continuously, without plugging it in or replacing a battery every 18 months?

As I reviewed a recent article in Energy & Environmental Science, it struck me just how central this question is and how often I skip past it when I talk about scaling smart city tech. The article published by Marina Freitag and several others including Francesca Brunetti and Francesca De Rossi proposes a path to autonomous power for the Internet of Things.

Power is in fact a defining feature of IoT networks. They need low, continuous power that can be a fraction of a single watt. Some devices need to stay online to transmit data 24/7. Easy enough for a lightbulb or a smart device that can be plugged into an outlet or connected by extension cord. A lot of devices are installed in hard-to-reach places (underground, behind walls, inside equipment) and so they have unwired power supplies by default. A lot of sensors and devices are also kind of permanent fixtures and so they are expected to work continuously for years without intervention.

Batteries are an obvious answer for a lot of people. They are compact and convenient. I will admit however that I struggle to replace the batteries in some of my home devices on a semi-annual basis. What does that look like at scale? Smart city scale? With thousands of devices? And, even with advancements in recycling, batteries have obvious environmental costs.

One my earliest memories in life is the marvel of a solar powered calculator. I remember covering the solar cells and watching the calculator power off only to come back to life when I lifted my fingers off them. This actually points to one of the challenges associated with powering the Internet of Things with solar. Because again, many devices need to be placed indoors away from light, underground, or in shaded areas. Plus, you need to store energy for periods of low light… with a battery.

If we want the Internet of Things to have greater autonomy, and I believe we do, we need to solve the power problem.

To be honest, I really had not spent a lot of time thinking about this until I read the article from Marina and her team. It presents a novel approach that would provide autonomy of power to the Internet of Things. It’s way beyond my technical depth but what they seem to have done is produce a light-harvesting superconductor built with viologen-based polymers and added a fungal membrane that acts as an electrolyte barrier. It’s a three-terminal device combining a dye-sensitized solar cell with a compact energy storage unit. It works well under low-light conditions and shows great stability. Of course, this is a lab-scale prototype. But, it seems to show that integrated, cable-free, battery-free energy systems could play a role in the future: zombies.

To follow Marina’s work on zombies and the Internet of Things check out the article she published with her team in Energy & Environmental Science (2025) here:

https://pubs.rsc.org/en/content/articlelanding/2025/ee/d5ee01052g

#smartcities #InternetOfThings #IoT #CleanTech #ZombieSolarCells
