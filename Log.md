Ran into a few problems trying the Google Colab notebook this week. For "What happens when you try to include columns 1-4?", I used the same code used in the previous block: options(digits=3) numSummary(DartPoints[, 5:11]). That gave me an error because apparently columns one to four are headings and do not have values. So Gemini tried to help me troubleshoot and I wound up with this:
<img width="721" height="584" alt="Screenshot 2026-11-03 at 10 23 34 AM" src="https://github.com/user-attachments/assets/8a7022fa-c1e5-4de4-83a7-70dde637b3a2" />
It goes on for so long.
