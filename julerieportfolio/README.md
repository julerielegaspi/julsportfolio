# Portfolio (React + TypeScript + Vite)

## Run it
```bash
npm install
npm run dev      # development at http://localhost:5173
npm run build    # production build in /dist
```

## Make it yours
- Edit **`src/data.ts`**: your bio, projects, skills, contact links and the words that get typed on the About page (`roles`).

## Add your photo
There are two ways, and you can use either one.

**A) Pick it in the browser (quickest)**
1. Open the **About** page.
2. Click the round photo slot (or drag an image onto it).
3. Your photo appears there and in the sidebar. It is saved in your browser, so it is still there after a refresh.
   Use **Remove photo** to clear it.

**B) Save it with the project (what visitors will see once it is online)**
1. Save your picture as **`public/profile.jpg`**.
2. Refresh. It is picked up automatically.
3. Before you publish, set `photoEditable: false` in `src/data.ts` so visitors don't see the "Change photo" controls.

Different file name? Change `photoPath` in `src/data.ts`.

> Note: a photo chosen with option A lives only in *your* browser. To show it to everyone, use option B.

## Upload your resume later
1. Export your resume as a PDF.
2. Save it as **`public/resume.pdf`** (replace any existing file).
3. Refresh. Clicking **About Me → View Resume** now shows it, with a Download button.

Different file name? Change `resumePath` in `src/data.ts`.
The "Upload a file" button in the resume viewer lets you preview a PDF in the browser
without saving it (handy for testing).

## What's animated
- Page transitions, a scroll-progress bar, drifting background shapes and a soft glow that follows the mouse
- Typing effect, shimmering name, count-up stats and orbiting tech badges around your photo
- Cards that light up and tilt under the mouse, scroll-reveal, and a project filter
- A scrolling skills strip

Visitors who have "reduce motion" turned on in their system settings get the same page without the movement.
