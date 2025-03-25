# Ido Schacham - My Open Source Projects

Well, hello there! 👋 Here are some open source projects that I worked on.

## The Bubble Figure

When Wunderdog participated in the Grand One 2023 design awards in Helsinki, we wanted to create an interactive art installation. 
A team of volunteer designers and developers came together to conceptualize and implement The Bubble Figure within two months. 

This installation used a webcam to recognize people and transform them into colorful bubble figures, allowing them to interact 
with falling shapes in a playful way—all within the visual language of Grand One 2023.

To bring this idea to life, we used Three.js, TensorFlow.js, and cannon-es, despite having no prior experience with this stack. 
As early adopters of ChatGPT, we leveraged it to understand the technologies and generate code examples. 

While it was a collaborative effort, I took significant initiative—helping create the concept, creating rapid prototypes, 
leading other developers, coding the solution, and coordinating with designers. The final installation was a hit with the 
audience, and after the event, we took the time to refactor the code to TypeScript. 

Easily one of the most fun development projects I've been part of!

* [Dev.to post](https://dev.to/idosius/the-bubble-figure-integrating-tensorflowjs-with-threejs-and-cannon-es-to-create-interactive-art-b8e)
* [Demo](https://wunderdogsw.github.io/go-23-app/) - make sure to enable camera and step back so that your pose is detected
* [GitHub](https://github.com/wunderdogsw/go-23-app)

## Klepto

While on the bench at Wunderdog, I wanted to learn new technologies. So, I built Klepto, a platform for freely sharing and stealing ideas.

This MVP is built with Svelte, SvelteKit, MongoDB, and Svelte Material UI. During the process, I also implemented user authentication using JWT.

* [Dev.to post](https://dev.to/idosius/mongodb-atlas-hackathon-2022-on-dev-4a4i)
* [Demo](https://klepto.vercel.app/)
* [GitHub](https://github.com/wunderdogsw/klepto)

## gatsby-plugin-automatic-redirects

While working on the Wunderdog website, I realized that when paths or slugs were changed, Gatsby did not create any redirects for them.

This is a problem—not only because previous SEO scores may be lost, but also because users who click an old link would get a 404 error.

Seeing that there was no solution to this issue, I developed a Gatsby plugin that automatically creates redirects when slugs or paths change.

* [Blog post](https://www.wunderdog.io/blog/how-to-manage-redirects-in-gatsby-automatically)
* [GitHub](https://github.com/wunderdogsw/gatsby-plugin-automatic-redirects)
* [npm](https://www.npmjs.com/package/gatsby-plugin-automatic-redirects)
