# 🌐 Frontend Mentor - Workit Landing Page

<p>This is a solution to the <a href="https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu" target="_blank">[Workit Landing Page on Frontend Mentor]</a>.</p>

# 📸 Screenshot

<table>
  <thead>
    <th>Web Version</th>
    <th>Tablet Version</th>
    <th>Mobile Version</th>
  </thead>
  <tbody>
    <tr>
      <td><img width="550" src="resources/images/web-version.png" /></td>
      <td><img width="550" src="resources/images/tablet-version.png" /></td>
      <td><img width="250" src="resources/images/mobile-version.png" /></td>
    </tr>
  </tbody>
</table>

# 🔗 Links

<ul>
  <li><strong>Solution URL:</strong> github.com/itsadnwn/workit-landing-page</li>
  <li><strong>Live Site URL:</strong> itsadnwn-workit-landing-page.vercel.app/</li>
</ul>

# 📂 Technologies

<p>This project was built with:</p>
<ul>
  <li><strong>HTML:</strong> Markup language for creating the content and structure.</li>
  <li><strong>shapedivider.app</strong>: For creating custom background shapes
  <li><strong>CSS:</strong> For styling both web and mobile versions.</li>
</ul>

# 🖱️ Interaction

<ul>
  <li>Fully responsive interaction experience across both desktop and mobile devices.</li>
  <li>Hover effects on all buttons.</li>
</ul>

# 🗒️ Key Learning Points

<div>
  <h3>⭐ Custom Shape Dividers</h3>
  <ul>
    <li><strong>Tool:</strong> <a href="www.shapedivider.app">shapedivider.app</a> for creating custom background shapes</li>
    <li>Use for creating visually appealing section dividers and background elements</li>
  </ul>
</div>

<div>
  <h3>⭐ SVG Background Implementation</h3>
  <ul>
    <li><strong>Properties:</strong> <code>background-image</code>, <code>background-repeat</code>, <code>background-position</code></li>
    <li>Essential for positioning and controlling SVG elements within hero sections</li>
    <li>Ensures proper scaling and placement across different screen sizes</li>
  </ul>
</div>

<div>
  <h3>⭐ Smooth Button Transitions</h3>
  <ul>
    <li><strong>Best Practice:</strong> Apply <code>transition</code> property to the base element, not the <code>:hover</code> pseudo-class</li>
    <li>Results in smoother animation effects both on hover-in and hover-out</li>
    <li>Prevents jarring animation behavior when cursor leaves the element</li>
  </ul>
</div>

<div>
  <h3>⭐ Preventing Layout Shift on Hover</h3>
  <ul>
    <li><strong>Technique:</strong> Add <code>px solid transparent</code> border to base element when hover state includes visible borders</li>
    <li>Maintains consistent element dimensions during state change</li>
    <li>Eliminates unwanted button movement or layout shifting during interaction</li>
  </ul>
</div>

<div>
  <h3>⭐ Image Color Transition</h3>
  <ul>
    <li><strong>Property:</strong> <code>filter</filter> transition for SVG and image elements</li>
    <li>Enables smooth color changes during hover states</li>
    <li>Provides polished visual feedback for interactive elements</li>
  </ul>
</div>

<div>
  <h3>⭐ Aspect Ratio Control</h3>
  <ul>
    <li><strong>Property:</strong> <code>aspect-ratio</code></li>
    <li>Defines precise width-to-height ratios for elements</li>
    <li>Maintains consistent proportions across different screen sizes</li>
  </ul>
</div>