
# wordpress_docs

## Tips:
Better performance and SEO:
1. Image optimization

Set Globals before working on project for being more productive:
1. Fonts
2. Font sizes - all devices
3. Colors

Typography:
1. Use rems
2. Use em line-height, padding, and margins

Responsive:
Elementor - check under Responsive section

____________________________

Typography font scaling:
To create a style guide for font sizes, do you find the hero(heading) font size and then go.from there?


ChatGPT said:
Yes, that’s a very effective way to start a font size scale — by choosing your hero (or largest heading) font size first, then working down from there using a type scale.

Here's a practical approach:
✅ 1. Start with the hero size
Pick a font size that feels right for your most important text — usually the main headline or hero text. This could be something like 48px, 64px, or even larger depending on the design and screen size.

Example:
Hero (H1) = 64px

✅ 2. Choose a base body size
Most UI designs use 16px or 18px as a body font base. This should be readable at all screen sizes and used for paragraphs, form labels, etc.

Example:
Body = 16px

✅ 3. Pick a type scale
Use a modular scale to create the rest of your headings. Common ratios include:

Minor Third (1.2)

Major Third (1.25)

Perfect Fourth (1.333)

Golden Ratio (1.618)

You can use a modular scale calculator to generate consistent font sizes.

Example (starting from 16px, Perfect Fourth scale 1.333):

Body: 16px

H6: 21px

H5: 28px

H4: 37px

H3: 49px

H2: 65px

H1: 86px

✅ 4. Adjust for hierarchy and use case
Once you’ve generated the scale, tweak it slightly if needed to:

Keep mobile readability in mind

Maintain a visual hierarchy

Adjust for line-height and font-weight

✅ 5. Document your scale
Create a guide like:

scss
Copy code
// Example font size tokens
--font-size-body: 16px;
--font-size-h6: 21px;
--font-size-h5: 28px;
--font-size-h4: 37px;
--font-size-h3: 49px;
--font-size-h2: 65px;
--font-size-h1: 86px;
--font-size-hero: 120px;
Summary
✅ Yes — start with the hero font size (top of your hierarchy), then create a type scale down to your body text. Adjust for balance and readability, then lock it in as your system.

______________________________

Hero image:
Find an image which reflects the message being convyed. 
1. Process of working with the company - clients get to view. A behind-the-scenes view
2. Face of the brand
3. Product focused image
4. Benefits focused image - what benefit the client gets by working with you
5. Grab attention: humans view shapes first and then words so need a strong image
6. Set the mood - create the atmosphere: actions
7. High quality
8. Leave space for text - if image is busy you cant read the text or CTA
9. Match your brand

All images must reflect brand personality -tone, and feel

--------------------------------------------------------------

## Fake navigation:

## Image optimizer:
1.Image optimizer plugin: Compress, Resize, and Optimize images
2. Adjust hero image so it works with the context

How to use? 
1. Under media section in Wordpress panel
2. Click Optimize All


## Spam gmail:
![image](https://github.com/user-attachments/assets/1e2a2997-1113-4f5b-ac4a-031811c5e37c)
![image](https://github.com/user-attachments/assets/ab8af659-7519-483d-80cd-e50719b1c3c5)
![image](https://github.com/user-attachments/assets/c52d01d1-774c-4d68-af6b-07edbc0fc2b7)
![image](https://github.com/user-attachments/assets/0854fdb4-23bf-4c45-9188-7426a6655326)


## Navigation:

1. Appreance -> Customize
2. Header -> Primary Menu & Transparent Header

## Navigation - font size change. Can add custom css as well
1. Customize
2. Header
3. Select Menu - example: primary
4. Design -> font size

Navigation links:
![image](https://github.com/user-attachments/assets/87db2290-dc1e-4e01-afa9-3d8308b1369d)
Instead go to Menus -> Appreances -> Customize:
![image](https://github.com/user-attachments/assets/5de4eabb-c83c-40f0-a4a1-9e6a10a3d59e)
![image](https://github.com/user-attachments/assets/67267256-0992-41f4-b934-779923950079)
Delete all Invalid values

Now create custom links and connect them to sections you want to go to on your single page website:
1. ![image](https://github.com/user-attachments/assets/ff0fa240-f416-40f4-86c4-86aba1718a15)
2. ![image](https://github.com/user-attachments/assets/0f5a96b7-09b3-40dc-ac41-c6b6bc197795)
3. Link section with header menu link
   ![image](https://github.com/user-attachments/assets/f9a06715-9370-4d95-823b-2148fdcc56b1)

## Email via button/link:
![image](https://github.com/user-attachments/assets/ce3a7a03-fa5e-4022-aa1b-0751f6b654cc)


Tip:
If a certain element isn't working on any given device, check to see if its hidden via elementor:
![image](https://github.com/user-attachments/assets/d6892414-06b9-4f0c-8020-00447700ef23)

If email links dont open in the browser and you see - mailto:"emailaddress" it means there is an issue on the browser. Need to allow the setting.
https://stackoverflow.com/questions/17517600/mailto-links-do-nothing-in-chrome-but-work-in-firefox
https://www.youtube.com/watch?v=lqojvnSudCo







## Global settings:
1. Colors
2. Fonts




