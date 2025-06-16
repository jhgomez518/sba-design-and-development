# Frontend Mentor - Testimonials grid section
Link to challenge completed: https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7

Overview of Steps Taken:

- Used Bulma's grid system to create a responsive, 12-column layout that adjusts for different screen sizes
- Used Bulma components, including "cell" and "is-col" classes, utility classes like "has-text-left",
  "has-background-white," as well as helper methods like "p-6." Also made use of the card component for layout reasons.
- Included custom CSS and good-old fashioned vanilla CSS to achieve as-granular a resemblance to the challenge design as possible.
- Challenges faced discussed in my Reflection below.

Reflection:

- Challenges Faced: The single biggest challenge was creating a mimetic layout to the chosen design while sticking with
  Bulma-specific capabilities. I got stuck for a long time because my brain became married to the idea of a grid with
  two columns (one with four testimonials and one with just the one on the far right), sitting side-by-side. I also spent
  a good deal of time trying to create a cell that would span AND act as a container for the right-most testimonial.
- I wrote many html files with various grid ideas, copying+pasting into a new file every time I wanted to experiment a new
  idea without losing my progress thus far. I had an epiphany (really a common sense realization) that I could make use
  of Bulma's full 12-column layout for the ENTIRE grid, and simply span in such a way that would result in a mimetic
  layout to my chosen design. The answer was staring at me, but for some reason I had become married to the idea of
  "two grids side by side."
- As you can see, Kira's testimonial is blatanly divided across both rows, which is not like the challenge design. I understand
  that point will be deducted for this, and that a solution may have been attained had I leaned on CSS Grid
  (and taken this assignment as an opportunity to truly delve into that topic). However, after doing a Bootstrap assignment and
  checking out Bulma, I quickly decided that I much prefer the latter, and I was excited by the prospect of managing to
  create a mimetic layout by restricting myself to Bulma-only capabilities. I exhausted many possibilities, and maybe it IS
  possible to get Kira's testimonial section 100% the same as in the challenge, but I could not see how, and accepted the
  workaround solution I ended up submitting. That said, I was happy with how far I was able to push Bulma to get as close
  to the challenge layout as possible, I think this is as difficult a design as I intend to do using Bulma on my
  personal projects, and I came out of this assigment feeling more comfortable with Bulma, and with an affinity for the
  library that frankly I did not feel for Bootstrap (or Tailwind). If given more time I would use CSS Grid to see if I could
  get the exact layout, but then I would not be using Bulma as extensively as I did, which was a big part of this assignment
  (that is, the ability to leverage CSS Library capabilities).
