---
layout: home
lang-ref: home-page
title: "Ethereal"
subtitle: "A Horizontal Jekyll Template"
banner:
    id: "banner"
    title: "Ethereal Template"
    subtitle: "by HTML5 Up"
    description: >-
        This is <strong>Ethereal</strong>, a free static site template designed by AJ for <a href='https://html5up.net'>HTML5 UP</a> and ported to Jekyll by <a href='https://moodule.github.io'>MOODULE</a>. It’s fully responsive, built on HTML5 and CSS3, and released entirely for free under the Creative Commons license. Hope you dig it :)
    button:
        target: "#first"
        label: "Next"
    style:
        size: "medium"
        text:
            position: "right"
        header:
            color: "color0"
        background:
            image: "assets/images/pillars-of-creation.jpg"
            color:
first:
    id: first
    title: Sed etiam aenean
    description: >-
        Mauris et ligula arcu. Proin dapibus convallis accumsan. Lorem maximus hendrerit orci, sit amet elementum massa hendrerit sed. Donec et ullamcorper ligula. Suspendisse amet potenti. Ut pretium libero eleifend euismod sed tristique. Quisque dictum magna risus, id ultricies justo sagittis vitae. Sed id odio tempor, porttitor elit amet, gravida hendrerit fringilla lorem ipsum dolor.
    style:
        size: large
        text:
            position: right
        background:
            image: "assets/images/orion_las.jpg"
            color: color2
second:
    id: second
    title: Amet lorem
    description: >-
        Sed vel nibh libero. Mauris et lorem pharetra massa lorem turpis congue pulvinar. Vivamus sed feugiat finibus. Duis amet bibendum amet sed. Duis mauris ex, dapibus sed ligula tempus volutpat magna etiam.
    style:
        size: medium
        text:
            position: left
        background:
            image:
            color: color1
third:
    id: third
    title: Magna amet tempus
    description: >-
        Mauris a cursus velit. Nunc lacinia sollicitudin egestas bibendum, magna dui bibendum ex, sagittis commodo enim risus sed magna nulla. Vestibulum ut consequat velit. Curabitur vitae libero lorem. Quisque iaculis porttitor blandit. Nullam quis sagittis maximus. Sed vel nibh libero. Mauris et lorem pharetra massa lorem turpis congue pulvinar.
    style:
        size: large
        text:
            position: left
        background:
            image: "assets/images/zeta-ophiuchi.jpg"
            color:
fourth:
    id:
    title:
    description:
    content:
        gallery:
            -
                - url:
                  position:
                  span:
                - url:
                  position:
                  span:
                - url:
                  position:
                  span:
            - url:
              position:
              span:
            -
                - url:
                  position:
                  span:
                - url:
                  position:
                  span:
                - url:
                  position:
                  span:
                - url:
                  position:
                  span:
    style:
contact:
    id: contact
    title: Contact
    description: >-
        Sed vel nibh libero. Mauris et lorem pharetra massa lorem turpis congue pulvinar. Vivamus sed feugiat finibus. Duis amet bibendum amet sed. Duis mauris ex, dapibus sed ligula tempus volutpat magna etiam.
    style:
        size: large
        background:
            color: color4-alt
        header:
            color: color4
        icons:
            color: color1
---

{% include spotlight.html id=page.first.id title=page.first.title description=page.first.description style=page.first.style %}

{% include panel.html id=page.second.id title=page.second.title description=page.second.description style=page.second.style %}

{% include spotlight.html id=page.third.id title=page.third.title description=page.third.description style=page.third.style %}

