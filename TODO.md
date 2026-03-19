# TODO: Add Article Image Support

## Steps:
1. Update BLOG-APP-BACKEND/models/ArticleModel.js: Add optional `imageUrl: { type: String }` field to articleSchema before comments.
2. Update blog-app-frontend/src/components/AddArticle.jsx: Add textarea/input for imageUrl, include data.imageUrl in payload.
3. Update blog-app-frontend/src/components/ArticleDetails.jsx: Add <img> tag for article.imageUrl after title section.
4. Restart backend (model change).
5. Test create/view article.

Status: Steps 1-3 complete. Next: Restart backend and test.
