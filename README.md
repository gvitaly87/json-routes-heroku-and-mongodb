# CPNT262 - Assignment 4 - Deployed Static Express Website

## General Information

- Course: CPNT-262 - Web Client & Server Prog.
- Author: [Vitaly Gins](https://github.com/gvitaly87) - Repository owner and maintainer.
- Github Links:
  - [GH repo](https://github.com/gvitaly87/cpnt262-a4)
  - [Deployed Heroku URL](https://vit-cpnt-262-a4.herokuapp.com/)

### Context

A three page fruit website, with a mock login, and registration page. The webpage is using ejs to generate dynamic pages. The website also sends a json api when requested to populate the gallery on the front end.

### Notes

- The npm module used is dayJS, it is used on the footer and on the error page.
- Error messages are fully displayed on the server console while providing the client with a generic code/message.
- Routes is exported as a function so I can pass arguments to it in A5
- The views use a template which then fills in the page content
- PathURL is replaced with imgName and imgExt.
- Can click images to stretch them to a full screen
- Animated Gallery was removed(might return to it later),

---

### Dependencies

- [Express](https://www.npmjs.com/package/express) Framework to handle the server side routing
- [dotenv](https://www.npmjs.com/package/dotenv) to load environment variables
- [ejs](https://www.npmjs.com/package/ejs) In order to work with javascript templates to generate dynamic pages
- [dayJS](https://www.npmjs.com/package/dayjs) is a minimalist JavaScript library that parses, validates, manipulates, and displays dates and times for modern browsers with a largely Moment.js-compatible API. If you use Moment.js, you already know how to use Day.js.

---

### Images

- peaches image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/bunch-of-peach-2363356/)
- watermelons image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/watermelons-2288692/)
- melons image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/4136869/)
- apples-red image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/4136829/)
- limes image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/4136712/)
- pears image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/2288697/)
- oranges image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/oranges-2288683/)
- plums image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/2288686/)
- pomelos image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/yello-fruits-lot-2286781/)
- bananas image by [Marco Antonio](https://www.pexels.com/@victorino) from [Pexels](https://www.pexels.com/photo/2286775/)
- header2.jpg image by [Andrea Piacquadio](https://www.pexels.com/@olly) from [Pexels](https://www.pexels.com/photo/photo-of-women-eating-watermelon-3760053/)

  - [Pexels License](https://www.pexels.com/license/)

### Content/text

- The descriptions for the images are from [Wikipedia](https://en.wikipedia.org/)
  - [Wikipedia Copyrights](https://en.wikipedia.org/wiki/Wikipedia:Copyrights)