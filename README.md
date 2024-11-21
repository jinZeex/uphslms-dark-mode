<h1>UPHSL LMS Dark Mode</h1>

Heavily based off of [Ateneo de Manila University's Moodle](https://github.com/deionmenor/moodle-night-mode)

<h2>Installing</h2>

- Install [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) first. 
- Head to [userstyles.world](https://userstyles.world/style/18314/uphsl-lms-dark-mode-scrollbar), and hit `Install`.
- Done!

<h2>Tasks</h2>

- [X] Tasks
- [X] Alerts
- [X] Website Theme itself
- [X] Reports, Calendars, Grades
- [X] Messages
- [ ] Quizzes
- [ ] Proper Text Boxes for Task Submissions

<h2>Contributing</h2>

I recommend using [Inspect CSS](https://chromewebstore.google.com/detail/inspect-css/fbopfffegfehobgoommphghohinpkego) for this.

<h3>Color Pallete</h3>

```css
:root {
  --background-color: #1e2227;
  --secondary-bg-color: #252a30; 
  --border-color: #2c3136;
  --text-color: #e0e0e0;
  --link-color: #80d0ff;
  --link-hover-color: #66baff;
  --card-shadow-color: rgba(0, 0, 0, 0.3);
  --alert-color: #ff4d4d;
}
```

<h3>How to use?</h3>
Simple.

```css
background-color: var(--alert-color) /* For alerts */
```
