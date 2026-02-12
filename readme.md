🔹 1️⃣ ip (Most Important Command)
✅ Check IP address
ip addr

✅ Check network interfaces
ip link

✅ Check routing table
ip route


👉 Modern replacement for ifconfig

🔹 2️⃣ ifconfig (Old Command)
ifconfig


Shows IP address

Shows network details
⚠️ May not be installed by default in Ubuntu

Install:

sudo apt install net-tools

🔹 3️⃣ ping

Check connectivity to another system.

ping google.com


👉 Tests internet connection.

🔹 4️⃣ netstat (Old but Important)
netstat -tulnp


Shows open ports

Shows running services

Modern replacement:

ss -tulnp

🔹 5️⃣ ss (Modern Command)
ss -tuln


Shows:

Listening ports

Active connections

🔹 6️⃣ traceroute

Shows path packets travel.

traceroute google.com


Install if not present:

sudo apt install traceroute

🔹 7️⃣ nslookup

Check DNS details.

nslookup google.com

🔹 8️⃣ curl

Test website or API.

curl google.com

🔹 9️⃣ wget

Download file from internet.

wget http://example.com/file.zip

🔹 🔟 hostname

Check system hostname.

hostname


Check IP with hostname:

hostname -I

🎯 Most Important for Interview

ip addr

ping

ss -tuln

netstat -tulnp

traceroute

nslookup