<!-- Panel -->
<section class="panel color0">
    <div class="intro color2">
        <h2 class="major">Elit integer</h2>
        <p>Sed vel nibh libero. Mauris et lorem pharetra massa lorem turpis congue pulvinar. Vivamus sed feugiat finibus. Duis amet bibendum amet sed. Duis mauris ex, dapibus sed ligula tempus volutpat magna etiam.</p>
    </div>
    <div class="gallery">
        <div class="group span-3">
            <a href="{{ 'assets/images/gallery/fulls/01.jpg' | absolute_url }}" class="image filtered span-3" data-position="bottom"><img src="{{ 'assets/images/gallery/thumbs/01.jpg' | absolute_url }}" alt="" /></a>
            <a href="{{ 'assets/images/gallery/fulls/02.jpg' | absolute_url }}" class="image filtered span-1-5" data-position="center"><img src="{{ 'assets/images/gallery/thumbs/02.jpg' | absolute_url }}" alt="" /></a>
            <a href="{{ 'assets/images/gallery/fulls/03.jpg' | absolute_url }}" class="image filtered span-1-5" data-position="bottom"><img src="{{ 'assets/images/gallery/thumbs/03.jpg' | absolute_url }}" alt="" /></a>
        </div>
        <a href="{{ 'assets/images/gallery/fulls/04.jpg' | absolute_url }}" class="image filtered span-2-5" data-position="top"><img src="{{ 'assets/images/gallery/thumbs/04.jpg' | absolute_url }}" alt="" /></a>
        <div class="group span-4-5">
            <a href="{{ 'assets/images/gallery/fulls/05.jpg' | absolute_url }}" class="image filtered span-3" data-position="top"><img src="{{ 'assets/images/gallery/thumbs/05.jpg' | absolute_url }}" alt="" /></a>
            <a href="{{ 'assets/images/gallery/fulls/06.jpg' | absolute_url }}" class="image filtered span-1-5" data-position="center"><img src="{{ 'assets/images/gallery/thumbs/06.jpg' | absolute_url }}" alt="" /></a>
            <a href="{{ 'assets/images/gallery/fulls/07.jpg' | absolute_url }}" class="image filtered span-1-5" data-position="bottom"><img src="{{ 'assets/images/gallery/thumbs/07.jpg' | absolute_url }}" alt="" /></a>
            <a href="{{ 'assets/images/gallery/fulls/08.jpg' | absolute_url }}" class="image filtered span-3" data-position="top"><img src="{{ 'assets/images/gallery/thumbs/08.jpg' | absolute_url }}" alt="" /></a>
        </div>
        <a href="{{ 'assets/images/gallery/fulls/09.jpg' | absolute_url }}" class="image filtered span-2-5" data-position="right"><img src="{{ 'assets/images/gallery/thumbs/09.jpg' | absolute_url }}" alt="" /></a>
    </div>
</section>

{% include contact.html id=page.contact.id title=page.contact.title description=page.contact.description style=page.contact.style %}

<!-- Panel -->
<section class="panel color2-alt">
    <div class="intro color2">
        <h2 class="major">Elements</h2>
        <p>Sed vel nibh libero. Mauris et lorem pharetra massa lorem turpis congue pulvinar. Vivamus sed feugiat finibus. Duis amet bibendum amet sed. Duis mauris ex, dapibus sed ligula tempus volutpat magna etiam. </p>
    </div>
    <div class="inner columns aligned">
        <div class="span-2-75">

            <h3 class="major">Text</h3>
            <p>This is <b>bold</b> and this is <strong>strong</strong>. This is <i>italic</i> and this is <em>emphasized</em>.
            This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
            This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>. Finally, <a href="#">this is a link</a>.</p>

            <h1>Heading Level 1</h1>
            <h2>Heading Level 2</h2>
            <h3>Heading Level 3</h3>
            <h4>Heading Level 4</h4>
            <h5>Heading Level 5</h5>
            <h6>Heading Level 6</h6>

        </div>
        <div class="span-3">

            <h4>Blockquote</h4>
            <blockquote>Lorem ipsum dolor sit amet. Felis sagittis eget tempus euismod. Vestibulum ante ipsum primis in vestibulum. Blandit adipiscing eu iaculis volutpat ac adipiscing volutpat ac adipiscing faucibus.</blockquote>

            <h4>Preformatted</h4>
            <pre><code>i = 0;

while (!deck.isInOrder()) {
print 'Iteration ' + (i++);
deck.shuffle();
}

