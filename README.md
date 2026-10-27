# Vercel Classroom Example: Small Site Screener

This is a deliberately small, static prototype for teaching deployment with Vercel.

## Classroom workflow

1. Create a GitHub repository named `vercel-classroom-parcel-screener`.
2. Upload `index.html`.
3. In Vercel, choose **Add New Project**, import the GitHub repository, and deploy.
4. Open the resulting `.vercel.app` URL.
5. Change one score or weighting in `index.html`, commit the change, and observe the new deployment.

## Student questions

- Which zone ranks first under each scenario?
- Which weights drive the ranking most strongly?
- What data would be needed to replace the fictional values?
- What should be a hard filter rather than a weighted score?
- Where could an AI feature add value, and where should deterministic rules remain in control?

## Optional next step

Students can add a Vercel server-side function that receives the selected site and returns an AI-generated explanation. The AI key should be stored as a Vercel environment variable, never in `index.html` or GitHub.
