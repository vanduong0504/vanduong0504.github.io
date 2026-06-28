---
layout: post
title: Half Marathon Plan
subtitle: 24-week training plan — Techcombank HCM Half Marathon
tags: [running, fitness]
full-width: true
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=DM+Mono:wght@400;500&display=swap');
  .hm-plan {
    --bg:      #0F1117;
    --border:  rgba(255,255,255,0.07);
    --text:    #E8EAF0;
    --muted:   rgba(232,234,240,0.42);
    --easy:    #4CAF82;
    --int:     #E05A2A;
    --tempo:   #F0A830;
    --long:    #6B7FD4;
    --trial:   #C84070;
    --stair:   #A0C878;
    --race:    #D4404A;
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-size: 13px;
    border-radius: 8px;
    overflow: hidden;
    margin: 0 -20px;
  }
  .hm-plan header {
    padding: 24px 20px 18px;
    border-bottom: 1px solid var(--border);
    display: flex; flex-wrap: wrap; gap: 16px;
    align-items: center; justify-content: space-between;
    background: var(--bg);
  }
  .hm-plan .plan-title { font-size: 18px; font-weight: 700; letter-spacing: -0.01em; color: var(--text); }
  .hm-plan .legend { display: flex; flex-wrap: wrap; gap: 8px; }
  .hm-plan .leg { display: flex; align-items: center; gap: 4px; font-family: 'DM Mono', monospace; font-size: 10px; color: var(--muted); }
  .hm-plan .dot { width: 7px; height: 7px; border-radius: 50%; }

  .hm-plan .phase-label {
    padding: 7px 16px;
    font-family: 'DM Mono', monospace; font-size: 10px;
    letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--muted); background: rgba(255,255,255,0.02);
    border-bottom: 1px solid var(--border);
  }

  .hm-plan .table-wrap { overflow-x: auto; }
  .hm-plan table { width: 100%; border-collapse: collapse !important; min-width: 680px; background: var(--bg) !important; color: var(--text) !important; }
  .hm-plan thead th {
    font-family: 'DM Mono', monospace; font-size: 10px;
    letter-spacing: 0.08em; text-transform: uppercase;
    color: var(--muted) !important; padding: 8px 12px; text-align: left;
    border-bottom: 1px solid var(--border) !important; border-top: none !important; font-weight: 500;
    background: var(--bg) !important;
  }
  .hm-plan tbody tr { background: transparent !important; border-bottom: 1px solid rgba(255,255,255,0.07) !important; }
  .hm-plan tbody tr:hover { background: rgba(255,255,255,0.04) !important; }
  .hm-plan tbody tr.deload { background: rgba(255,255,255,0.03) !important; }
  .hm-plan tbody tr.racerow { background: rgba(212,64,74,0.08) !important; }
  .hm-plan td { padding: 8px 12px !important; vertical-align: top !important; background: transparent !important; border: none !important; color: #E8EAF0 !important; }

  .hm-plan .wk { font-family: 'DM Mono', monospace; font-size: 11px; white-space: nowrap; }
  .hm-plan .wk b { display: block; color: #E8EAF0 !important; }
  .hm-plan .wk small { color: rgba(232,234,240,0.42) !important; font-size: 10px; }

  .hm-plan .chip {
    display: flex; flex-direction: column;
    border-radius: 5px; padding: 5px 8px;
    width: 100%; line-height: 1.3;
  }
  .hm-plan .ck { font-weight: 600; font-size: 12px; margin-bottom: 1px; color: #E8EAF0 !important; }
  .hm-plan .cd { font-size: 10.5px; opacity: 0.75; color: #E8EAF0 !important; }
  .hm-plan .ct { font-size: 10px; font-weight: 500; opacity: 0.85; margin-bottom: 1px; color: #E8EAF0 !important; }

  .hm-plan .c-easy   { background: rgba(76,175,130,0.13);  border-left: 3px solid #4CAF82; }
  .hm-plan .c-int    { background: rgba(224,90,42,0.13);   border-left: 3px solid #E05A2A; }
  .hm-plan .c-tempo  { background: rgba(240,168,48,0.13);  border-left: 3px solid #F0A830; }
  .hm-plan .c-long   { background: rgba(107,127,212,0.13); border-left: 3px solid #6B7FD4; }
  .hm-plan .c-trial  { background: rgba(200,64,112,0.13);  border-left: 3px solid #C84070; }
  .hm-plan .c-stair  { background: rgba(160,200,120,0.12); border-left: 3px solid #A0C878; }
  .hm-plan .c-race   { background: rgba(212,64,74,0.16);   border-left: 3px solid #D4404A; }
  .hm-plan .c-rest   { color: rgba(232,234,240,0.42) !important; font-size: 11px; padding: 5px 0; }

  .hm-plan footer {
    padding: 14px 20px;
    border-top: 1px solid var(--border);
    font-size: 11.5px; color: var(--muted);
    line-height: 1.6;
    background: var(--bg);
  }
</style>

<div class="hm-plan">

<header>
  <div class="plan-title">DƯƠNG · Half Marathon Plan + Leo Cầu Thang</div>
  <div class="legend">
    <div class="leg"><div class="dot" style="background:#4CAF82"></div>Easy</div>
    <div class="leg"><div class="dot" style="background:#E05A2A"></div>Intervals</div>
    <div class="leg"><div class="dot" style="background:#F0A830"></div>Tempo</div>
    <div class="leg"><div class="dot" style="background:#6B7FD4"></div>Long Run</div>
    <div class="leg"><div class="dot" style="background:#C84070"></div>Time Trial</div>
    <div class="leg"><div class="dot" style="background:#A0C878"></div>Leo cầu thang</div>
    <div class="leg"><div class="dot" style="background:#D4404A"></div>Race</div>
  </div>
</header>

<div class="table-wrap">

<div class="phase-label">Phase 1 — Base Building · Tuần 1–8</div>
<table>
  <thead><tr><th style="width:80px">Tuần</th><th>Thứ 4</th><th>Thứ 5 · Leo CThang</th><th>Thứ 6</th><th>Chủ nhật</th></tr></thead>
  <tbody>
    <tr>
      <td class="wk"><b>W1</b><small>22 Jun</small></td>
      <td><div class="chip c-rest">Rest</div></td>
      <td><div class="chip c-stair"><span class="ck">20'</span><span class="ct">Base Climb</span><span class="cd">Leo đều zone 2, thang máy xuống</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5.5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">7km</span><span class="cd">Progressive Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W2</b><small>29 Jun</small></td>
      <td><div class="chip c-int"><span class="ck">6km</span><span class="cd">400m Repeats</span></div></td>
      <td><div class="chip c-stair"><span class="ck">25'</span><span class="ct">Base Climb</span><span class="cd">Zone 2 liên tục, chú ý form gót</span></div></td>
      <td><div class="chip c-easy"><span class="ck">4km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">8km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W3</b><small>6 Jul</small></td>
      <td><div class="chip c-tempo"><span class="ck">6km</span><span class="cd">Progressive Run</span></div></td>
      <td><div class="chip c-stair"><span class="ck">30'</span><span class="ct">Base Climb</span><span class="cd">Zone 2, tăng 5' so tuần trước</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5.5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">9km</span><span class="cd">Block Long Run</span></div></td>
    </tr>
    <tr class="deload">
      <td class="wk"><b>W4 ↓</b><small>13 Jul</small></td>
      <td><div class="chip c-int"><span class="ck">4km</span><span class="cd">Rolling 400s</span></div></td>
      <td><div class="chip c-stair"><span class="ck">20'</span><span class="ct">Base Climb · Deload</span><span class="cd">Nhẹ nhàng, hồi phục</span></div></td>
      <td><div class="chip c-easy"><span class="ck">4.5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">6km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W5</b><small>20 Jul</small></td>
      <td><div class="chip c-int"><span class="ck">5.6km</span><span class="cd">200m Repeats</span></div></td>
      <td><div class="chip c-stair"><span class="ck">5×(3'+2')</span><span class="ct">Interval Stair</span><span class="cd">5 set: 3' leo nhanh + 2' leo nhẹ</span></div></td>
      <td><div class="chip c-easy"><span class="ck">6km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">10km</span><span class="cd">Progressive Repeat Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W6</b><small>27 Jul</small></td>
      <td><div class="chip c-tempo"><span class="ck">5km</span><span class="cd">Over and Unders 400m</span></div></td>
      <td><div class="chip c-stair"><span class="ck">40'</span><span class="ct">Base Climb</span><span class="cd">Zone 2, bắt đầu xuống cầu thang</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">11km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W7</b><small>3 Aug</small></td>
      <td><div class="chip c-tempo"><span class="ck">7km</span><span class="cd">On Off Ks</span></div></td>
      <td><div class="chip c-stair"><span class="ck">45'</span><span class="ct">Tempo Climb</span><span class="cd">Zone 3, nói chuyện khó, duy trì đều</span></div></td>
      <td><div class="chip c-easy"><span class="ck">6km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">12km</span><span class="cd">Progressive Long Run</span></div></td>
    </tr>
    <tr class="deload">
      <td class="wk"><b>W8 ↓</b><small>10 Aug</small></td>
      <td><div class="chip c-trial"><span class="ck">4.9km</span><span class="cd">2 Mile Time Trial</span></div></td>
      <td><div class="chip c-stair"><span class="ck">25'</span><span class="ct">Base Climb · Deload</span><span class="cd">Zone 2, cảm nhận chân</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">7.5km</span><span class="cd">Long Run</span></div></td>
    </tr>
  </tbody>
</table>

<div class="phase-label">Phase 2 — Build · Tuần 9–16</div>
<table>
  <thead><tr><th style="width:80px">Tuần</th><th>Thứ 4</th><th>Thứ 5 · Leo CThang</th><th>Thứ 6</th><th>Chủ nhật</th></tr></thead>
  <tbody>
    <tr>
      <td class="wk"><b>W9</b><small>17 Aug</small></td>
      <td><div class="chip c-tempo"><span class="ck">8km</span><span class="cd">Half Easy, Half Tempo</span></div></td>
      <td><div class="chip c-stair"><span class="ck">4×(5'+3')</span><span class="ct">Interval Stair</span><span class="cd">4 set: 5' hard + 3' recovery</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">12km</span><span class="cd">Progressive Repeat Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W10</b><small>24 Aug</small></td>
      <td><div class="chip c-tempo"><span class="ck">8km</span><span class="cd">Over and Unders 1km</span></div></td>
      <td><div class="chip c-stair"><span class="ck">55'</span><span class="ct">Tempo Climb</span><span class="cd">Zone 3–4, ~500m D+</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">13km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W11</b><small>31 Aug</small></td>
      <td><div class="chip c-int"><span class="ck">8.1km</span><span class="cd">Fast 8-4-2s</span></div></td>
      <td><div class="chip c-stair"><span class="ck">Power Bounds</span><span class="ct">Power Bounds</span><span class="cd">6× bước đôi + 40' base climb</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5.5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">13km</span><span class="cd">Progressive Long Run</span></div></td>
    </tr>
    <tr class="deload">
      <td class="wk"><b>W12 ↓</b><small>7 Sep</small></td>
      <td><div class="chip c-tempo"><span class="ck">5.6km</span><span class="cd">Tempo 1200s</span></div></td>
      <td><div class="chip c-stair"><span class="ck">30'</span><span class="ct">Base Climb · Deload</span><span class="cd">Zone 2, kéo giãn sau</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">7.5km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W13</b><small>14 Sep</small></td>
      <td><div class="chip c-tempo"><span class="ck">8km</span><span class="cd">On Off Ks</span></div></td>
      <td><div class="chip c-stair"><span class="ck">60'</span><span class="ct">Long Climb</span><span class="cd">Zone 2–3 liên tục, ~600m D+</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">14km</span><span class="cd">Block Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W14</b><small>21 Sep</small></td>
      <td><div class="chip c-int"><span class="ck">8km</span><span class="cd">1km Repeats</span></div></td>
      <td><div class="chip c-stair"><span class="ck">Pyramid</span><span class="ct">Pyramid Climb</span><span class="cd">5'+8'+10'+8'+5' với 2' active rest</span></div></td>
      <td><div class="chip c-easy"><span class="ck">6km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">15km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W15</b><small>28 Sep</small></td>
      <td><div class="chip c-int"><span class="ck">7.6km</span><span class="cd">Rolling 300s</span></div></td>
      <td><div class="chip c-stair"><span class="ck">70'</span><span class="ct">Long Climb</span><span class="cd">~700m D+, mang vest 5kg nếu có</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">16km</span><span class="cd">Hotspot Long Run</span></div></td>
    </tr>
    <tr class="deload">
      <td class="wk"><b>W16 ↓</b><small>5 Oct</small></td>
      <td><div class="chip c-trial"><span class="ck">6km</span><span class="cd">5km Time Trial</span></div></td>
      <td><div class="chip c-stair"><span class="ck">35'</span><span class="ct">Base Climb · Deload</span><span class="cd">Nhẹ, xuống cầu thang kiểm soát</span></div></td>
      <td><div class="chip c-easy"><span class="ck">5.5km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">10km</span><span class="cd">Long Run</span></div></td>
    </tr>
  </tbody>
</table>

<div class="phase-label">Phase 3 — Peak & Taper · Tuần 17–24</div>
<table>
  <thead><tr><th style="width:80px">Tuần</th><th>Thứ 4</th><th>Thứ 5 · Leo CThang</th><th>Thứ 6</th><th>Chủ nhật</th></tr></thead>
  <tbody>
    <tr>
      <td class="wk"><b>W17</b><small>12 Oct</small></td>
      <td><div class="chip c-int"><span class="ck">8.1km</span><span class="cd">Drop Set</span></div></td>
      <td><div class="chip c-stair"><span class="ck">75'</span><span class="ct">Long Climb</span><span class="cd">Zone 2–3, ~750m D+, vest</span></div></td>
      <td><div class="chip c-easy"><span class="ck">9km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">17km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W18</b><small>19 Oct</small></td>
      <td><div class="chip c-tempo"><span class="ck">9km</span><span class="cd">Progressive Run</span></div></td>
      <td><div class="chip c-stair"><span class="ck">4×(10'+5')</span><span class="ct">Power Endurance</span><span class="cd">10' hard + 5' walk, HR 85–90%</span></div></td>
      <td><div class="chip c-easy"><span class="ck">10km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">18km</span><span class="cd">Race Practice Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W19</b><small>26 Oct</small></td>
      <td><div class="chip c-tempo"><span class="ck">9km</span><span class="cd">Tempo 4km</span></div></td>
      <td><div class="chip c-stair"><span class="ck">90'</span><span class="ct">Long Climb · Peak</span><span class="cd">~900m D+, vest, test nutrition</span></div></td>
      <td><div class="chip c-easy"><span class="ck">9km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">20km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr class="deload">
      <td class="wk"><b>W20 ↓</b><small>2 Nov</small></td>
      <td><div class="chip c-int"><span class="ck">6km</span><span class="cd">Mile Repeats</span></div></td>
      <td><div class="chip c-stair"><span class="ck">40'</span><span class="ct">Base Climb · Deload</span><span class="cd">Zone 2, chân hồi phục</span></div></td>
      <td><div class="chip c-easy"><span class="ck">7km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">10km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W21</b><small>9 Nov</small></td>
      <td><div class="chip c-tempo"><span class="ck">9km</span><span class="cd">Under and Overs 2km</span></div></td>
      <td><div class="chip c-stair"><span class="ck">75'</span><span class="ct">Tempo Climb</span><span class="cd">Zone 3, ~700m D+</span></div></td>
      <td><div class="chip c-easy"><span class="ck">9km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">18km</span><span class="cd">Block Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W22</b><small>16 Nov</small></td>
      <td><div class="chip c-tempo"><span class="ck">7.5km</span><span class="cd">Tempo 2-1-1</span></div></td>
      <td><div class="chip c-stair"><span class="ck">60'</span><span class="ct">Long Climb</span><span class="cd">Taper — zone 2–3, ~550m D+</span></div></td>
      <td><div class="chip c-easy"><span class="ck">9km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">15km</span><span class="cd">Long Run</span></div></td>
    </tr>
    <tr>
      <td class="wk"><b>W23</b><small>23 Nov</small></td>
      <td><div class="chip c-int"><span class="ck">6km</span><span class="cd">400m Repeats</span></div></td>
      <td><div class="chip c-stair"><span class="ck">45'</span><span class="ct">Base Climb</span><span class="cd">Taper — nhẹ, giữ cảm giác chân</span></div></td>
      <td><div class="chip c-easy"><span class="ck">9km</span><span class="cd">Easy Run</span></div></td>
      <td><div class="chip c-long"><span class="ck">11km</span><span class="cd">Race Practice Long Run</span></div></td>
    </tr>
    <tr class="racerow">
      <td class="wk"><b>W24 🏁</b><small>30 Nov</small></td>
      <td><div class="chip c-tempo"><span class="ck">6.5km</span><span class="cd">Race Pace Practice</span></div></td>
      <td><div class="chip c-rest">Rest</div></td>
      <td><div class="chip c-rest">Rest</div></td>
      <td><div class="chip c-race"><span class="ck">21.1km</span><span class="cd">Techcombank HCM Half Marathon · 12/6/26</span></div></td>
    </tr>
  </tbody>
</table>

</div>

<footer>
  Thứ 5 leo cầu thang: cross-training trail 50km. Phase 1 Base Climb 20–45' zone 2 · Phase 2 Interval/Pyramid/Long Climb ~600m D+ · Phase 3 peak 90' ~900m D+ → taper W22–23 · Race week nghỉ.
</footer>

</div>
