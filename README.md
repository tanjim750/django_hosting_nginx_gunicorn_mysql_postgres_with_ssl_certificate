 <h1>🐍 Django Deployment on Ubuntu with PostgreSQL, Gunicorn &amp; Nginx</h1>
<p>This guide walks you through deploying a Django project on an Ubuntu server using <strong>PostgreSQL</strong> as the database, <strong>Gunicorn</strong> as the WSGI server, and <strong>Nginx</strong> as the reverse proxy.</p>
<hr />
<h2>✅ Prerequisites</h2>
<ul>
<li>Ubuntu 22.04 server</li>
<li>A non-root sudo user</li>
<li>Firewall configured (e.g., UFW)</li>
<li>Domain name (optional but recommended)</li>
</ul>
<hr />
<h2>1. 🧱 Install Required Packages</h2>
<p><code>bash
sudo apt update
sudo apt install python3-venv python3-dev libpq-dev postgresql postgresql-contrib nginx curl</code></p>
<hr />
