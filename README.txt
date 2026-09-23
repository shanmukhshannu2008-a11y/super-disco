CS180 PORTFOLIO — SETUP

1. Open index.html in your browser to preview the site. No installation or build is required.

2. In index.html, replace [Your name], the major placeholder, and the two About Me paragraph placeholders. Write your own introduction; include all eight required items from your lab. Add more <p>...</p> paragraphs if needed. Do not put private information in HTML comments; comments are public too.

3. Put your photo in assets and name it my-photo.jpg (use a real JPEG, or change the filename/extension in the HTML to match your image). In index.html replace the entire <div class="photo-placeholder">...</div> with:
<img class="portrait" src="assets/my-photo.jpg" alt="Portrait of YOUR NAME">
Replace YOUR NAME with your preferred name. The photo is cropped to fit; adjust object-position in .portrait if needed.

4. In ai-use.html complete all six fields accurately. Replace the transcript placeholder with a real link, for example:
<a href="YOUR_CONVERSATION_LINK">Full collaboration transcript</a>
Or upload a transcript.txt alongside index.html and link to it. Remove the draft badge/template note when complete. For another entry, copy the entire <article class="log-entry">...</article> block and put the newer entry above it.

5. Unzip the download first. Open your existing GitHub repository, choose Add file > Upload files, and upload the CONTENTS of this folder, including assets when you add your image. index.html must be at the repository root, not inside a cs180-portfolio folder. Commit the changes. Do not upload the ZIP itself as your website.

6. In repository Settings > Pages choose Deploy from a branch, main, / (root), and Save. If already configured, uploading the files triggers another deployment. Wait for the deployment to finish, then use the Visit site link.

7. Check the live site in an incognito window and on your phone. Click every navigation link and each Back to About Me link. Verify the photo, your writing, and the complete collaboration log. The initial files contain placeholders and are not a completed submission.

robots.txt contains the lab-required text. Each HTML page also includes noindex, nofollow. These are requests to crawlers, not an access restriction or guarantee against indexing. Keep your link out of public class spaces as instructed.

FILES
index.html — About Me home
outcome1.html through outcome5.html — learning outcomes
ai-use.html — collaboration logs
styles.css — all shared styling
robots.txt — lab-required crawler instructions
assets/ — put your photo here
