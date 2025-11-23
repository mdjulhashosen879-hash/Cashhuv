<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Cashhuv — VIP Dashboard</title>
  <meta name="theme-color" content="#061735">
  <style>
    :root{
      --bg1: #04102a;
      --bg2: #07224a;
      --card: #0f2b63;
      --glass: rgba(255,255,255,0.04);
      --accent: #ffd662;
      --muted: #cfe3ff;
      --round: 14px;
      --maxw: 980px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;font-family: "Segoe UI", Roboto, Arial, sans-serif;
      background: linear-gradient(180deg,var(--bg1) 0%, var(--bg2) 100%);
      color:#fff;-webkit-font-smoothing:antialiased;
    }
    .wrap{max-width:var(--maxw);margin:12px auto;padding:14px}
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:12px;
      background:linear-gradient(135deg,#1554a8,#2b9adf);display:flex;
      align-items:center;justify-content:center;font-weight:800;color:#fff;font-size:20px;box-shadow:0 8px 24px rgba(0,0,0,.35)
    }
    .userline small{display:block;color:var(--muted);font-size:12px}
    .vip{background:linear-gradient(90deg,#ffd662,#ffb347);color:#061735;padding:6px 10px;border-radius:999px;font-weight:800;font-size:13px}
    /* Hero / Balance card */
    .hero{margin-top:14px;background:linear-gradient(90deg, rgba(255,255,255,0.03), rgba(0,0,0,0.02)); padding:18px;border-radius:var(--round);display:flex;gap:12px;align-items:center;box-shadow:0 10px 30px rgba(2,6,23,.6)}
    .bal{flex:1}
    .bal h2{margin:0;font-size:18px;color:var(--accent)}
    .bal .big{font-weight:800;font-size:22px;color:#fff;margin-top:6px}
    .statsmall{color:var(--muted);font-size:13px;margin-top:6px}
    .cta{display:flex;gap:8px;margin-top:10px;flex-wrap:wrap}
    .btn{background:var(--accent);color:#061735;padding:10px 14px;border-radius:12px;font-weight:800;text-decoration:none;display:inline-block}
    .btn2{border:1px solid rgba(255,255,255,.08);padding:10px 12px;border-radius:12px;color:var(--muted);text-decoration:none;display:inline-block}
    /* quick actions */
    .actions{display:flex;gap:10px;margin-top:12px;flex-wrap:wrap}
    .action{background:var(--card);padding:12px;border-radius:12px;min-width:110px;text-align:left;box-shadow:0 8px 20px rgba(0,0,0,.25)}
    .action b{display:block;margin-top:6px}
    /* Plans */
    .section-title{display:flex;align-items:center;justify-content:space-between;margin-top:18px}
    .plans{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:12px;margin-top:12px}
    .plan{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.02));padding:14px;border-radius:12px}
    .plan h3{margin:0;font-size:16px;color:var(--accent)}
    .plan p{margin:8px 0 0;color:var(--muted);font-size:13px}
    .meta{display:flex;justify-content:space-between;align-items:center;margin-top:12px}
    .pill{background:var(--glass);padding:6px 10px;border-radius:10px;font-weight:700;color:var(--muted)}
    /* feed / notices */
    .notice{margin-top:14px;background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(0,0,0,0.02));padding:12px;border-radius:12px;color:var(--muted)}
    /* footer */
    footer{margin-top:22px;padding:18px;text-align:center;color:var(--muted);font-size:13px}
    /* responsive */
    @media (max-width:640px){
      .hero{flex-direction:column;align-items:flex-start}
      .topbar{gap:8px}
      .plans{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="topbar">
      <div class="brand">
        <div class="logo">C</div>
        <div class="userline">
          <strong>স্বাগতম — 186****838</strong>
          <small>ID: 434354 • <span class="vip">VIP 0</span></small>
        </div>
      </div>
      <div style="text-align:right">
        <div style="font-size:13px;color:var(--muted)">মোট সম্পদ</div>
        <div class="big" style="font-size:20px">BDT 2,091.69</div>
      </div>
    </div>

    <div class="hero">
      <div class="bal">
        <h2>আমার ব্যালান্স</h2>
        <div class="big">BDT 2,091.69</div>
        <div class="statsmall">টোটাল ইনভেস্ট: BDT 0.00 • টোটাল রিটার্ন: BDT 0.00</div>

        <div class="cta">
          <a class="btn" href="login.html">লগইন / অ্যাক্সেস</a>
          <a class="btn2" href="deposit.html">ডিপোজিট</a>
          <a class="btn2" href="withdraw.html">উইথড্র</a>
        </div>

        <div class="actions">
          <div class="action">
            <small>দৈনিক আয়</small>
            <b>BDT 0.00</b>
          </div>
          <div class="action">
            <small>রেফার বোনাস</small>
            <b>0.5%</b>
          </div>
          <div class="action">
            <small>টিম আকাস</small>
            <b>3</b>
          </div>
        </div>
      </div>

      <div style="min-width:160px;text-align:center">
        <div style="background:linear-gradient(135deg,#092b5b,#0c5ea8);padding:14px;border-radius:12px">
          <div style="font-size:12px;color:var(--muted)">তোমার ভিআইপি স্তর</div>
          <div style="margin-top:8px;font-weight:800;color:var(--accent);font-size:20px">VIP 0</div>
          <div style="margin-top:8px;color:var(--muted);font-size:12px">পরবর্তী: VIP 1 — BDT 500</div>
        </div>
      </div>
    </div>

    <div class="section-title">
      <h3 style="margin:0;color:var(--accent)">পপুলার প্ল্যান</h3>
      <a class="btn2" href="plans.html">সব প্ল্যান দেখুন</a>
    </div>

    <div class="plans">
      <div class="plan">
        <h3>ইন্টেল 6741P (Small)</h3>
        <p>মূল্য: BDT 10,500 • দৈনিক আয়: BDT 1,260 • মোট আয়: BDT 459,900</p>
        <div class="meta">
          <div class="pill">365 দিন</div>
          <div><a class="btn" href="plans.html#p1">কিনুন</a></div>
        </div>
      </div>

      <div class="plan">
        <h3>ইন্টেল Xeon (Pro)</h3>
        <p>মূল্য: BDT 40,000 • দৈনিক আয়: BDT 1,400 • মোট আয়: BDT 511,000</p>
        <div class="meta">
          <div class="pill">365 দিন</div>
          <div><a class="btn" href="plans.html#p2">কিনুন</a></div>
        </div>
      </div>

      <div class="plan">
        <h3>VIP বেনিফিট</h3>
        <p>রেফার বোনাস, প্রাধান্যভিত্তিক উইথড্র, দ্রুত সাপোর্ট।</p>
        <div class="meta">
          <div class="pill">রেফারঃ 0.5%</div>
          <div><a class="btn" href="profile.html">বিস্তারিত</a></div>
        </div>
      </div>
    </div>

    <div class="notice">
      <strong>নোট:</strong> এই ডেমো সাইটটি টেস্ট/ডিজাইন উদ্দেশ্যে। রিয়েল মানি ট্রান্সফার চালুর আগে লাইসেন্স এবং আইনগত অনুমোদন বাধ্যতামূলক।
    </div>

    <footer>
      © <strong>Cashhuv</strong> — Made by Farhan (Jaan). <br>
      <small style="color:var(--muted)">এই সাইট ডেমো/শিক্ষামূলক — বাস্তব টাকা পরিচালনার পূর্বে আইনগত পরামর্শ নাও।</small>
    </footer>
  </div>
</body>
</html>
