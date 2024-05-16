# HelloDX Blog

Welcome to the HelloDX Blog repository! This blog is built with Jekyll and hosted on Netlify. Follow the instructions below to set up and run the blog locally, create new blog posts, and understand the deployment process.

## Setup and Run Locally

1. **Clone the Repository**

   ```sh
   git clone https://github.com/your-username/hellodx-blog.git
   cd hellodx-blog

   ```

2. **Install Jekyll and Bundler**

  ```sh
       gem install bundler jekyll
  ```

3. **Install Dependencies**

   ```sh
   bundle install
   ```

4. **Run Jekyll Locally**

   ```sh
   bundle exec jekyll build
   bundle exec jekyll serve
   ```

   Your local site will be running at <http://localhost:4000>.

## Creating a Blog Post

Blog posts are written in Markdown and stored in the _posts collection.

1. **Navigate to the `_posts` Directory**

   ```sh
   cd _posts
   ```

2. **Create a New Markdown File**

   ```sh
   touch 2024-05-16-new-blog-post.md
   ```

3. **Write Your Blog Post**

   ```sh
   ---
   layout: post
   title: "Hello World - Hello DX"
   date: 2024-05-15
   authors: ["Kunal Batra"]
   categories: ["DX", "AI"]
   description: "We're launching Hello DX to help Devtool companies grow with a refined developer experience."
   thumbnail: "/assets/images/gen/blog/amitkunal.JPG"
   image: "/assets/images/gen/blog/amitkunal.JPG"
   comments: true
  
   meta_title: Improving page speed with Jekyll
   meta_description: Learn how to improve your Jekyll page speed with these practical tips for your blog.
   meta_image: "/assets/images/og/og-twitter-blog-image.webp"
   ---
   Your blog post content goes here...
   ```

4. **Check Sample Blog Posts**
   For examples of how to structure your blog posts, check out the sample blog posts in the `sample_pages` folder at the root of the repository.

## Deployment

1. **Create a New Branch**

   ```sh
   git checkout -b your-branch-name
   ```

2. **Make Your Changes and Commit**

   ```sh
   git add .
   git commit -m "Your commit message"

   ```

3. **Push Your Branch and Create a PR**

   ```sh
   git push origin your-branch-name
   ```

4. **Open a PR on GitHub**
   Go to your repository on GitHub, open a PR from your branch to the main branch, and wait for the review and merge. Once merged, Netlify will automatically build and deploy your changes.

## Contributing

We welcome contributions! Please fork the repository, create a new branch, and submit a pull request with your changes.
  
