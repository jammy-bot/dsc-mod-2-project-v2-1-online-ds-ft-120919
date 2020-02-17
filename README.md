<!DOCTYPE html>
<html data-markdown-preview-plus-context="html-export">
  <head>
    <meta charset="utf-8" />
    <title>README</title>
    <style>.emoji {
  max-width: 1em !important;
}
del {
  text-decoration: none;
  position: relative;
}
del::after {
  border-bottom: 1px solid black;
  content: '';
  left: 0;
  position: absolute;
  right: 0;
  top: 50%;
}
ul.contains-task-list li.task-list-item {
  position: relative;
  list-style-type: none;
}
ul.contains-task-list li.task-list-item input.task-list-item-checkbox {
  position: absolute;
  transform: translateX(-100%);
  width: 26px;
}
span.critic.comment {
  position: relative;
}
span.critic.comment::before {
  content: '\1f4ac';
  position: initial;
}
span.critic.comment > span {
  display: none;
}
span.critic.comment:hover > span {
  display: initial;
  position: absolute;
  top: 100%;
  left: 0;
  border: 1px solid;
  border-radius: 5px;
  max-height: 4em;
  overflow: auto;
}
span.critic.comment:focus > span {
  display: initial;
  text-decoration: underline;
  position: initial;
  top: auto;
  left: auto;
  border: initial;
  border-radius: initial;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
  background-color: transparent;
}

body {
  padding: 2em;
  font-size: 1.2em;
  color: #2b2c27;
  background-color: #eddab9;
  overflow: auto;
}
body > :first-child,
body > div.update-preview > :first-child {
  margin-top: 0;
}
body > p,
body > div.update-preview > p {
  margin-top: 0;
  margin-bottom: 1.5em;
}
body > ul,
body > div.update-preview > ul,
body > ol,
body > div.update-preview > ol {
  margin-bottom: 1.5em;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  line-height: 1.2;
  margin-top: 1.5em;
  margin-bottom: 0.5em;
  color: #000000;
}
h1 {
  font-size: 2.4em;
  font-weight: 300;
}
h2 {
  font-size: 1.8em;
  font-weight: 400;
}
h3 {
  font-size: 1.5em;
  font-weight: 500;
}
h4 {
  font-size: 1.2em;
  font-weight: 600;
}
h5 {
  font-size: 1.1em;
  font-weight: 600;
}
h6 {
  font-size: 1em;
  font-weight: 600;
}
strong {
  color: #000000;
}
del {
  color: #55574d;
}
a,
a code {
  color: #15b5d2;
}
img {
  max-width: 100%;
}
blockquote {
  margin: 1.5em 0;
  font-size: inherit;
  color: #55574d;
  border-color: #dcb878;
  border-width: 4px;
}
hr {
  margin: 3em 0;
  border-top: 2px dashed #dcb878;
  background: none;
}
table {
  margin: 1.5em 0;
}
th {
  color: #000000;
}
th,
td {
  padding: 0.66em 1em;
  border: 1px solid #dcb878;
}
code {
  color: #000000;
  background-color: #e7cda1;
}
pre.editor-colors {
  margin: 1.5em 0;
  padding: 1em;
  font-size: 0.92em;
  border-radius: 3px;
  background-color: #e9d1a9;
}
kbd {
  color: #000000;
  border: 1px solid #dcb878;
  border-bottom: 2px solid #d6ab60;
  background-color: #e7cda1;
}

.bracket-matcher .region {
  border-bottom: 1px dotted lime;
  position: absolute;
}
.line-number.bracket-matcher.bracket-matcher {
  color: #2b2c27;
  background-color: #13a1bb;
}

.spell-check-misspelling .region {
  border-bottom: 2px dotted rgba(255, 51, 51, 0.75);
}
.spell-check-corrections {
  width: 25em !important;
}

