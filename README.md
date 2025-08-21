```bash
cd Desktop
mkdir tailwind-html
cd tailwind-html
touch index.html
```
# Open with live server , not open index.html
### 2nd section is not quite responsive right now

stroke in svg to control color


```html
<!-- Tailwind CDN -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Move Right on Hover -->
<div class="w-24 h-24 bg-blue-500 hover:translate-x-10 transition-transform"></div>

<!-- Move Down on Hover -->
<div class="w-24 h-24 bg-red-500 hover:translate-y-10 transition-transform"></div>

<!-- Bouncing Box (Y axis) -->
<div class="w-24 h-24 bg-green-500 animate-bounce"></div>