<h1 class="code-line" data-line-start="0" data-line-end="1"><a id="Digital_Marketing_Web_0"></a>Digital Marketing Web</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3">
    A Node.js and Express-based web application for showcasing Sunhare digital marketing services. This multi-page site includes a Home, Services, and Contact page, built with EJS templating, request logging,Docker and Kubernetes support for easy deployment.
</p>

<h2 class="code-line" data-line-start="4" data-line-end="5"><a id="Table_of_Contents_4"></a>Table of Contents</h2>
<ul>
    <li class="has-line-data" data-line-start="5" data-line-end="6"><a href="#features">Features</a></li>
    <li class="has-line-data" data-line-start="6" data-line-end="7"><a href="#tech-stack">Tech Stack</a></li>
    <li class="has-line-data" data-line-start="7" data-line-end="8"><a href="#getting-started">Getting Started</a></li>
    <li class="has-line-data" data-line-start="8" data-line-end="9"><a href="#project-structure">Project Structure</a></li>
    <li class="has-line-data" data-line-start="9" data-line-end="10"><a href="#docker-instructions">Docker Instructions</a></li>
    <li class="has-line-data" data-line-start="10" data-line-end="11"><a href="#kubernetes-deployment">Kubernetes Deployment</a></li>
    <li class="has-line-data" data-line-start="11" data-line-end="12"><a href="#contributing">Contributing</a></li>
    <li class="has-line-data" data-line-start="12" data-line-end="14"><a href="#license">License</a></li>
</ul>

<h2 class="code-line" data-line-start="14" data-line-end="15"><a id="Features_14"></a>Features</h2>
<ul>
    <li class="has-line-data" data-line-start="15" data-line-end="16"><strong>Multi-page Structure</strong>: Includes Home, Services, and Contact pages rendered with EJS.</li>
    <li class="has-line-data" data-line-start="16" data-line-end="17"><strong>Logging</strong>: Utilizes Morgan for detailed HTTP request logging.</li>
    <li class="has-line-data" data-line-start="17" data-line-end="18"><strong>Static File Serving</strong>: Hosts static assets like CSS, JavaScript, and images.</li>
    <li class="has-line-data" data-line-start="18" data-line-end="20"><strong>Docker Support</strong>: Dockerized for consistent and quick deployment in various environments.</li>
</ul>

<h2 class="code-line" data-line-start="20" data-line-end="21"><a id="Tech_Stack_20"></a>Tech Stack</h2>
<ul>
    <li class="has-line-data" data-line-start="21" data-line-end="22"><strong>Backend</strong>: Node.js, Express</li>
    <li class="has-line-data" data-line-start="22" data-line-end="23"><strong>Templating</strong>: EJS</li>
    <li class="has-line-data" data-line-start="23" data-line-end="24"><strong>Logging</strong>: Morgan</li>
    <li class="has-line-data" data-line-start="24" data-line-end="26"><strong>Containerization</strong>: Docker</li>
</ul>

<h2 class="code-line" data-line-start="26" data-line-end="27"><a id="Getting_Started_26"></a>Getting Started</h2>
<h3 class="code-line" data-line-start="28" data-line-end="29"><a id="Installation_28"></a>Installation</h3>
<ol>
    <li class="has-line-data" data-line-start="29" data-line-end="33"><strong>Clone the repository</strong>:
        <pre><code class="has-line-data" data-line-start="31" data-line-end="33" class="language-bash">git clone https://github.com/vinaysunhare/digital-marketing-web.git
cd digital-marketing-web
</code></pre>
    </li>
</ol>

<h2 class="code-line" data-line-start="33" data-line-end="34"><a id="Install_dependencies_33"></a>Install dependencies:</h2>
<pre><code class="has-line-data" data-line-start="35" data-line-end="72" class="language-bash">npm install 
</code></pre>

# Run the application:
</code><pre>
node server.js
</code></pre>

Access the app at http://localhost:3000.

<h3 class="code-line" data-line-start="36" data-line-end="37"><a id="Project_Structure_36"></a>Project Structure</h3>
<pre><code class="has-line-data" data-line-start="37" data-line-end="42">
digital-marketing-web/
├── public/          # Static assets (CSS, JS, images)
├── views/           # EJS templates (index.ejs, services.ejs, contact.ejs)
├── server.js        # Main server file
└── package.json     # Project dependencies
</code></pre>

<h2 class="code-line" data-line-start="42" data-line-end="43"><a id="Docker_Instructions_42"></a>Docker Instructions</h2>
<p><strong>Build the Docker image:</strong></p>
<pre><code class="has-line-data" data-line-start="45" data-line-end="46" class="language-bash">docker build -t digital-marketing-web .
</code></pre>

<p><strong>Run the Docker container:</strong></p>
<pre><code class="has-line-data" data-line-start="47" data-line-end="48" class="language-bash">docker run -p 3000:3000 digital-marketing-web
</code></pre>
<p>Access the app at <a href="http://localhost:3000">http://localhost:3000</a>.</p>

<h2 class="code-line" data-line-start="48" data-line-end="49"><a id="Kubernetes_Deployment_48"></a>Kubernetes Deployment</h2>
<p>To deploy on Kubernetes, apply the following configuration:</p>
<pre><code class="has-line-data" data-line-start="50" data-line-end="51" class="language-bash">kubectl apply -f service.yaml
</code></pre>

<h2 class="code-line" data-line-start="51" data-line-end="52"><a id="Contributing_51"></a>Contributing</h2>
<p>Contributions are welcome! Please open an issue or pull request for any improvements.</p>

<h2 class="code-line" data-line-start="52" data-line-end="53"><a id="License_52"></a>License</h2>
<p>This project is licensed under the MIT License.</p>

<h2 class="code-line" data-line-start="52" data-line-end="53"><a id="Contact_53"></a>Contact</h2>
<p>If you have any questions or suggestions, feel free to reach out to us at vinaysunhare25@gmail.com</p>
