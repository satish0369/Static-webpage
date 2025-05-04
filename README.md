# Static-webpage
# Business Website - Static Hosting (AWS S3 + CloudFront)

This project is a simple static business website built with HTML and CSS. It showcases services like Web Development, Marketing, and Consulting. The site is hosted on Amazon S3 and distributed via CloudFront for fast global access.

---

## 🌐 Live Demo

[https://your-distribution-id.cloudfront.net](https://your-distribution-id.cloudfront.net)  
> _Replace with your actual CloudFront URL_

---

## 📁 Features

- Responsive Hero Section with background image
- Services section with hover animation
- Contact form (Formspree)
- Admin login page
- Simple navigation
- Clean, modern layout

---

## 🚀 Hosting Setup (AWS)

### 1. Create S3 Bucket
- Enable static website hosting
- Upload `index.html`, `style.css`, and images
- Set bucket policy to allow public read access

### 2. Enable Versioning (Optional)
- For rollback or version tracking

### 3. Configure Bucket Permissions
- Go to **Permissions** tab → **Block Public Access** → Disable all (for website access)
- Add a public-read bucket policy

### 4. Create CloudFront Distribution
- Set S3 bucket as origin
- Enable “Redirect HTTP to HTTPS”
- Copy and save your distribution URL

---

## 🧪 Testing

Test the website in:
- Desktop and mobile browsers
- S3 public URL and CloudFront URL

---

## 🛠 Technologies Used

- HTML5
- CSS3
- AWS S3
- AWS CloudFront
- Formspree (for contact form)

---

## ✍️ Author

**Degavath Satish**  
Email: degavathsatish5@gmail.com  
GitHub: [your-github-link]

---

## 📜 License

This project is open-source and free to use under the MIT License.