pre.editor-colors {
  background-color: #eddab9;
  color: #2b2c27;
}
pre.editor-colors .wrap-guide {
  background-color: #8b8a88;
}
pre.editor-colors .indent-guide {
  color: #8b8a88;
}
pre.editor-colors .invisible-character {
  color: #8b8a88;
}
pre.editor-colors .gutter {
  background-color: #eddab9;
  color: #2b2c27;
}
pre.editor-colors .gutter .line-number.cursor-line {
  background-color: #13a1bb;
  color: #2b2c27;
}
pre.editor-colors .gutter .line-number.cursor-line-no-selection {
  color: #2b2c27;
}
pre.editor-colors .gutter .line-number.folded,
pre.editor-colors .gutter .line-number:after,
pre.editor-colors .fold-marker:after {
  color: #8b8a88;
}
pre.editor-colors .invisible {
  color: #2b2c27;
}
pre.editor-colors .cursor {
  color: #15b5d2;
}
pre.editor-colors .selection .region {
  background-color: #e7cda1;
}
.syntax--comment {
  color: #8b8a88;
}
.syntax--keyword {
  color: #b53244;
}
.syntax--keyword.syntax--control {
  color: #b53244;
}
.syntax--keyword.syntax--operator {
  color: #2b2c27;
}
.syntax--keyword.syntax--other.syntax--special-method {
  color: #b53244;
}
.syntax--keyword.syntax--other.syntax--unit {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--storage {
  color: #b53244;
  font-weight: bold;
}
.syntax--constant {
  color: #b53244;
}
.syntax--constant.syntax--character.syntax--escape {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--constant.syntax--numeric {
  color: #b53244;
  font-weight: bold;
}
.syntax--constant.syntax--other.syntax--color {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--constant.syntax--other.syntax--symbol {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--variable {
  color: #b53244;
  font-weight: bold;
}
.syntax--variable.syntax--interpolation {
  color: #8d2735;
}
.syntax--variable.syntax--parameter.syntax--function {
  color: #2b2c27;
}
.syntax--invalid.syntax--illegal {
  background-color: #b53244;
  color: #eddab9;
}
.syntax--string {
  color: #b53244;
}
.syntax--string.syntax--regexp {
  color: #b53244;
  font-weight: bold;
}
.syntax--string.syntax--regexp .syntax--source.syntax--ruby.syntax--embedded {
  color: #b53244;
  font-weight: bold;
}
.syntax--string.syntax--other.syntax--link {
  color: #b53244;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--comment {
  color: #8b8a88;
}
.syntax--punctuation.syntax--definition.syntax--string,
.syntax--punctuation.syntax--definition.syntax--variable,
.syntax--punctuation.syntax--definition.syntax--parameters,
.syntax--punctuation.syntax--definition.syntax--array {
  color: #2b2c27;
}
.syntax--punctuation.syntax--definition.syntax--heading,
.syntax--punctuation.syntax--definition.syntax--identity {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--bold {
  color: #b53244;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--italic {
  color: #b53244;
  font-style: italic;
}
.syntax--punctuation.syntax--section.syntax--embedded {
  color: #8d2735;
}
.syntax--support.syntax--class {
  color: #b53244;
  font-weight: bold;
}
.syntax--support.syntax--function {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--support.syntax--function.syntax--any-method {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--entity.syntax--name.syntax--function {
  color: #2b2c27;
  font-weight: bold;
}
.syntax--entity.syntax--name.syntax--type {
  color: #b53244;
  text-decoration: underline;
}
.syntax--entity.syntax--other.syntax--inherited-class {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--entity.syntax--name.syntax--class,
.syntax--entity.syntax--name.syntax--type.syntax--class {
  color: #b53244;
  font-weight: bold;
}
.syntax--entity.syntax--name.syntax--section {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--entity.syntax--name.syntax--tag {
  color: #b53244;
  text-decoration: underline;
}
.syntax--entity.syntax--other.syntax--attribute-name {
  color: #2b2c27;
}
.syntax--entity.syntax--other.syntax--attribute-name.syntax--id {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--meta.syntax--class {
  color: #b53244;
  font-weight: bold;
}
.syntax--meta.syntax--link {
  color: #b53244;
}
.syntax--meta.syntax--require {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--meta.syntax--selector {
  color: #b53244;
  font-weight: bold;
}
.syntax--meta.syntax--separator {
  background-color: #eddab9;
  color: #2b2c27;
}
.syntax--none {
  color: #2b2c27;
}
.syntax--markup.syntax--bold {
  color: #b53244;
  font-weight: bold;
}
.syntax--markup.syntax--changed {
  color: #b53244;
}
.syntax--markup.syntax--deleted {
  color: #b53244;
}
.syntax--markup.syntax--italic {
  color: #b53244;
  font-style: italic;
}
.syntax--markup.syntax--heading .syntax--punctuation.syntax--definition.syntax--heading {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--markup.syntax--inserted {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--markup.syntax--list {
  color: #b53244;
  font-weight: bold;
}
.syntax--markup.syntax--quote {
  color: #b53244;
}
.syntax--markup.syntax--raw.syntax--inline {
  color: #15b5d2;
  font-weight: bold;
}
.syntax--source.syntax--gfm .syntax--markup {
  -webkit-font-smoothing: auto;
}
.syntax--source.syntax--gfm .syntax--markup.syntax--heading {
  color: #15b5d2;
  font-weight: bold;
}
pre.editor-colors[mini] .scroll-view {
  padding-left: 1px;
}

/*
 * Your Stylesheet
 *
 * This stylesheet is loaded when Atom starts up and is reloaded automatically
 * when it is changed and saved.
 *
 * Add your own CSS or Less to fully customize Atom.
 * If you are unfamiliar with Less, you can read more about it here:
 * http://lesscss.org
 */
/*
 * Examples
 * (To see them, uncomment and save)
 */
.script-view .line {
  font-size: 14px;
  margin: 2.5px;
}
.scrollbars-visible-always /deep/ ::-webkit-scrollbar {
  width: 20px;
  height: 20px;
}
.scrollbars-visible-always /deep/ ::-webkit-scrollbar-track {
  border: 0px;
  border-radius: 0px;
  background-color: #444 !important;
}
.scrollbars-visible-always /deep/ ::-webkit-scrollbar-thumb {
  background-color: rgba(255, 200, 200, 0.35) !important;
  border: 0px;
  border-radius: 9px;
}
</style>

  </head>
  <body>
    <h1>Module 1 Final Project</h1>
<p><img src="..\..\gen Reference\images\thebossbaby-happy-baby.gif" alt="Happy Clap GIF By The Boss Baby"></p>
<h2>Introduction</h2>
<p>This project focuses on building a multiple linear regression model capable of predicting home prices.</p>
<h2>Objectives</h2>
<p>Through this project, I explore the following questions and why:</p>
<ul>
<li>Which variables show the strongest correlations with price?</li>
<li>Which variables (whether redundant or un - influential) can or should be eliminated toward building a predictive model for predicting home price?</li>
<li>Does model effectiveness vary across zip codes?</li>
</ul>
<h1>The Dataset</h1>
<p>King County housing data was provided for this project as a single, comma - separated flat file. The file includes housing records for greater than 20,000 properties. Also provided was the following column names and data description for the data set:</p>
<ul>
<li>id - unique identified for a house</li>
<li>date - house was sold</li>
<li>price - is prediction target</li>
<li>bedrooms - Number of Bedrooms/House</li>
<li>bathrooms - Number of bathrooms/bedrooms</li>
<li>sqft_living - square footage of the home</li>
</ul>
<details>
  <summary>Click to view more!</summary>
<ul>
<li>sqft_lot - square footage of the lot</li>
<li>floors - floors (levels) in house</li>
<li>waterfront - House which has a view to a waterfront</li>
<li>view - Has been viewed</li>
<li>condition - How good the condition is ( Overall )</li>
<li>grade - overall grade given to the housing unit, based on King County grading system</li>
<li>sqft_above - square footage of house apart from basement</li>
<li>sqft_basement - square footage of the basement</li>
<li>yr_built - Built Year</li>
<li>yr_renovated - Year when house was renovated</li>
<li>zipcode - zip</li>
<li>lat - Latitude coordinate</li>
<li>long - Longitude coordinate</li>
<li>sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors</li>
<li>sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors</li>
</ul>
</details>
<h1>Featured Notebooks/Analysis</h1>
<ul>
<li>
<p><a href="/blob/master/student.ipynb"><code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">student</code>: <strong>Jupyter Notebook</strong></a>: containing code written for this project and comments explaining it.</p>
</li>
<li>
<p><a href="/blob/master/1-obtain-and-scrub.ipynb"><code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">cleaning-notebook</code></a>: [notebook segment] Import and Clean Data</p>
</li>
<li>
<p><a href="/blob/master/2-eda-and-transform.ipynb"><code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">exploratory notebook</code></a>: [notebook segment] Explore, visualize, and Analyze</p>
</li>
<li>
<p><a href="/blob/master/3-model-and-conclude.ipynb"><code style="font-family: Menlo, Consolas, &quot;DejaVu Sans Mono&quot;, monospace;">modeling-notebook</code></a>: [notebook segment] Build, Train, and Test Regression models</p>
</li>
</ul>
<h4>Visualizations &amp; EDA</h4>
<ul>
<li>visualizations, with corresponding interpretations are included within the the relevant notebook(s).</li>
</ul>
<h3>Non-Technical Presentation</h3>
<ul>
<li><a href="../blob/master/presentation.pdf">presentation.pdf</a> summarizing  methodology and findings</li>
</ul>
<h1>Technologies</h1>
<p>framework: jupyter notebook
languages: python
libraries: pandas, numpy, scipy, statsmodels, sci-kit learn, pickle
plot Libraries: seaborn, matplotlib</p>

  </body>
</html>
