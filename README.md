<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PetTech - Smart Technology for Your Pet</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#2A9D8F',secondary:'#F8F9FA'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Inter', sans-serif;
}
.hero-section {
background-image: url('https://readdy.ai/api/search-image?query=A%20modern%2C%20minimalist%20home%20interior%20with%20soft%20natural%20lighting.%20A%20French%20Bulldog%20sitting%20next%20to%20a%20sleek%2C%20white%20automatic%20pet%20feeder%20on%20a%20clean%20white%20surface.%20The%20background%20is%20slightly%20blurred%20with%20a%20cozy%20living%20room%20environment.%20The%20image%20has%20a%20clean%2C%20Apple-like%20aesthetic%20with%20plenty%20of%20white%20space%20on%20the%20left%20side%20for%20text%20placement.&width=1200&height=600&seq=pet1&orientation=landscape');
background-position: right center;
background-repeat: no-repeat;
background-size: contain;
}
input:focus {
outline: none;
}
#testimonialWrapper {
transition: transform 0.5s ease-in-out;
}
.testimonial {
flex-shrink: 0;
padding: 2rem;
}
</style>
</head>
<body class="bg-white text-gray-900">
<header class="shadow-sm bg-white">
<div class="container mx-auto px-4 py-4 flex justify-between items-center">
<a href="#" class="flex items-center gap-2">
<div class="w-10 h-10 flex items-center justify-center text-white bg-primary rounded-full">
<i class="ri-footprint-line ri-lg"></i>
</div>
<span class="text-2xl font-bold">PetTech</span>
</a>
<nav class="hidden md:flex items-center gap-8">
<a href="#" class="font-medium hover:text-primary transition-colors">About</a>
<a href="#" class="font-medium hover:text-primary transition-colors">Products</a>
<a href="#" class="font-medium hover:text-primary transition-colors">Contact</a>
<a href="#" class="w-10 h-10 flex items-center justify-center">
<i class="ri-shopping-cart-line ri-lg"></i>
</a>
</nav>
<button class="md:hidden w-10 h-10 flex items-center justify-center">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</header>
<main>
<section class="hero-section min-h-[600px] flex items-center relative">
<div class="absolute inset-0 bg-gradient-to-r from-white via-white/80 to-transparent w-[33.33%] pointer-events-none"></div>
<div class="container mx-auto px-4 w-full relative">
<div class="max-w-lg">
<h1 class="text-5xl font-bold mb-4">Smart Technology for Your Pet</h1>
<p class="text-xl mb-8">Discover innovative gadgets to enhance your pet's life</p>
<button class="bg-primary text-white px-8 py-3 font-medium !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Shop Now</button>
</div>
</div>
</section>
<section class="py-16">
<div class="container mx-auto px-4">
<h2 class="text-3xl font-bold mb-12">Featured Products</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow">
<img src="https://readdy.ai/api/search-image?query=A%20modern%2C%20sleek%20white%20automatic%20pet%20feeder%20with%20transparent%20food%20container%20on%20top%20and%20a%20black%20feeding%20bowl%20at%20the%20bottom%2C%20photographed%20against%20a%20clean%20white%20background%20with%20soft%20shadows%2C%20product%20photography%20style&width=400&height=300&seq=feeder1&orientation=landscape" alt="Automatic Pet Feeder" class="w-full h-64 object-cover object-top">
<div class="p-6">
<h3 class="text-xl font-bold mb-2">Automatic Pet Feeder</h3>
<p class="text-gray-600 mb-4">Schedule meals and control portions with our smart feeder</p>
<button class="bg-primary text-white px-6 py-2 font-medium !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Buy Now</button>
</div>
</div>
<div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow">
<img src="https://readdy.ai/api/search-image?query=A%20modern%2C%20sleek%20white%20smart%20pet%20camera%20with%20a%20minimalist%20design%2C%20featuring%20a%20black%20lens%20in%20the%20center%20and%20a%20small%20button%20at%20the%20bottom%2C%20photographed%20against%20a%20clean%20white%20background%20with%20soft%20shadows%2C%20product%20photography%20style&width=400&height=300&seq=camera1&orientation=landscape" alt="Pet Camera" class="w-full h-64 object-cover object-top">
<div class="p-6">
<h3 class="text-xl font-bold mb-2">Pet Camera</h3>
<p class="text-gray-600 mb-4">Monitor your pet remotely with HD video and two-way audio</p>
<button class="bg-primary text-white px-6 py-2 font-medium !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Buy Now</button>
</div>
</div>
<div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow">
<img src="https://readdy.ai/api/search-image?query=A%20happy%20golden%20retriever%20dog%20wearing%20a%20sleek%20white%20GPS%20collar%20tracker%2C%20photographed%20outdoors%20on%20green%20grass%20with%20natural%20lighting%2C%20the%20dog%20is%20smiling%20with%20tongue%20out%2C%20product%20in%20use%20lifestyle%20photography&width=400&height=300&seq=tracker1&orientation=landscape" alt="GPS Pet Tracker" class="w-full h-64 object-cover object-top">
<div class="p-6">
<h3 class="text-xl font-bold mb-2">GPS Pet Tracker</h3>
<p class="text-gray-600 mb-4">Keep track of your pet's location and activity in real-time</p>
<button class="bg-primary text-white px-6 py-2 font-medium !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Buy Now</button>
</div>
</div>
</div>
</div>
</section>
<section class="py-12 bg-secondary">
<div class="container mx-auto px-4">
<div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
<div>
<div class="w-16 h-16 mx-auto flex items-center justify-center text-primary mb-4">
<i class="ri-truck-line ri-2x"></i>
</div>
<h3 class="font-bold mb-1">Free Shipping</h3>
<p class="text-sm text-gray-600">On all orders over $50</p>
</div>
<div>
<div class="w-16 h-16 mx-auto flex items-center justify-center text-primary mb-4">
<i class="ri-customer-service-2-line ri-2x"></i>
</div>
<h3 class="font-bold mb-1">24/7 Support</h3>
<p class="text-sm text-gray-600">Expert assistance anytime</p>
</div>
<div>
<div class="w-16 h-16 mx-auto flex items-center justify-center text-primary mb-4">
<i class="ri-arrow-go-back-line ri-2x"></i>
</div>
<h3 class="font-bold mb-1">Easy Returns</h3>
<p class="text-sm text-gray-600">30-day money back guarantee</p>
</div>
<div>
<div class="w-16 h-16 mx-auto flex items-center justify-center text-primary mb-4">
<i class="ri-secure-payment-line ri-2x"></i>
</div>
<h3 class="font-bold mb-1">Secure Payments</h3>
<p class="text-sm text-gray-600">Safe & encrypted transactions</p>
</div>
</div>
</div>
</section>
<section class="py-16">
<div class="container mx-auto px-4">
<h2 class="text-3xl font-bold mb-4 text-center">What Pet Owners Say</h2>
<p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Loved by 10,000+ pet lovers worldwide</p>
<div class="max-w-4xl mx-auto">
<div id="testimonialSlider" class="relative overflow-hidden">
<div id="testimonialWrapper" class="transition-transform duration-500 ease-in-out">
<div class="testimonial bg-white p-8 rounded-lg shadow-md">
<div class="flex items-center gap-4 mb-6">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white">
<i class="ri-user-line ri-2x"></i>
</div>
<div>
<h3 class="font-bold">Michael Thompson</h3>
<p class="text-sm text-gray-600">Dog Owner</p>
</div>
<div class="ml-auto flex">
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
</div>
</div>
<p class="text-gray-700">"The automatic feeder has been a game-changer for my busy schedule. My Labrador gets fed on time, every time, and I can monitor everything from my phone. The build quality is exceptional and setup was incredibly simple."</p>
</div>
<div class="testimonial bg-white p-8 rounded-lg shadow-md">
<div class="flex items-center gap-4 mb-6">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white">
<i class="ri-user-line ri-2x"></i>
</div>
<div>
<h3 class="font-bold">Sarah Anderson</h3>
<p class="text-sm text-gray-600">Cat Owner</p>
</div>
<div class="ml-auto flex">
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
</div>
</div>
<p class="text-gray-700">"The pet camera gives me peace of mind when I'm at work. I love being able to check on my cats and even talk to them through the app. The video quality is crystal clear and the night vision works perfectly."</p>
</div>
<div class="testimonial bg-white p-8 rounded-lg shadow-md">
<div class="flex items-center gap-4 mb-6">
<div class="w-16 h-16 bg-primary rounded-full flex items-center justify-center text-white">
<i class="ri-user-line ri-2x"></i>
</div>
<div>
<h3 class="font-bold">David Martinez</h3>
<p class="text-sm text-gray-600">Dog & Cat Owner</p>
</div>
<div class="ml-auto flex">
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
<i class="ri-star-fill text-yellow-400"></i>
</div>
</div>
<p class="text-gray-700">"The GPS tracker has saved me from panic multiple times when my adventurous dog decided to explore the neighborhood. The real-time tracking is accurate and the battery life is impressive. Worth every penny!"</p>
</div>
</div>
<div id="testimonialDots" class="flex justify-center mt-8 gap-2">
<button class="w-3 h-3 rounded-full bg-primary" data-index="0"></button>
<button class="w-3 h-3 rounded-full bg-gray-300" data-index="1"></button>
<button class="w-3 h-3 rounded-full bg-gray-300" data-index="2"></button>
</div>
</div>
</div>
</div>
</section>
<section class="py-16 bg-secondary">
<div class="container mx-auto px-4 text-center">
<h2 class="text-3xl font-bold mb-4">Smart Technology for Happy Pets</h2>
<p class="max-w-2xl mx-auto text-gray-700 mb-8">Discover innovative and reliable pet gadgets to improve your furry friend's daily life. Our products are designed with your pet's comfort and your convenience in mind.</p>
<div class="flex flex-wrap justify-center gap-4">
<div class="bg-white px-6 py-2 rounded-full shadow-sm flex items-center gap-2">
<i class="ri-shield-check-line text-primary"></i>
<span class="font-medium">Safe for pets</span>
</div>
<div class="bg-white px-6 py-2 rounded-full shadow-sm flex items-center gap-2">
<i class="ri-cpu-line text-primary"></i>
<span class="font-medium">Smart & intuitive tech</span>
</div>
<div class="bg-white px-6 py-2 rounded-full shadow-sm flex items-center gap-2">
<i class="ri-heart-line text-primary"></i>
<span class="font-medium">Vet approved</span>
</div>
</div>
</div>
</section>
<section class="py-16">
<div class="container mx-auto px-4">
<div class="max-w-4xl mx-auto bg-white rounded-lg shadow-md overflow-hidden">
<div class="md:flex">
<div class="md:w-1/2 p-8 flex flex-col justify-center">
<h2 class="text-3xl font-bold mb-4">Join Our Newsletter</h2>
<p class="text-gray-600 mb-6">Stay updated with our latest products and exclusive offers for your pet.</p>
<div class="flex">
<input type="email" placeholder="Your email address" class="border border-gray-300 rounded-l-button px-4 py-3 w-full border-r-0">
<button class="bg-primary text-white px-6 py-3 font-medium !rounded-r-button !rounded-l-none whitespace-nowrap hover:bg-opacity-90 transition-colors">Subscribe</button>
</div>
</div>
<div class="md:w-1/2 bg-cover bg-center" style="background-image: url('https://readdy.ai/api/search-image?query=A%20happy%20cat%20and%20dog%20sitting%20together%20looking%20at%20a%20smartphone%20or%20tablet%20showing%20a%20pet%20app%20interface%2C%20in%20a%20modern%20living%20room%20with%20soft%20natural%20lighting%2C%20the%20pets%20appear%20engaged%20and%20curious%2C%20lifestyle%20product%20photography&width=500&height=400&seq=newsletter1&orientation=portrait')"></div>
</div>
</div>
</div>
</section>
</main>
<footer class="bg-gray-900 text-white py-12">
<div class="container mx-auto px-4">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8">
<div>
<a href="#" class="flex items-center gap-2 mb-4">
<div class="w-10 h-10 flex items-center justify-center text-white bg-primary rounded-full">
<i class="ri-footprint-line ri-lg"></i>
</div>
<span class="text-2xl font-bold">PetTech</span>
</a>
<p class="text-gray-400">Innovative technology solutions for the modern pet owner.</p>
</div>
<div>
<h3 class="font-bold text-lg mb-4">Quick Links</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">About Us</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Products</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Contact</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">FAQ</a></li>
</ul>
</div>
<div>
<h3 class="font-bold text-lg mb-4">Legal</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Privacy Policy</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Terms of Service</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Return Policy</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Shipping Info</a></li>
</ul>
</div>
<div>
<h3 class="font-bold text-lg mb-4">Connect With Us</h3>
<div class="flex gap-4 mb-4">
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-instagram-line"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-facebook-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-twitter-x-line"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-youtube-line"></i>
</a>
</div>
<div class="flex items-center gap-2">
<i class="ri-secure-payment-line text-gray-400"></i>
<span class="text-gray-400">Secure Payment:</span>
</div>
<div class="flex gap-2 mt-2">
<i class="ri-visa-line text-2xl text-gray-400"></i>
<i class="ri-mastercard-line text-2xl text-gray-400"></i>
<i class="ri-paypal-line text-2xl text-gray-400"></i>
<i class="ri-apple-fill text-2xl text-gray-400"></i>
</div>
</div>
</div>
<div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-500">
<p>&copy; 2025 PetTech. All rights reserved.</p>
</div>
</div>
</footer>
<script id="mobileMenu">
document.addEventListener('DOMContentLoaded', function() {
const menuButton = document.querySelector('.ri-menu-line').parentElement;
const nav = document.querySelector('nav');
menuButton.addEventListener('click', function() {
if (nav.classList.contains('hidden')) {
nav.classList.remove('hidden');
nav.classList.add('flex', 'flex-col', 'absolute', 'top-16', 'right-0', 'bg-white', 'shadow-md', 'p-4', 'w-48', 'z-50');
} else {
nav.classList.add('hidden');
nav.classList.remove('flex', 'flex-col', 'absolute', 'top-16', 'right-0', 'bg-white', 'shadow-md', 'p-4', 'w-48', 'z-50');
}
});
});
</script>
<script id="testimonialSlider">
document.addEventListener('DOMContentLoaded', function() {
const wrapper = document.getElementById('testimonialWrapper');
const dots = document.getElementById('testimonialDots').getElementsByTagName('button');
let currentSlide = 0;
function updateSlider(index) {
wrapper.style.transform = `translateX(-${index * 100}%)`;
Array.from(dots).forEach((dot, i) => {
dot.classList.remove('bg-primary');
dot.classList.add('bg-gray-300');
if (i === index) {
dot.classList.remove('bg-gray-300');
dot.classList.add('bg-primary');
}
});
currentSlide = index;
}
Array.from(dots).forEach((dot, index) => {
dot.addEventListener('click', () => {
updateSlider(index);
});
});
const testimonials = wrapper.getElementsByClassName('testimonial');
wrapper.style.width = `${testimonials.length * 100}%`;
wrapper.style.display = 'flex';
Array.from(testimonials).forEach(testimonial => {
testimonial.style.width = `${100 / testimonials.length}%`;
});
});
</script>
</body>
</html>
