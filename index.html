<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Journey to Trust | An Interactive Devotional on Psalm 13</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;1,300;1,400&family=Source+Sans+3:wght@400;600;700&display=swap" rel="stylesheet">
    
    <!-- Chosen Palette: Warm Neutrals -->
    <!-- Application Structure Plan: The SPA is designed around a central, tab-based interactive framework. The main navigation separates the devotional into thematic sections: 'Home', 'Scripture', 'Core Concepts', and 'Prayer'. The Core Concepts section uses interactive tabs for 'Principle', 'Problem', 'Gospel', and 'Response' to guide the user through the PPGR framework. Interactive textareas are included in the introduction and each core concept to gather user reflections. This data is then synthesized in the 'Prayer' section by the Gemini API into a final, personalized prayer, creating a guided journey from understanding to personal application. -->
    <!-- Visualization & Content Choices: Report Info: The devotional's content is theological and reflective. Goal: To make abstract concepts tangible and personal. Viz/Presentation Method: Interactive textareas for user input are central. Interaction: Users write their own reflections which are stored in a JS object. A button press sends this compiled object to the Gemini API. Justification: This transforms the app from a content delivery system into a personal journaling and prayer generation tool, dramatically increasing engagement and personal value. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <!-- Copyright (c) 2025 PPGR360. All Rights Reserved. -->

    <style>
        body {
            font-family: 'Source Sans 3', sans-serif;
            background-color: #FDFBF8; /* Warm Off-White */
            color: #4B423A; /* Dark Brown */
        }
        h1, h2, h3, h4, .font-heading {
            font-family: 'Merriweather', serif;
        }
        .nav-link {
            transition: color 0.3s, border-color 0.3s;
        }
        .nav-link.active {
            color: #D3A578; /* Muted Gold */
            border-bottom-color: #D3A578;
        }
        .concept-tab.active {
            background-color: #D3A578; /* Muted Gold */
            color: #FDFBF8;
        }
        .highlight-verse {
            background-color: #F3E9DE; /* Light Beige */
            border-radius: 4px;
            padding: 2px 4px;
            transition: background-color 0.5s ease;
        }
        .content-panel {
            display: none;
        }
        .content-panel.active {
            display: block;
        }
    </style>
