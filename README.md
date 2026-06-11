
<div align="center">
<br>

<img src="https://github.com/takkun2355.png" width="120" style="border-radius:50%;" />

# Takkun2355
### 別名: UNKOMAN

Discord Bot Developer

🎂 09/24

<div class="counter-widget" style="width: 300px; height: 75px; border-radius: 12px; background: #f8fafc; border: 1px solid #e2e8f0; display: flex; flex-direction: column; justify-content: center; align-items: center; font-family: sans-serif; box-sizing: border-box; margin: 0; padding: 0;">
    <div class="label" style="font-size: 11px; color: #64748b; margin-bottom: 4px; box-sizing: border-box;">年齢</div>
    <div class="value" id="md-age" style="font-size: 16px; font-weight: bold; color: #3b82f6; box-sizing: border-box;">-</div>
</div>

[![Discord Presence](https://lanyard.cnrad.dev/api/985151399207788615?animated=false&showDisplayName=true)](https://discord.com/users/985151399207788615)

## 📊 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=takkun2355&show_icons=true&theme=tokyonight" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=takkun2355&layout=compact&theme=tokyonight" />
</p>

---

## 📈 Activity Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=takkun2355&theme=tokyo-night" />
</p>

---

## 🏆 Trophy

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=takkun2355&theme=tokyonight&row=1&column=6" />
<img src="https://github-profile-trophy.vercel.app/?username=takkun2355" />
</p>

---

## ⭐ Profile Summary

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=takkun2355&theme=tokyonight" />
</p>

---

## 🛠 Languages

<p align="center">
<img src="https://skillicons.dev/icons?i=python,html,css,js" />
</p>

---

## ⚙️ Tools

<p align="center">
<img src="https://skillicons.dev/icons?i=git,github,vscode,sqlite" />
</p>

---

## 👀 Visitors

<p align="center">
<img src="https://komarev.com/ghpvc/?username=takkun2355&style=flat-square" />
</p>

</div>
<script type="text/javascript">
    (function() {
        function updateAge() {
            const base = new Date(2011, 8, 24, 0, 0, 0);
            const now = new Date();
            
            let years = now.getFullYear() - base.getFullYear();
            let months = now.getMonth() - base.getMonth();
            let days = now.getDate() - base.getDate();
            let hours = now.getHours() - base.getHours();

            if (hours < 0) { days--; hours += 24; }
            if (days < 0) { months--; days += new Date(now.getFullYear(), now.getMonth(), 0).getDate(); }
            if (months < 0) { years--; months += 12; }

            const el = document.getElementById('md-age');
            if (el) {
                el.innerHTML = 
                    `${years}<span style="font-size: 11px; color: #334155; margin-right: 4px; font-weight: normal;">歳</span>` +
                    `${months}<span style="font-size: 11px; color: #334155; margin-right: 4px; font-weight: normal;">ヶ月</span>` +
                    `${days}<span style="font-size: 11px; color: #334155; margin-right: 4px; font-weight: normal;">日</span>` +
                    `${hours}<span style="font-size: 11px; color: #334155; margin-right: 4px; font-weight: normal;">時間</span>`;
            }
        }
        setInterval(updateAge, 1000);
        updateAge();
    })();
</script>
