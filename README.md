# Aaron-demo-landing-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stop Bleeding Money on Google Ads That Don't Convert</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f9fa;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .preheader {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 20px;
            color: #ffd700;
        }
        
        .hero h1 {
            font-size: 42px;
            font-weight: bold;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero .subheader {
            font-size: 24px;
            margin-bottom: 40px;
            font-weight: 300;
        }
        
        .vsl-container {
            margin: 40px 0;
            position: relative;
        }
        
        .vsl-icon {
            display: inline-block;
            background: #000;
            border-radius: 20px;
            padding: 40px 60px;
            text-decoration: none;
            color: white;
            position: relative;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }
        
        .vsl-icon:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 40px rgba(0,0,0,0.4);
        }
        
        .play-button {
            width: 80px;
            height: 80px;
            background: #ff4757;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            position: relative;
        }
        
        .play-button::after {
            content: '';
            width: 0;
            height: 0;
            border-left: 25px solid white;
            border-top: 15px solid transparent;
            border-bottom: 15px solid transparent;
            margin-left: 5px;
        }
        
        .vsl-text {
            font-size: 18px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .cta-button {
            background: #ff4757;
            color: white;
            padding: 20px 40px;
            font-size: 20px;
            font-weight: bold;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            margin: 30px 0;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .cta-button:hover {
            background: #ff3742;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(255, 71, 87, 0.3);
        }
        
        .section {
            padding: 80px 0;
        }
        
        .section-white {
            background: white;
        }
        
        .section-gray {
            background: #f8f9fa;
        }
        
        .fascination-headline {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 40px;
            text-align: center;
            color: #1e3c72;
        }
        
        .content p {
            font-size: 18px;
            margin-bottom: 20px;
            line-height: 1.8;
        }
        
        .highlight {
            background: #ffd700;
            padding: 2px 6px;
            font-weight: bold;
        }
        
        .bold {
            font-weight: bold;
            color: #1e3c72;
        }
        
        .testimonial {
            background: white;
            padding: 30px;
            border-radius: 10px;
            margin: 30px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border-left: 5px solid #ff4757;
        }
        
        .testimonial-text {
            font-style: italic;
            font-size: 16px;
            margin-bottom: 15px;
        }
        
        .testimonial-author {
            font-weight: bold;
            color: #1e3c72;
        }
        
        .bullet-points {
            list-style: none;
            margin: 30px 0;
        }
        
        .bullet-points li {
            margin-bottom: 15px;
            padding-left: 30px;
            position: relative;
            font-size: 18px;
        }
        
        .bullet-points li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: #28a745;
            font-weight: bold;
            font-size: 20px;
        }
        
        .value-stack {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 10px;
            margin: 30px 0;
            border: 2px dashed #1e3c72;
        }
        
        .value-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
            border-bottom: 1px solid #ddd;
        }
        
        .value-item:last-child {
            border-bottom: none;
            font-weight: bold;
            font-size: 20px;
            color: #1e3c72;
        }
        
        .value-price {
            color: #28a745;
            font-weight: bold;
        }
        
        .faq {
            margin: 30px 0;
        }
        
        .faq-item {
            margin-bottom: 20px;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .faq-question {
            background: #1e3c72;
            color: white;
            padding: 20px;
            font-weight: bold;
            cursor: pointer;
        }
        
        .faq-answer {
            padding: 20px;
            display: block;
        }
        
        .urgency-box {
            background: linear-gradient(45deg, #ff4757, #ff6b7a);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            margin: 40px 0;
            box-shadow: 0 10px 30px rgba(255, 71, 87, 0.3);
        }
        
        .urgency-text {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .countdown {
            font-size: 16px;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 32px;
            }
            
            .hero .subheader {
                font-size: 20px;
            }
            
            .fascination-headline {
                font-size: 28px;
            }
            
            .container {
                padding: 0 15px;
            }
        }
    </style>
</head>
<body>
    <!-- HERO SECTION -->
    <div class="hero">
        <div class="container">
            <div class="preheader">
                FOR BUSINESS OWNERS SPENDING $5K-$10K+ ON GOOGLE ADS
            </div>
            
            <h1>Finally Scale Your Google Ads Past $10K/Month Without Watching Your ROI Crash and Burn</h1>
            
            <div class="subheader">
                Get profitable campaigns that actually convert... without relying on overpriced agencies or guessing your way through "advanced" tactics that don't work
            </div>
            
            <div class="vsl-container">
                <a href="https://docs.google.com/document/d/1oyDn9DnWOdv19LHG3zLV1TFVfAi-Qog34Ke2GduEln4/edit?usp=sharing" class="vsl-icon" target="_blank">
                    <div class="play-button"></div>
                    <div class="vsl-text">VSL I WROTE FOR YOU</div>
                </a>
            </div>
            
            <a href="#offer" class="cta-button">STOP BLEEDING MONEY - APPLY NOW</a>
        </div>
    </div>

    <!-- PROBLEM IDENTIFICATION -->
    <div class="section section-white">
        <div class="container">
            <h2 class="fascination-headline">
                You're Stuck in Google Ads Hell... And Every Day You Wait, Your Competitors Steal More of Your Market Share
            </h2>
            
            <div class="content">
                <p>Picture this...</p>

                <p>You open your Google Ads dashboard, and your heart sinks.</p>

                <p><span class="bold">Another $500 down the drain.</span></p>

                <p>The clicks are coming in. The numbers look decent on paper. But when you check your actual sales...</p>

                <p>Crickets.</p>

                <p>You've tried everything the "gurus" told you:</p>

                <p>✗ You hired that agency that promised the moon (they delivered a crater)<br>
                ✗ You bought every "advanced" course that claimed to have the "secret sauce"<br>
                ✗ You spent countless hours watching YouTube tutorials that contradict each other<br>
                ✗ You tested keywords, tweaked ads, adjusted bids... yet nothing moves the needle</p>

                <p>And now you're facing the brutal truth...</p>

                <p><span class="highlight">You're hemorrhaging money every single day your ads aren't profitable.</span></p>

                <p>While you're struggling to get a decent ROI, your competitors are scaling past you.</p>

                <p>They're capturing the customers that should be yours.</p>

                <p>They're growing their businesses while you're stuck spinning your wheels...</p>

                <p><span class="bold">But what if I told you there's a proven way to fix this?</span></p>

                <p>A way that doesn't involve complex "hacks" or expensive agencies...</p>

                <p>A method that actually works for businesses ready to scale past $10K/month...</p>
            </div>
        </div>
    </div>

    <!-- ORIGIN STORY -->
    <div class="section section-gray">
        <div class="container">
            <h2 class="fascination-headline">
                How I Went From Burning $50K on Failed Campaigns to Building a System That Consistently Delivers Profitable Results
            </h2>
            
            <div class="content">
                <p>Three years ago, I was exactly where you are now.</p>

                <p>I had a thriving business, but Google Ads was my Achilles heel.</p>

                <p>I'd burned through <span class="bold">$50,000</span> trying to make it work.</p>

                <p>Agency after agency promised they'd "crack the code."</p>

                <p>Course after course claimed they had the "missing piece."</p>

                <p>But here's what I learned the hard way...</p>

                <p><span class="highlight">Most Google Ads advice is designed for beginners spending $1K/month, not serious businesses ready to scale.</span></p>

                <p>The strategies that work at small budgets completely fall apart when you try to scale.</p>

                <p>That's when I had my breakthrough moment...</p>

                <p>I realized successful agencies don't use the same tactics they teach in their courses.</p>

                <p>They have an entirely different approach...</p>

                <p>A systematic method that focuses on <span class="bold">foundational mastery</span> instead of shiny new tactics.</p>

                <p>Once I cracked this code, everything changed.</p>

                <p>My campaigns went from bleeding money to generating consistent profits.</p>

                <p>I scaled past $10K/month... then $25K... then $50K...</p>

                <p>And I did it without depending on anyone else.</p>
            </div>
        </div>
    </div>

    <!-- SOLUTION REVELATION -->
    <div class="section section-white">
        <div class="container">
            <h2 class="fascination-headline">
                The "Done-With-You" Method That Turns Google Ads Into Your Most Profitable Marketing Channel
            </h2>
            
            <div class="content">
                <p>Here's what I learned...</p>

                <p>Most business owners fail with Google Ads because they're trying to run before they can walk.</p>

                <p>They jump straight to "advanced" tactics without mastering the fundamentals.</p>

                <p>It's like trying to perform surgery before learning anatomy.</p>

                <p><span class="bold">My "Done-With-You" system works differently...</span></p>

                <p>Instead of throwing tactics at the wall and hoping something sticks...</p>

                <p>We start with a complete audit of your current campaigns.</p>

                <p>We identify exactly where you're losing money.</p>

                <p>Then we build a custom growth plan designed specifically for your business.</p>

                <p>But here's the kicker...</p>

                <p><span class="highlight">You're not doing this alone.</span></p>

                <p>You get weekly 1:1 coaching calls where we work through your campaigns together.</p>

                <p>You get monthly masterclasses that dive deep into scaling strategies.</p>

                <p>You get 24/7 Slack support when you hit roadblocks.</p>

                <p>And you get access to "AI Aaron" - our custom AI coach that knows your campaigns inside and out.</p>

                <p><span class="bold">Result?</span></p>

                <p>You finally have profitable campaigns that scale predictably.</p>

                <p>You stop wasting money on guesswork.</p>

                <p>You gain the confidence to manage bigger budgets.</p>

                <p>And you never have to depend on underperforming agencies again.</p>
            </div>
        </div>
    </div>

    <!-- PRODUCT INTRODUCTION -->
    <div class="section section-gray">
        <div class="container">
            <h2 class="fascination-headline">
                Introducing the "Done-With-You" Google Ads Mastery Program
            </h2>
            
            <div class="content">
                <p>This isn't another course you'll buy and never finish.</p>

                <p>This isn't a generic agency service that treats you like account #47.</p>

                <p><span class="bold">This is hands-on, personalized coaching that gets results.</span></p>

                <p>Here's exactly what you get when you join:</p>

                <ul class="bullet-points">
                    <li><span class="bold">Complete Campaign Audit & Custom Growth Plan</span> → No more guessing what's broken in your account → You'll know exactly what to fix and how to fix it</li>
                    
                    <li><span class="bold">Weekly 1:1 Coaching Calls</span> → Stop struggling alone with campaign optimization → You'll have expert guidance every step of the way</li>
                    
                    <li><span class="bold">Monthly Scaling Masterclasses</span> → Learn advanced strategies that actually work at scale → You'll master techniques used by 7-figure businesses</li>
                    
                    <li><span class="bold">24/7 Slack Support</span> → Get answers to urgent questions immediately → You'll never feel stuck or abandoned</li>
                    
                    <li><span class="bold">"AI Aaron" Personal Coaching</span> → Your custom AI coach knows your campaigns inside out → You'll get personalized advice anytime, day or night</li>
                    
                    <li><span class="bold">Private Mastery Community</span> → Connect with other serious business owners → You'll learn from peers who are scaling successfully</li>
                </ul>

                <p>Compare this to hiring an agency...</p>

                <p>Agencies charge $3K-$10K per month and you still don't own the knowledge.</p>

                <p>When you leave, you're back to square one.</p>

                <p><span class="highlight">With the Done-With-You program, you own the system forever.</span></p>
            </div>
        </div>
    </div>

    <!-- OFFER STRUCTURE -->
    <div class="section section-white" id="offer">
        <div class="container">
            <h2 class="fascination-headline">
                Here's Everything You Get When You Apply Today
            </h2>
            
            <div class="value-stack">
                <div class="value-item">
                    <span>✓ Complete Campaign Audit & Custom Growth Plan</span>
                </div>
                <div class="value-item">
                    <span>✓ Weekly 1:1 Coaching Calls</span>
                </div>
                <div class="value-item">
                    <span>✓ Monthly Scaling Masterclasses</span>
                </div>
                <div class="value-item">
                    <span>✓ 24/7 Slack Support</span>
                </div>
                <div class="value-item">
                    <span>✓ "AI Aaron" Personal Coach Access</span>
                </div>
                <div class="value-item">
                    <span>✓ Private Mastery Community</span>
                </div>
            </div>

            <div class="content">
                <p><span class="bold">This level of personalized coaching normally costs businesses $10K+ per month...</span></p>

                <p>But I'm not interested in pricing out serious business owners who are ready to scale.</p>

                <p>That's why this is structured as an application-only program.</p>

                <div class="urgency-box">
                    <div class="urgency-text">
                        WARNING: Only 10 Spots Available This Month
                    </div>
                    <div class="countdown">
                        I can only work with a limited number of businesses at once to ensure quality results
                    </div>
                </div>

                <p><span class="highlight">Plus, you're protected by my 90-Day Results Guarantee...</span></p>

                <p>If you don't see measurable improvement in your campaign performance within 90 days, I'll refund every penny and let you keep all the materials.</p>

                <p>No questions asked.</p>

                <p><span class="bold">But here's the thing...</span></p>

                <p>This isn't for everyone.</p>

                <p>This program is designed for business owners who:</p>
                <p>• Are already spending $5K+ per month on Google Ads<br>
                • Want to scale past $10K/month profitably<br>
                • Are committed to implementing what they learn<br>
                • Value expertise over cheap DIY solutions</p>

                <p>If that sounds like you...</p>
            </div>

            <div style="text-align: center;">
                <a href="#apply" class="cta-button">APPLY FOR THE DONE-WITH-YOU PROGRAM</a>
            </div>
        </div>
    </div>

    <!-- FAQ SECTION -->
    <div class="section section-gray">
        <div class="container">
            <h2 class="fascination-headline">
                "But What If..." - Let Me Address Your Concerns
            </h2>
            
            <div class="faq">
                <div class="faq-item">
                    <div class="faq-question">
                        "What if I'm not spending enough on ads yet?"
                    </div>
                    <div class="faq-answer">
                        If you're spending under $5K/month, start with our Google Ads Search Bootcamp ($497) to build your foundation. Once you're ready to scale, the Done-With-You program will be waiting for you. Don't try to run before you can walk.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        "How is this different from hiring an agency?"
                    </div>
                    <div class="faq-answer">
                        Agencies do the work FOR you. We do it WITH you. When you leave an agency, you're back to square one. With our program, you own the knowledge and skills forever. Plus, you're not locked into expensive monthly contracts.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        "What if I don't have time for weekly calls?"
                    </div>
                    <div class="faq-answer">
                        If you don't have 60 minutes per week to invest in scaling your most profitable marketing channel, you're not ready for this program. Success requires commitment. But remember - this investment now saves you hundreds of hours of trial and error later.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        "Can you guarantee specific ROI results?"
                    </div>
                    <div class="faq-answer">
                        I can't guarantee specific numbers because every business is different. But I can guarantee you'll have a systematic approach that works, ongoing support when you need it, and the confidence to scale profitably. That's worth far more than any number promise.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        "What if this doesn't work for my industry?"
                    </div>
                    <div class="faq-answer">
                        The principles of profitable Google Ads work across all industries. We've helped everyone from e-commerce stores to B2B services to local businesses. The tactics might vary, but the foundation remains the same. That's what we'll customize for your specific situation.
                    </div>
                </div>
            </div>

            <div class="content">
                <p style="text-align: center; font-size: 20px; margin-top: 40px;">
                    <span class="bold">Ready to stop wasting money and start scaling profitably?</span>
                </p>
            </div>

            <div style="text-align: center;">
                <a href="#apply" class="cta-button">YES, I'M READY TO MASTER GOOGLE ADS</a>
            </div>

            <div class="content">
                <p style="text-align: center; font-style: italic; margin-top: 20px;">
                    Remember: Every day you wait is another day your competitors are getting ahead. The best time to fix your Google Ads was yesterday. The second best time is right now.
                </p>
            </div>
        </div>
    </div>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add some interactive elements
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', function() {
                const answer = this.nextElementSibling;
                answer.style.display = answer.style.display === 'none' ? 'block' : 'none';
            });
        });
    </script>
</body>
</html>
