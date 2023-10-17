# Developer Test

The Developer Test is a set of tasks we give our prospective web developers to see how they perform tasks. Please read the whold README.md before starting!

- We do not offer bonus points for doing more work.
- Additional tasks completed for this test are not taken into account.
- You are invited to suggest design or workflow changes, but they are not required.
- **This is not a pass/fail test.**
- This test is designed to help us gain insight into your problem solving, current skills, communication, etc.
- Your HTML and CSS should pass W3 validation Instructions.

## Tools & Resources

Here are a list of tools we use regularly at STAFFLINK. You will not require them all for this test, but I highly recommend you take a look into them, as you will almost certainly be using them everyday. If some of these appear overwhelming, don't stress. Once you get a deep enough understanding of each of them, you'll wonder why you didn't use something similar prior to today. :)

- [BootStrap 5.3](https://getbootstrap.com/)
- [Lando - Automated development environments](https://lando.dev/)
- [WordPress Specific Lando Recipe](https://docs.lando.dev/wordpress/)
- [Bedrock, by Roots.io](https://roots.io/bedrock/)
- [UnderStrap](https://github.com/understrap/understrap) OR
- [Sage - Advanced WordPress starter theme with Tailwind & Blade Templating](https://github.com/roots/sage)

## Task #1 - BootStrap, HTML, & CSS

[In this reference Figma file](https://www.figma.com/file/tGN4FqmtUOE7dvnEs9gYO9/Developer-Test-1.0?type=design&mode=design), there is a property grid that has 6 listings for sale. Using the latest version of BootStrap, recreate this section from static HTML/CSS. If you do not have a Figma account, sign up, and you will have access to the HTML/CSS classes/styling used.

#### Notes

- You do not need to use WordPress. This is a HTML/CSS test.
- Feel free to use the [Getting Started Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for BootStrap. Compiling assets are not required, but encouraged.

#### What We're looking for

- Clean, readable, formatted HTML
- BootStrap classes used as often as possible to reduce unnecessary additional CSS classes
- Responsiveness: use of BootStrap Columns, with Flex/Grid use
- Accuracy: Your attempt should mirror the design in a pixel perfect manner. If you see ways the design could be improved you're welcome to offer suggestions in your response.

## Task #2 - WordPress, Bedrock, and development

We use WordPress exclusively, along with BootStrap, modern JavaScript, SASS, PHP Composer, Git, etc. Bedrock is a modern WordPress boilerplate which easily allows us to use Composer, Git, and set development, staging, and production environments. Read more about it in the links above.

- Install and set up a Lando environment for local WordPress development
- Create a WordPress website locally using Bedrock as the boilerplate.
- Upload your dev environment to GitHub
- Use WP hooks/filters to:
  - disable comments
  - limit the excerpt length to 30 characters
  - delete attached media when a post is deleted.
 
## Submitting your developer test

**Upload your work to a public github repo, and share it with webservices@stafflink.com.au.**

Happy coding!
