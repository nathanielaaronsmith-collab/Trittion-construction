<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trittion Construction | Montgomery, TX</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "HomeAndConstructionBusiness",
        "name": "Trittion Construction",
        "image": "https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80",
        "url": "#",
        "telephone": "(936) 443-0831",
        "email": "dioniciogarcia242@gmail.com",
        "address": {
            "@type": "PostalAddress",
            "streetAddress": "16869 west Forrestal",
            "addressLocality": "Montgomery",
            "addressRegion": "TX",
            "postalCode": "77316",
            "addressCountry": "US"
        },
        "priceRange": "$",
        "openingHours": "Mo-Fr 08:00-17:00",
        "description": "Trittion Construction offers flooring, concrete, dirt work, fencing, landscaping, and remodeling in Montgomery, Conroe, Spring area. Quality craftsmanship, fair pricing, free estimates.",
        "founder": {
            "@type": "Person",
            "name": "Dionicio Garcia"
        },
        "numberOfEmployees": "1",
        "areaServed": ["Montgomery, TX", "Conroe, TX", "Spring, TX"],
        "review": {
            "@type": "Review",
            "reviewRating": {
                "@type": "Rating",
                "ratingValue": "5",
                "bestRating": "5"
            },
            "author": {
                "@type": "Person",
                "name": "Customer"
            }
        },
        "sameAs": [
            "https://instagram.com/trittion_construction",
            "https://facebook.com/trittion_construction",
            "https://linktr.ee/trittion_construction"
        ]
    }
    </script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        }

        body {
            background: #f4f7fb;
            color: #1e293b;
            line-height: 1.6;
        }

        /* Floating CTA */
        .floating-cta {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #eab308;
            color: #1e293b;
            padding: 16px 28px;
            border-radius: 60px;
            font-weight: 700;
            text-decoration: none;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            z-index: 999;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .floating-cta:hover {
            background: #1e293b;
            color: #eab308;
            border-color: #eab308;
            transform: scale(1.05);
        }

        .floating-cta i {
            font-size: 1.3rem;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80') center/cover fixed;
            min-height: 80vh;
            display: flex;
            align-items: center;
            color: white;
            padding: 0 5%;
            position: relative;
        }

        .hero-content {
            max-width: 800px;
        }

        .hero h1 {
            font-size: clamp(2.5rem, 8vw, 5rem);
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 20px;
        }

        .hero h1 span {
            color: #eab308;
            display: block;
            font-size: 0.6em;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 20px;
        }

        .hero-meta {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }

        .hero-meta-item {
            display: flex;
            align-items: center;
            gap: 10px;
            background: rgba(255,255,255,0.1);
            padding: 10px 20px;
            border-radius: 40px;
            backdrop-filter: blur(5px);
        }

        .hero-meta-item i {
            color: #eab308;
        }

        .hero-buttons {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 16px 36px;
            border-radius: 50px;
            font-weight: 600;
            text-decoration: none;
            transition: 0.3s;
            display: inline-block;
            border: 2px solid transparent;
        }

        .btn-primary {
            background: #eab308;
            color: #1e293b;
        }

        .btn-primary:hover {
            background: transparent;
            border-color: #eab308;
            color: #eab308;
        }

        .btn-outline {
            border: 2px solid white;
            color: white;
        }

        .btn-outline:hover {
            background: white;
            color: #1e293b;
        }

        /* Business Info Bar */
        .info-bar {
            background: white;
            padding: 25px 5%;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .info-item {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .info-icon {
            width: 50px;
            height: 50px;
            background: #f1f5f9;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #eab308;
            font-size: 1.4rem;
        }

        .info-text h4 {
            font-weight: 600;
            color: #1e293b;
        }

        .info-text p {
            color: #64748b;
        }

        .info-text a {
            color: #1e293b;
            text-decoration: none;
            font-weight: 500;
        }

        .info-text a:hover {
            color: #eab308;
        }

        /* Stats Bar (Social Proof) */
        .stats-bar {
            display: flex;
            justify-content: space-around;
            background: #1e293b;
            color: white;
            padding: 30px 5%;
            flex-wrap: wrap;
            gap: 30px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 800;
            color: #eab308;
        }

        .stat-label {
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #cbd5e1;
        }

        /* Services Section */
        .services {
            padding: 80px 5%;
            background: white;
        }

        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-header h2 {
            font-size: 2.5rem;
            color: #1e293b;
            position: relative;
            display: inline-block;
            padding-bottom: 15px;
        }

        .section-header h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: #eab308;
            border-radius: 2px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .service-card {
            background: #f8fafc;
            border-radius: 20px;
            padding: 35px 20px;
            text-align: center;
            transition: 0.3s;
            border: 1px solid #e2e8f0;
        }

        .service-card:hover {
            transform: translateY(-10px);
            border-color: #eab308;
            box-shadow: 0 20px 25px -5px rgba(0,0,0,0.1);
        }

        .service-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #eab308;
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        /* Instagram Feed */
        .instagram-feed {
            background: #f8fafc;
            padding: 80px 5%;
        }

        .feed-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            max-width: 1200px;
            margin: 40px auto 0;
        }

        .feed-post {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .feed-post:hover {
            transform: scale(1.02);
        }

        .post-image {
            height: 200px;
            background-size: cover;
            background-position: center;
            position: relative;
        }

        .post-date {
            position: absolute;
            top: 15px;
            left: 15px;
            background: #eab308;
            color: #1e293b;
            padding: 5px 12px;
            border-radius: 30px;
            font-weight: 600;
            font-size: 0.8rem;
        }

        .post-caption {
            padding: 20px;
        }

        .post-caption p {
            color: #475569;
            margin-bottom: 10px;
        }

        .post-likes {
            display: flex;
            align-items: center;
            gap: 8px;
            color: #eab308;
            font-weight: 600;
        }

        /* Meet the Owner */
        .owner {
            background: white;
            padding: 80px 5%;
        }

        .owner-card {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            align-items: center;
            max-width: 1000px;
            margin: 0 auto;
            background: linear-gradient(135deg, #f1f5f9, #ffffff);
            border-radius: 40px;
            padding: 40px;
            box-shadow: 0 20px 25px -5px rgba(0,0,0,0.1);
        }

        .owner-avatar {
            width: 180px;
            height: 180px;
            background: #eab308;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: white;
            border: 5px solid white;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .owner-info h3 {
            font-size: 2rem;
            color: #1e293b;
        }

        .owner-info p {
            margin: 15px 0;
            color: #475569;
        }

        .owner-contact {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .owner-contact a {
            background: #1e293b;
            color: white;
            padding: 12px 25px;
            border-radius: 40px;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            transition: 0.3s;
        }

        .owner-contact a:hover {
            background: #eab308;
            color: #1e293b;
        }

        /* Contact + Map */
        .contact-map {
            padding: 80px 5%;
            background: #f8fafc;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .contact-form {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
        }

        .contact-form h3 {
            font-size: 1.8rem;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 15px;
            border: 1px solid #cbd5e1;
            border-radius: 10px;
            font-size: 1rem;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #eab308;
            box-shadow: 0 0 0 3px rgba(234,179,8,0.2);
        }

        .form-btn {
            background: #eab308;
            color: #1e293b;
            border: none;
            padding: 16px 30px;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.1rem;
            cursor: pointer;
            transition: 0.3s;
            width: 100%;
        }

        .form-btn:hover {
            background: #1e293b;
            color: #eab308;
        }

        .map-container {
            border-radius: 20px;
            overflow: hidden;
            height: 100%;
            min-height: 400px;
            box-shadow: 0 20px 25px -5px rgba(0,0,0,0.1);
        }

        .map-container iframe {
            width: 100%;
            height: 100%;
            border: 0;
        }

        /* Footer */
        footer {
            background: #0f172a;
            color: #94a3b8;
            padding: 40px 5% 20px;
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 40px;
        }

        .footer-brand h3 {
            color: white;
            font-size: 1.5rem;
        }

        .footer-social {
            display: flex;
            gap: 20px;
        }

        .footer-social a {
            color: #94a3b8;
            font-size: 1.5rem;
            transition: 0.3s;
        }

        .footer-social a:hover {
            color: #eab308;
        }

        .footer-links {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
        }

        .footer-links a {
            color: #94a3b8;
            text-decoration: none;
        }

        .footer-links a:hover {
            color: #eab308;
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #334155;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .contact-grid {
                grid-template-columns: 1fr;
            }
            .hero-meta {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Floating CTA -->
    <a href="tel:9364430831" class="floating-cta">
        <i class="fas fa-phone-alt"></i>
        <span>Call Now: (936) 443-0831</span>
    </a>

    <!-- Hero -->
    <section class="hero">
        <div class="hero-content">
            <h1>
                Trittion Construction
                <span>Montgomery • Conroe • Spring</span>
            </h1>
            <p>Flooring • Concrete • Dirt Work • Fencing • Landscaping • Remodeling</p>
            <div class="hero-meta">
                <div class="hero-meta-item"><i class="fas fa-star"></i> 1 Review</div>
                <div class="hero-meta-item"><i class="fas fa-users"></i> 71 Followers</div>
                <div class="hero-meta-item"><i class="fas fa-images"></i> 38 Posts</div>
            </div>
            <div class="hero-buttons">
                <a href="#contact" class="btn btn-primary">Free Estimate</a>
                <a href="#instagram" class="btn btn-outline">View Our Work</a>
            </div>
        </div>
    </section>

    <!-- Info Bar -->
    <div class="info-bar">
        <div class="info-item">
            <div class="info-icon"><i class="fas fa-map-pin"></i></div>
            <div class="info-text">
                <h4>Service Area</h4>
                <p>Montgomery, Conroe, Spring, TX</p>
            </div>
        </div>
        <div class="info-item">
            <div class="info-icon"><i class="fas fa-phone"></i></div>
            <div class="info-text">
                <h4>Call or Text</h4>
                <p><a href="tel:9364430831">(936) 443-0831</a></p>
            </div>
        </div>
        <div class="info-item">
            <div class="info-icon"><i class="fas fa-envelope"></i></div>
            <div class="info-text">
                <h4>Email</h4>
                <p><a href="mailto:dioniciogarcia242@gmail.com">dioniciogarcia242@gmail.com</a></p>
            </div>
        </div>
        <div class="info-item">
            <div class="info-icon"><i class="fas fa-clock"></i></div>
            <div class="info-text">
                <h4>Hours</h4>
                <p>Mon-Fri 8am-5pm • Closed Now</p>
            </div>
        </div>
    </div>

    <!-- Stats Bar (extra social proof) -->
    <div class="stats-bar">
        <div class="stat-item">
            <div class="stat-number">38</div>
            <div class="stat-label">Instagram Posts</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">71</div>
            <div class="stat-label">Followers</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">⭐ 5.0</div>
            <div class="stat-label">1 Review</div>
        </div>
        <div class="stat-item">
            <div class="stat-number">📞 24/7</div>
            <div class="stat-label">Call Anytime</div>
        </div>
    </div>

    <!-- Services -->
    <section class="services" id="services">
        <div class="section-header">
            <h2>Our Services</h2>
            <p>Quality craftsmanship for residential & commercial</p>
        </div>
        <div class="services-grid">
            <div class="service-card"><i class="fas fa-border-all service-icon"></i><h3>Flooring</h3><p>Tile, hardwood, laminate, vinyl</p></div>
            <div class="service-card"><i class="fas fa-trowel service-icon"></i><h3>Concrete</h3><p>Driveways, patios, foundations</p></div>
            <div class="service-card"><i class="fas fa-tractor service-icon"></i><h3>Dirt Work</h3><p>Excavation, grading, clearing</p></div>
            <div class="service-card"><i class="fas fa-fence service-icon"></i><h3>Fencing</h3><p>Wood, vinyl, chain-link</p></div>
            <div class="service-card"><i class="fas fa-tree service-icon"></i><h3>Landscaping</h3><p>Design, planting, hardscape</p></div>
            <div class="service-card"><i class="fas fa-home service-icon"></i><h3>Remodeling</h3><p>Kitchen, bath, whole home</p></div>
        </div>
    </section>

    <!-- Instagram Feed -->
    <section class="instagram-feed" id="instagram">
        <div class="section-header">
            <h2>Latest from Instagram</h2>
            <p>@trittion_construction • 38 posts</p>
        </div>
        <div class="feed-grid">
            <!-- Post 1: Tile installation Feb 12 -->
            <div class="feed-post">
                <div class="post-image" style="background-image: url('https://images.unsplash.com/photo-1581851234877-65f7b0d6d12b?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80');">
                    <div class="post-date">Feb 12</div>
                </div>
                <div class="post-caption">
                    <p>Another beautiful tile installation completed today! From preparation to final detail, we delivered...</p>
                    <div class="post-likes"><i class="fas fa-heart"></i> 6 likes · 1 comment</div>
                </div>
            </div>
            <!-- Post 2: Driveway Jan 17 -->
            <div class="feed-post">
                <div class="post-image" style="background-image: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80');">
                    <div class="post-date">Jan 17</div>
                </div>
                <div class="post-caption">
                    <p>Another beautiful driveway and walkway addition enhancing the look, function, and value...</p>
                    <div class="post-likes"><i class="fas fa-heart"></i> 12 likes · 2 comments</div>
                </div>
            </div>
            <!-- Post 3: Before & After Flooring Jan 3 -->
            <div class="feed-post">
                <div class="post-image" style="background-image: url('https://images.unsplash.com/photo-1595428774223-ef52624120d2?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80');">
                    <div class="post-date">Jan 3</div>
                </div>
                <div class="post-caption">
                    <p>Before & After – New Flooring Installation. We completed this flooring upgrade at this beautiful home...</p>
                    <div class="post-likes"><i class="fas fa-heart"></i> 9 likes · 1 comment</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Meet the Owner -->
    <section class="owner">
        <div class="owner-card">
            <div class="owner-avatar">
                <i class="fas fa-user-tie"></i>
            </div>
            <div class="owner-info">
                <h3>Dionicio Garcia</h3>
                <p>Owner & Operator • “Fulfill your dreams.” With over 10 years of experience, Dionicio leads Trittion Construction with a commitment to quality and fair pricing. Every project is personal.</p>
                <div class="owner-contact">
                    <a href="tel:9364430831"><i class="fas fa-phone"></i> (936) 443-0831</a>
                    <a href="mailto:dioniciogarcia242@gmail.com"><i class="fas fa-envelope"></i> Email</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact + Map -->
    <section class="contact-map" id="contact">
        <div class="section-header">
            <h2>Request a Free Estimate</h2>
            <p>We'll respond within 24 hours</p>
        </div>
        <div class="contact-grid">
            <div class="contact-form">
                <h3>Tell us about your project</h3>
                <form id="estimateForm" onsubmit="event.preventDefault(); alert('Thanks! We’ll be in touch soon.');">
                    <div class="form-group"><input type="text" placeholder="Full Name*" required></div>
                    <div class="form-group"><input type="email" placeholder="Email Address*" required></div>
                    <div class="form-group"><input type="tel" placeholder="Phone Number"></div>
                    <div class="form-group">
                        <select required>
                            <option value="">Select Service*</option>
                            <option>Flooring</option>
                            <option>Concrete</option>
                            <option>Dirt Work</option>
                            <option>Fencing</option>
                            <option>Landscaping</option>
                            <option>Remodeling</option>
                        </select>
                    </div>
                    <div class="form-group"><textarea placeholder="Project details*" required></textarea></div>
                    <button type="submit" class="form-btn">Get Free Estimate →</button>
                </form>
            </div>
            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3452.547814176177!2d-95.616222084891!3d30.388736681472!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x86472c0e1f3b7e45%3A0x7b5b7f5e5f5e5f5e!2s16869%20W%20Forrestal%20Rd%2C%20Montgomery%2C%20TX%2077316!5e0!3m2!1sen!2sus!4v1645555555555!5m2!1sen!2sus" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <h3>Trittion Construction</h3>
                <p>16869 west Forrestal, Montgomery, TX 77316</p>
            </div>
            <div class="footer-social">
                <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                <a href="#" aria-label="Linktree"><i class="fas fa-tree"></i></a>
            </div>
            <div class="footer-links">
                <a href="#">Cookie Preferences</a>
                <a href="#">Report</a>
                <a href="#">Privacy</a>
            </div>
        </div>
        <div class="copyright">
            &copy; 2025 Trittion Construction. All rights reserved. | Join @trittion_construction on Linktree
        </div>
    </footer>

    <script>
        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if(target) target.scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>