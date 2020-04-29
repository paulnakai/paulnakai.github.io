---
layout: default
title: Endurance Pursuits
permalink: /endurance/
--- 
<script>
    window.addEventListener('DOMContentLoaded', () => {

    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            const id = entry.target.getAttribute('id');
            if (entry.intersectionRatio > 0) {
                document.querySelector(`nav li a[href="#${id}"]`).parentElement.classList.add('active');
            } else {
                document.querySelector(`nav li a[href="#${id}"]`).parentElement.classList.remove('active');
            }
        });
    });

    document.querySelectorAll('section[id]').forEach((section) => {
        observer.observe(section);
    });
    
});
</script>

# {{ page.title }}

<div class="grid-endurance">
    <p> I enjoy endurance sports as one of my main hobbies. I am currently diving deeper into my love of running, and I have dabbled in triathlon and intend to continue to hone my swimming and biking. Below is an overview of my journey, which is hopefully just beginning!</p>
    <div class="iframe-container">
        <iframe frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/athletes/38702205/activity-summary/3fdde31678660e67b32fc2cda4ffc53b5a221592' class="resp-iframe"></iframe>
    </div>
</div>

## Timeline
<div class="endr">
    <nav class="section-nav">
        <ul>
            <li><a href="#2018">2018</a></li>
            <li><a href="#2019">2019</a></li>
            <li><a href="#2020">2020</a></li>
        </ul>
    </nav>
    <div>
        <section id="2018">
            <h2>2018</h2>
                <div>

Highlights: super fun first Half-Ironman (HIM) and first marathon.

Lowlights: bad *second* HIM and *second* marathon.

I succeeded in my primary goals of completing my first half-ironman (HIM) and my first marathon. Both races went well. I also raced a second HIM and Marathon. Beginner's enthusiasm made me squeeze these extra races in, which led to inadequate prep for the second HIM, an IT band injury during the race, and running the second marathon when I had just barely healed (and very undertrained). I was lucky to not re-aggravate the injury, and it was painful.

All in all, a great season. Learned a lot, lots of milestones, lots of fun!
                </div>
                <div> pic goes here </div>
                <h5>Races</h5>
                <table class="u-full-width">
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Type</th>
                            <th>Time</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Lavaman</td>
                            <td>Olympic tri</td>
                            <td>2:38:59</td>
                        </tr>
                        <tr>
                            <td>Horseshoe Lake</td>
                            <td>Half-marathon (trail)</td>
                            <td>1:38:21</td>
                        </tr>
                        <tr>
                            <td>Hawaii 70.3</td>
                            <td>Half-Ironman</td>
                            <td>5:38:16</td>
                        </tr>
                        <tr>
                            <td>SF Marathon</td>
                            <td>Marathon</td>
                            <td>3:05:51</td>
                        </tr>
                        <tr>
                            <td>Santa Cruz 70.3</td>
                            <td>Half-Ironman</td>
                            <td>5:40:08</td>
                        </tr>
                        <tr>
                            <td>Honolulu Marathon</td>
                            <td>Marathon</td>
                            <td>3:43:43</td>
                        </tr>
                    </tbody>
                </table>
        </section>
        <section id="2019">
            <h2>2019</h2>
            <div>

Highlights: I completed my primary goals of staying healthy and qualifying for the Ironman World Championships in Kona. I got to compete in the IM World Champs!!! And I got to "train" while doing a solo bike trip across Umbria, Italy.

Lowlights: My training through the year was inconsistent due to traveling/moving. This inconsistency lowered my motivation to train even when I could train.

I raced less this year, and I'm happy to say that meant I was better about not overextending myself. Didn't get hurt! But on the flip-side, I still had subpar preparation for a lot of my races. I set PBs in several races, but only because I still have so few races under my belt. The Ironman World Champs was about the only race I had a great preparation for, and thank goodness for that, because what a beast!
                </div>
                <div> pic goes here </div>
                <h5>Races</h5>
                <table class="u-full-width">
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Type</th>
                            <th>Time</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Stanford Treeathlon</td>
                            <td>Sprint tri</td>
                            <td>1:13:06</td>
                        </tr>
                        <tr>
                            <td>Rock'n'Roll Madrid</td>
                            <td>Half-marathon</td>
                            <td>1:26:58</td>
                        </tr>
                        <tr>
                            <td>Hawaii 70.3</td>
                            <td>Half-Ironman</td>
                            <td>5:22:24</td>
                        </tr>
                        <tr>
                            <td>Mana 10's</td>
                            <td>10mi run</td>
                            <td>1:08:21</td>
                        </tr>
                        <tr>
                            <td>Ironman World Champs</td>
                            <td>Ironman</td>
                            <td>11:44:55</td>
                        </tr>
                    </tbody>
                </table>
        </section>
        <section id="2020">
            <h2>2020</h2>
            <div>

Goals
- Sub-3hr marathon (qualify for Boston)
- Raise bike FTP to 250
- Sub-5hr HIM

Trying to be more patient this year. Focus on shorter distances, build my base, avoid injury by not feeling like I have to do long-distance races to be "impressive." The mantra: go fast while you're young!

Still picking races. More to come!
                </div>
                <div> pic goes here </div>
                <h5>Races</h5>
                <table class="u-full-width">
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Type</th>
                            <th>Time</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Sample name</td>
                            <td>Sample type</td>
                            <td>Sample time</td>
                        </tr>
                    </tbody>
                </table> 
        </section>
    </div>
</div>
