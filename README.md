# Which version of me do you meet?

A personal, branching hypertext narrative based on the supplied Figma design. Visitors choose Builder, Student, or Dreamer, follow individual thoughts, and decide whether to keep moving or pause.

## Open locally

Open `index.html` in a web browser. Keep all files and the `assets` folder together. No installation, JavaScript, or build step is needed.

## Publish to GitHub Pages

1. Create a public repository called `hypertext-narrative` on GitHub.
2. Extract the ZIP. Upload the CONTENTS of the `hypertext-narrative` folder to the repository root. Do not upload only the ZIP or nest the website inside another folder. `index.html`, `style.css`, and `assets/` should appear at the top level.
3. Commit the files to `main`.
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch, then `main` and `/ (root)`. Save.
6. Wait for deployment, then copy the actual live URL shown in Pages settings. Visit it and try all three paths.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Submit

Use your actual username and deployment URL, not these placeholders:

Live Project Link: https://YOUR-USERNAME.github.io/hypertext-narrative/
GitHub Repository Link: https://github.com/YOUR-USERNAME/hypertext-narrative

Submit both links in the assignment Text Entry box. Also post the live project link in the Week 6 discussion. This download is not itself a live GitHub Pages submission.

## Pages and routes

- index.html: choose Builder, Student, or Dreamer.
- builder.html: choose Fix it, Improve it, Try again, What if, or Pressure.
- student.html: follow deadline and learning fragments, or continue to Pressure.
- dreamer.html: follow an idea, goal, version, or Pressure.
- pressure.html: revisit a thought, pause, or keep moving.
- future.html: return to the beginning or see the quieter side.
- pause.html: begin again or continue at a different pace.
- fix-it.html: investigate a problem, try again, or pause.
- improve-it.html: choose another change or accept the current version.
- try-again.html: return to learning, explore another possibility, or pause.
- what-if.html: return to dreaming, build an idea, or move forward.

There are 11 separate HTML pages. All story navigation uses real `<a href="...">` links. Paths are relative so they work locally and beneath a GitHub project URL.

## Design and content

The seven original pages preserve the text, black background, pale-blue identity cards, gray thought fragments, and handwritten/monospace contrast shown in the Figma screenshots. Four new passages develop the existing thought fragments to meet the minimum page count. Review those new first-person passages before submitting so they reflect your own experience. Some return links were added for clearer navigation.

Icons are local SVG assets. If the local handwriting font cannot load, the site uses a system cursive fallback. The layout adapts to small screens. Keyboard focus is visible, and the site needs no external network requests to function.