print 'It took ' + i + ' iterations to sort the deck.';</code></pre>

        </div>
        <div class="span-1-25">

            <h3 class="major">Lists</h3>

            <h4>Unordered</h4>
            <ul>
                <li>Lorem ipsum dolor sit.</li>
                <li>Dolor pulvinar etiam.</li>
                <li>Etiam vel felis viverra.</li>
            </ul>

            <h4>Alternate</h4>
            <ul class="alt">
                <li>Lorem ipsum dolor sit.</li>
                <li>Dolor pulvinar etiam.</li>
                <li>Etiam vel felis viverra.</li>
                <li>Felis enim feugiat.</li>
            </ul>

        </div>
        <div class="span-1-5">

            <h4>Ordered</h4>
            <ol>
                <li>Lorem ipsum dolor sit.</li>
                <li>Dolor pulvinar etiam.</li>
                <li>Etiam vel felis viverra.</li>
                <li>Felis enim feugiat.</li>
                <li>Etiam vel felis lorem.</li>
            </ol>

            <h4>Actions</h4>
            <ul class="actions">
                <li><a href="#" class="button primary color2">Default</a></li>
                <li><a href="#" class="button">Default</a></li>
            </ul>
            <ul class="actions stacked">
                <li><a href="#" class="button primary color2">Default</a></li>
                <li><a href="#" class="button">Default</a></li>
            </ul>

        </div>
        <div class="span-1-25">

            <h4>Icons</h4>
            <ul class="icons">
                <li><a href="#" class="icon brands fa-twitter"><span class="label">Twitter</span></a></li>
                <li><a href="#" class="icon brands fa-facebook-f"><span class="label">Facebook</span></a></li>
                <li><a href="#" class="icon brands fa-instagram"><span class="label">Instagram</span></a></li>
                <li><a href="#" class="icon brands fa-github"><span class="label">GitHub</span></a></li>
                <li><a href="#" class="icon brands fa-medium-m"><span class="label">Medium</span></a></li>
            </ul>

            <h4>Contact Icons</h4>
            <ul class="contact-icons color2">
                <li class="icon brands fa-twitter"><a href="#">Twitter</a></li>
                <li class="icon brands fa-facebook-f"><a href="#">Facebook</a></li>
                <li class="icon brands fa-instagram"><a href="#">Instagram</a></li>
                <li class="icon brands fa-github"><a href="#">GitHub</a></li>
                <li class="icon brands fa-medium-m"><a href="#">Medium</a></li>
            </ul>

        </div>
        <div class="span-3">
            <h3 class="major">Table</h3>
            <h4>Default</h4>
            <div class="table-wrapper">
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td> Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tfoot>
                </table>
            </div>
        </div>
        <div class="span-3">
            <h4>Alternate</h4>
            <div class="table-wrapper">
                <table class="alt">
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Description</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Item One</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Two</td>
                            <td>Vis ac commodo adipiscing arcu aliquet.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Three</td>
                            <td> Morbi faucibus arcu accumsan lorem.</td>
                            <td>29.99</td>
                        </tr>
                        <tr>
                            <td>Item Four</td>
                            <td>Vitae integer tempus condimentum.</td>
                            <td>19.99</td>
                        </tr>
                        <tr>
                            <td>Item Five</td>
                            <td>Ante turpis integer aliquet porttitor.</td>
                            <td>29.99</td>
                        </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="2"></td>
                            <td>100.00</td>
                        </tr>
                    </tfoot>
                </table>
            </div>
        </div>
        <div class="span-2-25">
            <h3 class="major">Buttons</h3>
            <ul class="actions">
                <li><a href="#" class="button primary color2">Primary</a></li>
                <li><a href="#" class="button">Default</a></li>
            </ul>
            <ul class="actions">
                <li><a href="#" class="button">Default</a></li>
                <li><a href="#" class="button large">Large</a></li>
                <li><a href="#" class="button small">Small</a></li>
            </ul>
            <ul class="actions">
                <li><a href="#" class="button primary color2 icon solid fa-cog">Icon</a></li>
                <li><a href="#" class="button icon fa-gem">Icon</a></li>
            </ul>
            <ul class="actions">
                <li><span class="button primary color2 disabled">Disabled</span></li>
                <li><span class="button disabled">Disabled</span></li>
            </ul>
            <ul class="actions">
                <li><a href="#" class="button primary color2 circle icon solid fa-cog">Icon</a></li>
                <li><a href="#" class="button circle icon fa-gem">Icon</a></li>
            </ul>
        </div>
        <div class="span-4-5">
            <h3 class="major">Form</h3>
            <form method="post" action="#">
                <div class="fields">
                    <div class="field third">
                        <label for="demo-name">Name</label>
                        <input type="text" name="demo-name" id="demo-name" value="" placeholder="Jane Doe" />
                    </div>
                    <div class="field third">
                        <label for="demo-email">Email</label>
                        <input type="email" name="demo-email" id="demo-email" value="" placeholder="jane@untitled.tld" />
                    </div>
                    <div class="field third">
                        <label for="demo-category">Category</label>
                        <div class="select-wrapper">
                            <select name="demo-category" id="demo-category">
                                <option value="">-</option>
                                <option value="1">Manufacturing</option>
                                <option value="1">Shipping</option>
                                <option value="1">Administration</option>
                                <option value="1">Human Resources</option>
                            </select>
                        </div>
                    </div>
                    <div class="field quarter">
                        <input type="radio" id="demo-priority-low" name="demo-priority" class="color2" checked />
                        <label for="demo-priority-low">Low Priority</label>
                    </div>
                    <div class="field quarter">
                        <input type="radio" id="demo-priority-high" name="demo-priority" class="color2" />
                        <label for="demo-priority-high">High Priority</label>
                    </div>
                    <div class="field quarter">
                        <input type="checkbox" id="demo-copy" name="demo-copy" class="color2" />
                        <label for="demo-copy">Email a copy</label>
                    </div>
                    <div class="field quarter">
                        <input type="checkbox" id="demo-human" name="demo-human" class="color2" checked />
                        <label for="demo-human">Not a robot</label>
                    </div>
                    <div class="field">
                        <label for="demo-message">Message</label>
                        <textarea name="demo-message" id="demo-message" placeholder="Enter your message" rows="2"></textarea>
                    </div>
                </div>
                <ul class="actions">
                    <li><input type="submit" value="Send Message" class="primary color2" /></li>
                    <li><input type="reset" value="Reset" /></li>
                </ul>
            </form>
        </div>
    </div>
</section>