</head>
<body class="antialiased">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <header class="text-center mb-8">
            <h1 class="text-4xl md:text-5xl font-bold text-[#6D5D4D]">The Journey to Trust</h1>
            <p class="text-lg text-[#8A7968] mt-2">An Interactive Devotional on Psalm 13</p>
        </header>

        <nav class="flex justify-center border-b border-[#EAE0D5] mb-8">
            <a href="#" id="nav-scripture" class="nav-link text-lg font-semibold py-4 px-6 border-b-2 border-transparent hover:text-[#D3A578]">Scripture Reflection</a>
            <a href="#" id="nav-core-concepts" class="nav-link text-lg font-semibold py-4 px-6 border-b-2 border-transparent hover:text-[#D3A578]">Explore the Core Concepts</a>
            <a href="#" id="nav-prayer" class="nav-link text-lg font-semibold py-4 px-6 border-b-2 border-transparent hover:text-[#D3A578]">Personalize Your Prayer</a>
        </nav>

        <main id="main-content">
            
            <section id="scripture-content" class="content-panel">
                 <div class="max-w-3xl mx-auto bg-white/50 p-8 rounded-lg shadow-sm border border-[#EAE0D5]">
                    <h2 class="text-3xl font-bold mb-4 text-[#6D5D4D]">Scripture</h2>
                    <p class="text-lg leading-relaxed mb-4">Psalm 13 is a powerful, honest cry from a heart in pain. It’s a short but profound journey from the depths of despair to a confident declaration of trust. In just six verses, David models for us how to bring our rawest emotions to God, wrestle with feelings of abandonment, and anchor ourselves in the unchanging reality of His character. This devotional is designed to help you walk that same path, applying the gospel to the moments when you feel like crying out, "How long, O LORD?"</p>
                    <div class="mt-8 pt-8 border-t border-[#EAE0D5]">
                        <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Connect with the Psalm</h3>
                        <p class="text-lg text-[#8A7968] mb-4">What initial thoughts or feelings does this Psalm bring up for you?</p>
                        <textarea id="intro-input" class="personalization-input w-full p-3 border border-[#EAE0D5] rounded-md focus:ring-2 focus:ring-[#D3A578] focus:outline-none transition duration-200 bg-white" rows="3" placeholder="My initial reflections are..."></textarea>
                    </div>

                    <div class="mt-8 pt-8 border-t border-[#EAE0D5]">
                         <h3 class="text-3xl font-bold mb-4 text-[#6D5D4D]">Psalm 13 (ESV)</h3>
                         <p class="text-sm italic text-[#8A7968] mb-6">To the choirmaster. A Psalm of David.</p>
                        <div class="space-y-4 text-lg">
                            <p><span class="font-bold pr-2">¹</span><span id="verse-1">How long, O LORD? Will you forget me forever? How long will you hide your face from me?</span></p>
                            <p><span class="font-bold pr-2">²</span><span id="verse-2">How long must I take counsel in my soul and have sorrow in my heart all the day? How long shall my enemy be exalted over me?</span></p>
                            <p><span class="font-bold pr-2">³</span><span id="verse-3">Consider and answer me, O LORD my God; light up my eyes, lest I sleep the sleep of death,</span></p>
                            <p><span class="font-bold pr-2">⁴</span><span id="verse-4">lest my enemy say, “I have prevailed over him,” lest my foes rejoice because I am shaken.</span></p>
                            <p><span class="font-bold pr-2">⁵</span><span id="verse-5">But I have trusted in your steadfast love; my heart shall rejoice in your salvation.</span></p>
                            <p><span class="font-bold pr-2">⁶</span><span id="verse-6">I will sing to the LORD, because he has dealt bountifully with me.</span></p>
                        </div>
                        <div class="mt-8 pt-8 border-t border-[#EAE0D5]">
                            <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Expository Notes</h3>
                            <ul class="space-y-4 text-lg leading-relaxed">
                                <li><strong class="font-semibold text-[#6D5D4D]">vv. 1-2 (The Agonizing Lament):</strong> David unleashes a torrent of raw emotion, repeating 'How long?' four times. This isn't weak faith, but deep, honest relationship. He feels forgotten, unseen, and overwhelmed by internal sorrow and external threats. He is 'taking counsel in his soul,' stuck in a loop of anxious thoughts.</li>
                                <li><strong class="font-semibold text-[#6D5D4D]">vv. 3-4 (The Urgent Plea):</strong> The lament turns into a direct appeal. David stops talking *about* God and starts talking *to* God, asking for consideration, an answer, and renewed life ('light up my eyes'). The stakes are high: death and the shame of his enemies claiming victory.</li>
                                <li><strong class="font-semibold text-[#6D5D4D]">v. 5 (The Decisive Turn):</strong> The word 'But' is the hinge of the psalm. David's circumstances haven't changed, but his focus has. He actively chooses to remember and rely on God's 'steadfast love' (*hesed*). This trust, based on God's character not his feelings, births joy.</li>
                                 <li><strong class="font-semibold text-[#6D5D4D]">v. 6 (The Confident Song):</strong> The psalm concludes not with a plea, but with a song of praise. Faith has led to joy, and joy overflows in worship. David sings by remembering God’s past faithfulness, which fuels his present trust and future hope.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>

            <section id="core-concepts-content" class="content-panel">
                <div class="max-w-4xl mx-auto">
                    <div class="text-center mb-8">
                        <h2 class="text-3xl font-bold text-[#6D5D4D]">Exploring the Core Concepts</h2>
                        <p class="text-lg text-[#8A7968] mt-2">Click each tab to explore a part of the PPGR framework and reflect on how it applies to your life.</p>
                    </div>
                    <div class="flex justify-center space-x-2 sm:space-x-4 mb-8">
                        <button data-tab="principle" class="concept-tab px-4 py-2 sm:px-6 sm:py-3 font-semibold rounded-full transition-colors duration-300 bg-[#EAE0D5] hover:bg-[#D3A578] hover:text-white">Principle</button>
                        <button data-tab="problem" class="concept-tab px-4 py-2 sm:px-6 sm:py-3 font-semibold rounded-full transition-colors duration-300 bg-[#EAE0D5] hover:bg-[#D3A578] hover:text-white">Problem</button>
                        <button data-tab="gospel" class="concept-tab px-4 py-2 sm:px-6 sm:py-3 font-semibold rounded-full transition-colors duration-300 bg-[#EAE0D5] hover:bg-[#D3A578] hover:text-white">Gospel</button>
                        <button data-tab="response" class="concept-tab px-4 py-2 sm:px-6 sm:py-3 font-semibold rounded-full transition-colors duration-300 bg-[#EAE0D5] hover:bg-[#D3A578] hover:text-white">Response</button>
                    </div>
                    
                    <div class="bg-white/50 p-8 rounded-lg shadow-sm border border-[#EAE0D5]">
                        <div id="principle-panel" class="concept-panel">
                            <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Principle: God invites our honest lament as a pathway to deeper trust.</h3>
                            <p class="text-lg leading-relaxed">The raw anguish in David's fourfold cry of "How long?" is not the opposite of faith; it is the language of a relationship built on trust. David feels safe enough with God to be brutally honest about his feelings. He brings his pain directly to the only One he truly believes can help him. God desires a relationship with us that is real, not religious. He makes space for our questions and despair, knowing that bringing our brokenness to Him is the very first step toward renewing our **trust**.</p>
                            <div class="mt-6 pt-6 border-t border-[#EAE0D5]">
                                <h4 class="text-xl font-semibold mb-2 text-[#6D5D4D]">Make it Personal</h4>
                                <p class="text-lg text-[#8A7968] mb-4">What specific "How long?" questions are weighing on your heart today that you need to honestly bring to God?</p>
                                <textarea id="principle-input" class="personalization-input w-full p-3 border border-[#EAE0D5] rounded-md" rows="3" placeholder="I feel like asking God, 'How long...' about..."></textarea>
                            </div>
                        </div>
                        <div id="problem-panel" class="concept-panel" style="display:none;">
                            <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Problem: In suffering, our hearts are prone to a crisis of trust, leading us to rely on ourselves.</h3>
                            <p class="text-lg leading-relaxed">The problem emerges when our feelings of being forgotten sever our active trust in God. David describes this: "How long must I take counsel in my soul...?" (v. 2). When we stop **trusting** God, we turn inward. We place our **trust** in our own limited wisdom and strength. This self-reliant **trust** is an idol that always fails, leading only to deeper sorrow. The core sin is misplacing our **trust** from the faithful Creator onto our fickle selves.</p>
                             <div class="mt-6 pt-6 border-t border-[#EAE0D5]">
                                <h4 class="text-xl font-semibold mb-2 text-[#6D5D4D]">Make it Personal</h4>
                                <p class="text-lg text-[#8A7968] mb-4">In what areas are you 'taking counsel in your own soul' instead of trusting God's steadfast love?</p>
                                <textarea id="problem-input" class="personalization-input w-full p-3 border border-[#EAE0D5] rounded-md" rows="3" placeholder="I tend to rely on myself when it comes to..."></textarea>
                            </div>
                        </div>
                        <div id="gospel-panel" class="concept-panel" style="display:none;">
                            <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Gospel: Jesus demonstrates perfect trust in the Father on our behalf, even through the ultimate trial.</h3>
                            <p class="text-lg leading-relaxed">The ultimate crisis of faith was borne by Jesus on the cross. Crying out, "My God, my God, why have you forsaken me?", Jesus faced the terror of divine abandonment that we fear. Yet, in His final breath, He declared, "Father, into your hands I commit my spirit!" (Luke 23:46). This was the ultimate act of trust. He perfectly trusted the Father's plan even through death itself. Here is the gospel exchange: Jesus's perfect, unwavering **trust** is credited to us, and our broken, faltering trust was nailed to the cross with Him. Because He trusted the Father for us, we can begin to truly trust God as our loving Father, no matter what our circumstances scream at us.</p>
                             <div class="mt-6 pt-6 border-t border-[#EAE0D5]">
                                <h4 class="text-xl font-semibold mb-2 text-[#6D5D4D]">Make it Personal</h4>
                                <p class="text-lg text-[#8A7968] mb-4">How does knowing Jesus perfectly trusted the Father for you, even in abandonment, give you confidence to trust God now?</p>
                                <textarea id="gospel-input" class="personalization-input w-full p-3 border border-[#EAE0D5] rounded-md" rows="3" placeholder="Because Jesus trusted for me, I can face..."></textarea>
                            </div>
                        </div>
                        <div id="response-panel" class="concept-panel" style="display:none;">
                            <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">Response: In union with Christ, we are empowered by the Spirit to actively choose trust over despair.</h3>
                            <p class="text-lg leading-relaxed mb-4">The dramatic pivot in verse 5—"But I have **trusted** in your steadfast love"—is the Spirit-empowered response of a heart secured by the gospel. This is not a change in feelings but a declaration of faith. Because of Jesus's finished work, we are no longer left alone to "take counsel" in our souls. Rather than trusting our sorrow, we can, by the Spirit's power, choose to place our trust in God's steadfast love. This is a gift, not a duty. We can sing of God's goodness not because we feel it's true, but because we trust the One who has already secured our salvation.</p>
                             <div class="mt-6 pt-6 border-t border-[#EAE0D5]">
                                <h4 class="text-xl font-semibold mb-2 text-[#6D5D4D]">Make it Personal</h4>
                                <p class="text-lg text-[#8A7968] mb-4">What would it look like, practically, to shift from trusting your feelings of sorrow to trusting in God's steadfast love in your current situation?</p>
                                <textarea id="response-input" class="personalization-input w-full p-3 border border-[#EAE0D5] rounded-md" rows="3" placeholder="I can actively trust God by..."></textarea>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="prayer-content" class="content-panel">
                <div class="max-w-3xl mx-auto bg-white/50 p-8 rounded-lg shadow-sm border border-[#EAE0D5]">
                    <h2 class="text-3xl font-bold mb-4 text-[#6D5D4D]">Your Personal Prayer</h2>
                     <div class="mt-4">
                        <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D] flex items-center">
                            A Prayer from Your Reflections
                        </h3>
                        <p class="text-lg text-[#8A7968] mb-4">After reflecting in the sections above, click the button below to compile your personal thoughts into a single, comprehensive prayer rooted in the hope of Psalm 13.</p>
                        <button id="compile-prayer-btn" class="w-full mb-4 px-6 py-3 font-semibold rounded-full transition-colors duration-300 bg-[#D3A578] text-white hover:bg-[#c59461]">
                            ✨ Compile My Prayer from My Reflections
                        </button>
                        <div id="compiled-prayer-output" class="p-4 bg-[#F3E9DE]/50 rounded-md border border-[#EAE0D5]" style="display: none;"></div>
                    </div>
                    <div class="mt-8 pt-8 border-t border-[#EAE0D5]">
                        <h3 class="text-2xl font-bold mb-4 text-[#6D5D4D]">For Further Study</h3>
                        <div class="space-y-4">
                            <div class="p-4 bg-white rounded-lg border border-[#EAE0D5]">
                                <h4 class="font-bold text-xl text-[#6D5D4D]">Psalm 22</h4>
                                <p class="text-lg text-[#8A7968]">Trace the path of profound suffering and ultimate vindication that Jesus himself quoted on the cross, connecting your own lament to Christ's.</p>
                            </div>
                            <div class="p-4 bg-white rounded-lg border border-[#EAE0D5]">
                                <h4 class="font-bold text-xl text-[#6D5D4D]">Lamentations 3:19-24</h4>
                                <p class="text-lg text-[#8A7968]">See how the prophet Jeremiah, in the midst of national ruin, finds hope by recalling God's great faithfulness and steadfast love (*hesed*).</p>
                            </div>
                            <div class="p-4 bg-white rounded-lg border border-[#EAE0D5]">
                                <h4 class="font-bold text-xl text-[#6D5D4D]">Habakkuk 3:17-19</h4>
                                <p class="text-lg text-[#8A7968]">Witness a powerful declaration of choosing to find joy and strength in God alone, even when every external source of security fails.</p>
                            </div>
                            <div class="p-4 bg-white rounded-lg border border-[#EAE0D5]">
                                <h4 class="font-bold text-xl text-[#6D5D4D]">Romans 8:31-39</h4>
                                <p class="text-lg text-[#8A7968]">Anchor your heart in the ultimate promise that nothing can separate you from the love of God in Christ Jesus, the foundation of all true trust.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer class="mt-12 py-4 border-t border-[#EAE0D5]">
            <p class="text-center text-sm text-[#8A7968]">&copy; 2025 PPGR360. All Rights Reserved.</p>
        </footer>

    </div>

<script>
    document.addEventListener('DOMContentLoaded', () => {
        const navLinks = document.querySelectorAll('.nav-link');
        const contentPanels = document.querySelectorAll('.content-panel');
        const conceptTabs = document.querySelectorAll('.concept-tab');
        const conceptPanels = document.querySelectorAll('.concept-panel');
        const personalizationInputs = document.querySelectorAll('.personalization-input');
        const compilePrayerBtn = document.getElementById('compile-prayer-btn');
        const compiledPrayerOutput = document.getElementById('compiled-prayer-output');

        const userReflections = {
            intro: '',
            principle: '',
            problem: '',
            gospel: '',
            response: ''
        };

        const verseMap = {
            principle: 1,
            problem: 2,
            gospel: 5,
            response: 6,
        };

        function updateNav(activeLink) {
            navLinks.forEach(link => link.classList.remove('active'));
            activeLink.classList.add('active');
        }

        function showContent(contentId) {
            contentPanels.forEach(panel => {
                panel.style.display = 'none';
                panel.classList.remove('active');
            });
            const activePanel = document.getElementById(contentId);
            if (activePanel) {
                activePanel.style.display = 'block';
                activePanel.classList.add('active');
            }
        }

        function removeVerseHighlights() {
            for (let i = 1; i <= 6; i++) {
                const verseSpan = document.getElementById(`verse-${i}`);
                if (verseSpan) verseSpan.classList.remove('highlight-verse');
            }
        }

        function highlightVerse(verseNumber) {
            removeVerseHighlights();
            const verseSpan = document.getElementById(`verse-${verseNumber}`);
            if (verseSpan) verseSpan.classList.add('highlight-verse');
        }

        navLinks.forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                const sectionId = e.target.id.replace('nav-', '');
                updateNav(e.target);
                showContent(`${sectionId}-content`);
                
                if (sectionId === 'core-concepts') {
                    conceptTabs[0].click();
                } else {
                    removeVerseHighlights();
                }
            });
        });

        conceptTabs.forEach(tab => {
            tab.addEventListener('click', (e) => {
                const tabId = e.target.dataset.tab;
                conceptTabs.forEach(t => t.classList.remove('active'));
                e.target.classList.add('active');
                
                const conceptContentPanels = document.getElementById('core-concepts-content').querySelectorAll('.concept-panel');
                conceptContentPanels.forEach(panel => panel.style.display = 'none');
                
                document.getElementById(`${tabId}-panel`).style.display = 'block';

                if (verseMap[tabId]) {
                    highlightVerse(verseMap[tabId]);
                } else {
                     removeVerseHighlights();
                }
            });
        });

        personalizationInputs.forEach(input => {
            input.addEventListener('input', () => {
                const reflectionKey = input.id.split('-')[0];
                userReflections[reflectionKey] = input.value;
            });
        });
        
        compilePrayerBtn.addEventListener('click', async () => {
            const hasReflections = Object.values(userReflections).some(val => val.trim() !== '');

            if (!hasReflections) {
                compiledPrayerOutput.innerHTML = '<p class="text-red-600">Please share some of your reflections in the Home or Core Concepts sections before creating a prayer.</p>';
                compiledPrayerOutput.style.display = 'block';
                return;
            }

            compiledPrayerOutput.style.display = 'block';
            compiledPrayerOutput.innerHTML = '<p class="text-center text-[#8A7968]">✨ Weaving your thoughts into a prayer...</p>';
            compilePrayerBtn.disabled = true;
            compilePrayerBtn.classList.add('opacity-50', 'cursor-not-allowed');

            try {
                const systemPrompt = "You are a wise and empathetic pastoral guide. The user has provided their personal reflections on the different parts of Psalm 13. Synthesize their raw, personal notes into a beautiful, cohesive, first-person prayer. The prayer should follow the natural flow of the passage: acknowledging the struggle, affirming God's character, remembering Christ's work, and committing to a response of faith and trust. Weave the user's specific thoughts and feelings seamlessly into this structure.";
                
                const userPrompt = `Here are my reflections on Psalm 13:
- My initial thoughts on the psalm: "${userReflections.intro}"
- My personal 'How long?' questions (Principle): "${userReflections.principle}"
- Areas where I trust myself instead of God (Problem): "${userReflections.problem}"
- How Jesus's perfect trust impacts me (Gospel): "${userReflections.gospel}"
- How I want to respond by choosing trust (Response): "${userReflections.response}"`;

                const generatedText = await callGemini(systemPrompt, userPrompt);
                compiledPrayerOutput.innerHTML = `<p class="text-lg leading-loose italic">${generatedText.replace(/\n/g, '<br>')}</p>`;
            } catch (error) {
                console.error('Error compiling prayer:', error);
                compiledPrayerOutput.innerHTML = '<p class="text-red-600">Sorry, something went wrong. Please try again later.</p>';
            } finally {
                compilePrayerBtn.disabled = false;
                compilePrayerBtn.classList.remove('opacity-50', 'cursor-not-allowed');
            }
        });

        async function callGemini(systemPrompt, userPrompt, retries = 3, delay = 1000) {
            const apiKey = ""; 
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

            const payload = {
                contents: [{ parts: [{ text: userPrompt }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
            };

            for (let i = 0; i < retries; i++) {
                try {
                    const response = await fetch(apiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });

                    if (!response.ok) throw new Error(`HTTP error! status: ${response.status}`);
                    
                    const result = await response.json();
                    const candidate = result.candidates?.[0];

                    if (candidate && candidate.content?.parts?.[0]?.text) {
                        return candidate.content.parts[0].text;
                    } else {
                         throw new Error('Invalid response structure from Gemini API');
                    }
                } catch (error) {
                    if (i === retries - 1) throw error;
                    await new Promise(res => setTimeout(res, delay * Math.pow(2, i)));
                }
            }
             throw new Error('API call failed after multiple retries.');
        }

        // Initialize the app view
        document.getElementById('nav-scripture').click();

    });
</script>

</body>
</html>

