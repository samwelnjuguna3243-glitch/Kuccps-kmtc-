<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KUCCPS KMTC Application</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --navy: #0b1f3a;
    --navy-mid: #132d52;
    --teal: #0e7c7b;
    --teal-light: #12a09e;
    --gold: #c9a84c;
    --gold-light: #e2c06b;
    --cream: #f5f1ea;
    --white: #ffffff;
    --gray-100: #f4f6f9;
    --gray-300: #d0d5dd;
    --gray-500: #667085;
    --gray-700: #344054;
    --red: #c0392b;
    --green: #1a7a4a;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--navy);
    min-height: 100vh;
    font-size: 15px;
  }

  /* HEADER */
  header {
    background: var(--navy);
    color: var(--white);
    padding: 0;
    position: relative;
    overflow: hidden;
  }
  header::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, #0b1f3a 0%, #132d52 60%, #0e7c7b22 100%);
  }
  header::after {
    content: '';
    position: absolute;
    right: -80px; top: -80px;
    width: 380px; height: 380px;
    border-radius: 50%;
    border: 2px solid rgba(201,168,76,0.18);
    pointer-events: none;
  }
  .header-inner {
    position: relative;
    max-width: 860px;
    margin: 0 auto;
    padding: 36px 32px 30px;
    display: flex;
    align-items: center;
    gap: 24px;
  }
  .logo-circle {
    width: 72px; height: 72px;
    border-radius: 50%;
    background: linear-gradient(145deg, var(--gold), var(--gold-light));
    display: flex; align-items: center; justify-content: center;
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 700;
    color: var(--navy);
    flex-shrink: 0;
    box-shadow: 0 4px 18px rgba(201,168,76,0.35);
  }
  .header-text h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1.75rem;
    font-weight: 700;
    line-height: 1.15;
    letter-spacing: -0.3px;
  }
  .header-text p {
    margin-top: 4px;
    color: rgba(255,255,255,0.62);
    font-size: 0.85rem;
    font-weight: 300;
    letter-spacing: 0.5px;
    text-transform: uppercase;
  }
  .gold-bar {
    height: 3px;
    background: linear-gradient(90deg, var(--gold), var(--gold-light) 60%, transparent);
  }

  /* PROGRESS STRIP */
  .progress-strip {
    background: var(--navy-mid);
    padding: 14px 32px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0;
    position: relative;
  }
  .step {
    display: flex; align-items: center; gap: 8px;
    position: relative;
  }
  .step:not(:last-child)::after {
    content: '';
    width: 60px; height: 2px;
    background: rgba(255,255,255,0.15);
    margin: 0 8px;
    display: block;
  }
  .step-num {
    width: 26px; height: 26px;
    border-radius: 50%;
    background: rgba(255,255,255,0.1);
    border: 2px solid rgba(255,255,255,0.2);
    color: rgba(255,255,255,0.45);
    font-size: 11px; font-weight: 600;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.3s;
  }
  .step.active .step-num {
    background: var(--gold);
    border-color: var(--gold);
    color: var(--navy);
  }
  .step.done .step-num {
    background: var(--teal);
    border-color: var(--teal);
    color: white;
  }
  .step-label {
    font-size: 11px; font-weight: 500;
    color: rgba(255,255,255,0.4);
    letter-spacing: 0.4px;
    text-transform: uppercase;
  }
  .step.active .step-label { color: var(--gold-light); }
  .step.done .step-label { color: var(--teal-light); }

  /* MAIN */
  main {
    max-width: 860px;
    margin: 0 auto;
    padding: 40px 20px 60px;
  }

  /* FORM SECTIONS */
  .form-section {
    background: white;
    border-radius: 14px;
    margin-bottom: 20px;
    box-shadow: 0 2px 12px rgba(11,31,58,0.07);
    border: 1px solid rgba(11,31,58,0.06);
    overflow: hidden;
    display: none;
  }
  .form-section.visible { display: block; }

  .section-header {
    background: linear-gradient(135deg, var(--navy) 0%, var(--navy-mid) 100%);
    color: white;
    padding: 18px 28px;
    display: flex; align-items: center; gap: 14px;
  }
  .section-icon {
    width: 38px; height: 38px;
    border-radius: 8px;
    background: rgba(201,168,76,0.18);
    border: 1px solid rgba(201,168,76,0.35);
    display: flex; align-items: center; justify-content: center;
    font-size: 17px;
  }
  .section-header h2 {
    font-family: 'Playfair Display', serif;
    font-size: 1.15rem; font-weight: 600;
  }
  .section-header p {
    font-size: 0.78rem;
    color: rgba(255,255,255,0.55);
    margin-top: 1px;
  }

  .section-body { padding: 28px; }

  /* GRID */
  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; }
  .grid-3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 18px; }
  .col-span-2 { grid-column: span 2; }
  .col-span-3 { grid-column: span 3; }

  /* FIELD */
  .field { display: flex; flex-direction: column; gap: 6px; }
  .field label {
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--gray-700);
    letter-spacing: 0.3px;
    text-transform: uppercase;
  }
  .field label .req { color: var(--red); margin-left: 2px; }

  .field input, .field select, .field textarea {
    width: 100%;
    padding: 10px 14px;
    border: 1.5px solid var(--gray-300);
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    color: var(--navy);
    background: var(--gray-100);
    transition: border-color 0.2s, box-shadow 0.2s, background 0.2s;
    outline: none;
    appearance: none;
    -webkit-appearance: none;
  }
  .field input:focus, .field select:focus, .field textarea:focus {
    border-color: var(--teal);
    box-shadow: 0 0 0 3px rgba(14,124,123,0.12);
    background: white;
  }
  .field select {
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' fill='none'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%23667085' stroke-width='1.5' stroke-linecap='round'/%3E%3C/svg%3E");
    background-repeat: no-repeat;
    background-position: right 14px center;
    padding-right: 36px;
  }
  .field textarea { min-height: 80px; resize: vertical; }
  .field .hint { font-size: 11px; color: var(--gray-500); }
  .field.error input, .field.error select { border-color: var(--red); }
  .field .err-msg { font-size: 11px; color: var(--red); display: none; }
  .field.error .err-msg { display: block; }

  /* RADIO GROUP */
  .radio-group { display: flex; gap: 12px; flex-wrap: wrap; }
  .radio-opt {
    display: flex; align-items: center; gap: 8px;
    padding: 9px 16px;
    border: 1.5px solid var(--gray-300);
    border-radius: 8px;
    cursor: pointer;
    font-size: 13.5px;
    font-weight: 500;
    color: var(--gray-700);
    transition: all 0.18s;
    user-select: none;
    background: var(--gray-100);
  }
  .radio-opt input { display: none; }
  .radio-opt:has(input:checked) {
    border-color: var(--teal);
    background: rgba(14,124,123,0.07);
    color: var(--teal);
  }
  .radio-dot {
    width: 14px; height: 14px;
    border-radius: 50%;
    border: 2px solid currentColor;
    display: flex; align-items: center; justify-content: center;
  }
  .radio-opt:has(input:checked) .radio-dot::after {
    content: '';
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--teal);
  }

  /* DIVIDER */
  .divider {
    border: none;
    border-top: 1px solid #edf0f4;
    margin: 22px 0;
  }

  /* PHOTO UPLOAD */
  .photo-upload {
    display: flex; gap: 20px; align-items: flex-start;
  }
  .photo-preview {
    width: 110px; height: 130px;
    border: 2px dashed var(--gray-300);
    border-radius: 10px;
    background: var(--gray-100);
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    gap: 8px; flex-shrink: 0;
    overflow: hidden;
    position: relative;
    cursor: pointer;
    transition: border-color 0.2s;
  }
  .photo-preview:hover { border-color: var(--teal); }
  .photo-preview img {
    position: absolute; inset: 0;
    width: 100%; height: 100%;
    object-fit: cover;
    display: none;
  }
  .photo-placeholder { text-align: center; color: var(--gray-500); }
  .photo-placeholder span { font-size: 28px; }
  .photo-placeholder p { font-size: 11px; margin-top: 4px; font-weight: 500; }
  .photo-info { flex: 1; }
  .photo-info h4 { font-size: 13px; font-weight: 600; margin-bottom: 6px; color: var(--gray-700); }
  .photo-info ul { font-size: 12px; color: var(--gray-500); padding-left: 16px; line-height: 1.8; }

  /* CHECKBOX */
  .check-label {
    display: flex; align-items: flex-start; gap: 10px;
    cursor: pointer; font-size: 13.5px; color: var(--gray-700);
  }
  .check-label input { width: 16px; height: 16px; accent-color: var(--teal); margin-top: 1px; flex-shrink: 0; }

  /* BUTTONS */
  .btn-row {
    display: flex; gap: 12px; justify-content: flex-end;
    margin-top: 28px; flex-wrap: wrap;
  }
  .btn {
    padding: 11px 28px;
    border-radius: 8px;
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    border: none;
    transition: all 0.18s;
    letter-spacing: 0.2px;
  }
  .btn-outline {
    background: transparent;
    border: 1.5px solid var(--gray-300);
    color: var(--gray-700);
  }
  .btn-outline:hover { border-color: var(--navy); color: var(--navy); }
  .btn-primary {
    background: linear-gradient(135deg, var(--teal) 0%, #0a6665 100%);
    color: white;
    box-shadow: 0 3px 12px rgba(14,124,123,0.3);
  }
  .btn-primary:hover { transform: translateY(-1px); box-shadow: 0 5px 18px rgba(14,124,123,0.38); }
  .btn-primary:active { transform: translateY(0); }
  .btn-gold {
    background: linear-gradient(135deg, var(--gold) 0%, #b8922e 100%);
    color: var(--navy);
    box-shadow: 0 3px 12px rgba(201,168,76,0.35);
  }
  .btn-gold:hover { transform: translateY(-1px); box-shadow: 0 5px 18px rgba(201,168,76,0.42); }

  /* SUCCESS PAGE */
  #success-page {
    display: none;
    text-align: center;
    padding: 70px 20px;
  }
  .success-icon {
    width: 90px; height: 90px;
    border-radius: 50%;
    background: linear-gradient(145deg, var(--teal), var(--teal-light));
    display: flex; align-items: center; justify-content: center;
    margin: 0 auto 24px;
    font-size: 40px;
    box-shadow: 0 8px 28px rgba(14,124,123,0.3);
    animation: popIn 0.5s cubic-bezier(0.34,1.56,0.64,1) both;
  }
  @keyframes popIn {
    from { transform: scale(0.4); opacity: 0; }
    to { transform: scale(1); opacity: 1; }
  }
  #success-page h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    color: var(--navy);
    margin-bottom: 10px;
  }
  #success-page p { color: var(--gray-500); max-width: 420px; margin: 0 auto 10px; line-height: 1.65; }
  .ref-card {
    display: inline-block;
    margin: 22px auto 0;
    background: white;
    border: 1.5px solid var(--gold);
    border-radius: 12px;
    padding: 16px 32px;
    box-shadow: 0 4px 18px rgba(201,168,76,0.15);
  }
  .ref-card p { font-size: 11px; text-transform: uppercase; letter-spacing: 0.5px; color: var(--gray-500); margin: 0; }
  .ref-card h3 { font-family: 'Playfair Display', serif; font-size: 1.6rem; color: var(--navy); margin-top: 4px; letter-spacing: 2px; }

  /* NOTICE BOX */
  .notice {
    background: rgba(14,124,123,0.06);
    border-left: 3px solid var(--teal);
    border-radius: 0 8px 8px 0;
    padding: 12px 16px;
    font-size: 13px;
    color: var(--navy);
    display: flex; gap: 10px; align-items: flex-start;
  }
  .notice .icon { font-size: 16px; flex-shrink: 0; margin-top: 1px; }

  /* FOOTER */
  footer {
    text-align: center;
    padding: 20px;
    color: var(--gray-500);
    font-size: 12px;
    border-top: 1px solid rgba(11,31,58,0.08);
    margin-top: 20px;
  }

  @media (max-width: 640px) {
    .grid-2, .grid-3 { grid-template-columns: 1fr; }
    .col-span-2, .col-span-3 { grid-column: span 1; }
    .header-inner { padding: 24px 20px; }
    .section-body { padding: 20px 16px; }
    .photo-upload { flex-direction: column; }
    .progress-strip { gap: 0; padding: 12px 16px; }
    .step:not(:last-child)::after { width: 30px; }
    .step-label { display: none; }
  }
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="logo-circle">KM</div>
    <div class="header-text">
      <h1>KUCCPS KMTC Application</h1>
      <p>Kenya Universities and Colleges Central Placement Service</p>
    </div>
  </div>
  <div class="gold-bar"></div>
</header>

<div class="progress-strip">
  <div class="step active" id="step-ind-1">
    <div class="step-num">1</div>
    <div class="step-label">Personal Info</div>
  </div>
  <div class="step" id="step-ind-2">
    <div class="step-num">2</div>
    <div class="step-label">Education</div>
  </div>
  <div class="step" id="step-ind-3">
    <div class="step-num">3</div>
    <div class="step-label">Programme</div>
  </div>
  <div class="step" id="step-ind-4">
    <div class="step-num">4</div>
    <div class="step-label">Documents</div>
  </div>
  <div class="step" id="step-ind-5">
    <div class="step-num">5</div>
    <div class="step-label">Payment</div>
  </div>
</div>

<main>
  <form id="reg-form" novalidate>

    <!-- STEP 1: PERSONAL INFORMATION -->
    <div class="form-section visible" id="step-1">
      <div class="section-header">
        <div class="section-icon">👤</div>
        <div>
          <h2>Personal Information</h2>
          <p>Provide your official identification details</p>
        </div>
      </div>
      <div class="section-body">
        <div class="grid-2">
          <div class="field" data-required>
            <label>First Name <span class="req">*</span></label>
            <input type="text" id="first-name" placeholder="e.g. John">
            <span class="err-msg">First name is required</span>
          </div>
          <div class="field" data-required>
            <label>Last Name <span class="req">*</span></label>
            <input type="text" id="last-name" placeholder="e.g. Mwangi">
            <span class="err-msg">Last name is required</span>
          </div>
          <div class="field">
            <label>Middle Name</label>
            <input type="text" id="middle-name" placeholder="Optional">
          </div>
          <div class="field" data-required>
            <label>National ID / Passport No. <span class="req">*</span></label>
            <input type="text" id="id-number" placeholder="e.g. 12345678">
            <span class="err-msg">ID / Passport number is required</span>
          </div>
          <div class="field" data-required>
            <label>Date of Birth <span class="req">*</span></label>
            <input type="date" id="dob">
            <span class="err-msg">Date of birth is required</span>
          </div>
          <div class="field" data-required>
            <label>Gender <span class="req">*</span></label>
            <div class="radio-group" style="margin-top:2px">
              <label class="radio-opt"><input type="radio" name="gender" value="Male"><div class="radio-dot"></div>Male</label>
              <label class="radio-opt"><input type="radio" name="gender" value="Female"><div class="radio-dot"></div>Female</label>
              <label class="radio-opt"><input type="radio" name="gender" value="Other"><div class="radio-dot"></div>Other</label>
            </div>
            <span class="err-msg" id="gender-err" style="display:none; color:var(--red); font-size:11px;">Please select gender</span>
          </div>
        </div>
        <hr class="divider">
        <div class="grid-2">
          <div class="field" data-required>
            <label>Phone Number <span class="req">*</span></label>
            <input type="tel" id="phone" placeholder="+254 7XX XXX XXX">
            <span class="err-msg">Phone number is required</span>
          </div>
          <div class="field" data-required>
            <label>Email Address <span class="req">*</span></label>
            <input type="email" id="email" placeholder="you@example.com">
            <span class="err-msg">Valid email is required</span>
          </div>
          <div class="field" data-required>
            <label>County <span class="req">*</span></label>
            <select id="county">
              <option value="">— Select County —</option>
              <option>Nairobi</option><option>Mombasa</option><option>Kisumu</option>
              <option>Nakuru</option><option>Eldoret / Uasin Gishu</option>
              <option>Kiambu</option><option>Machakos</option><option>Nyeri</option>
              <option>Meru</option><option>Kitui</option><option>Kakamega</option>
              <option>Kilifi</option><option>Bungoma</option><option>Siaya</option>
              <option>Trans Nzoia</option><option>Bomet</option><option>Kericho</option>
              <option>Nandi</option><option>Murang'a</option><option>Kirinyaga</option>
              <option>Embu</option><option>Tharaka-Nithi</option><option>Isiolo</option>
              <option>Marsabit</option><option>Mandera</option><option>Wajir</option>
              <option>Garissa</option><option>Lamu</option><option>Tana River</option>
              <option>Kwale</option><option>Taita-Taveta</option><option>Makueni</option>
              <option>Nyandarua</option><option>Laikipia</option><option>Samburu</option>
              <option>West Pokot</option><option>Turkana</option><option>Baringo</option>
              <option>Elgeyo-Marakwet</option><option>Kajiado</option><option>Narok</option>
              <option>Migori</option><option>Homa Bay</option><option>Kisii</option>
              <option>Nyamira</option><option>Vihiga</option><option>Busia</option>
            </select>
            <span class="err-msg">Please select your county</span>
          </div>
          <div class="field">
            <label>Sub-County / Town</label>
            <input type="text" id="sub-county" placeholder="e.g. Westlands">
          </div>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-primary" onclick="goTo(2)">Continue →</button>
        </div>
      </div>
    </div>

    <!-- STEP 2: EDUCATION BACKGROUND -->
    <div class="form-section" id="step-2">
      <div class="section-header">
        <div class="section-icon">📚</div>
        <div>
          <h2>Education Background</h2>
          <p>Your academic history and qualifications</p>
        </div>
      </div>
      <div class="section-body">
        <div class="grid-2">
          <div class="field" data-required>
            <label>KCSE Index Number <span class="req">*</span></label>
            <input type="text" id="kcse-index" placeholder="e.g. 40101234000">
            <span class="err-msg">KCSE index number is required</span>
          </div>
          <div class="field" data-required>
            <label>KCSE Year <span class="req">*</span></label>
            <select id="kcse-year">
              <option value="">— Year —</option>
              <option>2024</option><option>2023</option><option>2022</option>
              <option>2021</option><option>2020</option><option>2019</option>
              <option>2018</option><option>2017</option><option>2016</option>
              <option>2015 or earlier</option>
            </select>
            <span class="err-msg">Please select KCSE year</span>
          </div>
          <div class="field" data-required>
            <label>KCSE Overall Grade <span class="req">*</span></label>
            <select id="kcse-grade">
              <option value="">— Grade —</option>
              <option>A (Plain)</option><option>A-</option><option>B+</option>
              <option>B (Plain)</option><option>B-</option><option>C+</option>
              <option>C (Plain)</option><option>C-</option><option>D+</option>
              <option>D (Plain)</option><option>D-</option>
            </select>
            <span class="err-msg">Please select your overall KCSE grade</span>
          </div>
          <div class="field">
            <label>Biology Grade</label>
            <select id="bio-grade">
              <option value="">— Grade —</option>
              <option>A</option><option>A-</option><option>B+</option>
              <option>B</option><option>B-</option><option>C+</option>
              <option>C</option><option>C-</option><option>D+</option>
              <option>D</option><option>D-</option>
            </select>
          </div>
          <div class="field">
            <label>Chemistry Grade</label>
            <select id="chem-grade">
              <option value="">— Grade —</option>
              <option>A</option><option>A-</option><option>B+</option>
              <option>B</option><option>B-</option><option>C+</option>
              <option>C</option><option>C-</option><option>D+</option>
              <option>D</option><option>D-</option>
            </select>
          </div>
          <div class="field">
            <label>Mathematics Grade</label>
            <select id="math-grade">
              <option value="">— Grade —</option>
              <option>A</option><option>A-</option><option>B+</option>
              <option>B</option><option>B-</option><option>C+</option>
              <option>C</option><option>C-</option><option>D+</option>
              <option>D</option><option>D-</option>
            </select>
          </div>
        </div>
        <hr class="divider">
        <div class="field">
          <label>Secondary School Name <span class="req">*</span></label>
          <input type="text" id="school-name" placeholder="Full name of your secondary school" required>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-outline" onclick="goTo(1)">← Back</button>
          <button type="button" class="btn btn-primary" onclick="goTo(3)">Continue →</button>
        </div>
      </div>
    </div>

    <!-- STEP 3: PROGRAMME SELECTION -->
    <div class="form-section" id="step-3">
      <div class="section-header">
        <div class="section-icon">🏥</div>
        <div>
          <h2>Programme Selection</h2>
          <p>Choose your preferred KMTC programmes and campus</p>
        </div>
      </div>
      <div class="section-body">
        <div class="notice" style="margin-bottom:20px">
          <span class="icon">ℹ️</span>
          <span>You may select up to <strong>3 programme preferences</strong> in order of priority. You will be placed based on your qualifications and available slots.</span>
        </div>
        <div class="grid-3">
          <div class="field" data-required>
            <label>1st Choice Programme <span class="req">*</span></label>
            <select id="prog-1">
              <option value="">— Select Programme —</option>
              <optgroup label="Clinical">
                <option>Clinical Medicine</option>
                <option>Community Health</option>
              </optgroup>
              <optgroup label="Nursing">
                <option>Kenya Registered Nursing</option>
                <option>Kenya Registered Community Health Nursing</option>
                <option>Kenya Registered Midwifery</option>
              </optgroup>
              <optgroup label="Pharmacy">
                <option>Pharmaceutical Technology</option>
              </optgroup>
              <optgroup label="Allied Health">
                <option>Medical Laboratory Sciences</option>
                <option>Diagnostic Radiography</option>
                <option>Physiotherapy</option>
                <option>Occupational Therapy</option>
                <option>Orthopaedic Technology</option>
                <option>Nutrition & Dietetics</option>
                <option>Environmental Health</option>
                <option>Health Records & Information Management</option>
                <option>Dental Technology</option>
                <option>Optometry</option>
                <option>Medical Engineering</option>
                <option>Prosthetics and Orthotics</option>
              </optgroup>
            </select>
            <span class="err-msg">Please select your first choice</span>
          </div>
          <div class="field">
            <label>2nd Choice Programme</label>
            <select id="prog-2">
              <option value="">— Optional —</option>
              <optgroup label="Clinical">
                <option>Clinical Medicine</option>
                <option>Community Health</option>
              </optgroup>
              <optgroup label="Nursing">
                <option>Kenya Registered Nursing</option>
                <option>Kenya Registered Community Health Nursing</option>
                <option>Kenya Registered Midwifery</option>
              </optgroup>
              <optgroup label="Pharmacy">
                <option>Pharmaceutical Technology</option>
              </optgroup>
              <optgroup label="Allied Health">
                <option>Medical Laboratory Sciences</option>
                <option>Diagnostic Radiography</option>
                <option>Physiotherapy</option>
                <option>Occupational Therapy</option>
                <option>Orthopaedic Technology</option>
                <option>Nutrition & Dietetics</option>
                <option>Environmental Health</option>
                <option>Health Records & Information Management</option>
                <option>Dental Technology</option>
                <option>Optometry</option>
                <option>Medical Engineering</option>
                <option>Prosthetics and Orthotics</option>
              </optgroup>
            </select>
          </div>
          <div class="field">
            <label>3rd Choice Programme</label>
            <select id="prog-3">
              <option value="">— Optional —</option>
              <optgroup label="Clinical">
                <option>Clinical Medicine</option>
                <option>Community Health</option>
              </optgroup>
              <optgroup label="Nursing">
                <option>Kenya Registered Nursing</option>
                <option>Kenya Registered Community Health Nursing</option>
                <option>Kenya Registered Midwifery</option>
              </optgroup>
              <optgroup label="Pharmacy">
                <option>Pharmaceutical Technology</option>
              </optgroup>
              <optgroup label="Allied Health">
                <option>Medical Laboratory Sciences</option>
                <option>Diagnostic Radiography</option>
                <option>Physiotherapy</option>
                <option>Occupational Therapy</option>
                <option>Orthopaedic Technology</option>
                <option>Nutrition & Dietetics</option>
                <option>Environmental Health</option>
                <option>Health Records & Information Management</option>
                <option>Dental Technology</option>
                <option>Optometry</option>
                <option>Medical Engineering</option>
                <option>Prosthetics and Orthotics</option>
              </optgroup>
            </select>
          </div>
        </div>
        <hr class="divider">
        <div class="grid-2">
          <div class="field" data-required>
            <label>Preferred Campus <span class="req">*</span></label>
            <select id="campus">
              <option value="">— Select Campus —</option>
              <option>Nairobi</option><option>Mombasa</option><option>Kisumu</option>
              <option>Nakuru</option><option>Eldoret</option><option>Kakkakamega</option>
              <option>Nyeri</option><option>Embu</option><option>Meru</option>
              <option>Kitui</option><option>Machakos</option><option>Muranga</option>
              <option>Thika</option><option>Kiambu</option><option>Garissa</option>
              <option>Wajir</option><option>Mandera</option><option>Marsabit</option>
              <option>Isiolo</option><option>Turkana</option><option>Samburu</option>
              <option>Bomet</option><option>Kilifi</option><option>Malindi</option>
            </select>
            <span class="err-msg">Please select your preferred campus</span>
          </div>
          <div class="field">
            <label>Disability / Special Needs</label>
            <select id="disability">
              <option value="None">None</option>
              <option>Visual Impairment</option>
              <option>Hearing Impairment</option>
              <option>Physical Disability</option>
              <option>Other</option>
            </select>
            <span class="hint">We ensure equal opportunity for all applicants</span>
          </div>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-outline" onclick="goTo(2)">← Back</button>
          <button type="button" class="btn btn-primary" onclick="goTo(4)">Continue →</button>
        </div>
      </div>
    </div>

    <!-- STEP 4: DOCUMENTS & DECLARATION -->
    <div class="form-section" id="step-4">
      <div class="section-header">
        <div class="section-icon">📋</div>
        <div>
          <h2>Documents & Declaration</h2>
          <p>Upload your photo and confirm your details</p>
        </div>
      </div>
      <div class="section-body">
        <div class="photo-upload">
          <div class="photo-preview" onclick="document.getElementById('photo-input').click()" id="photo-preview">
            <img id="photo-img" src="" alt="">
            <div class="photo-placeholder">
              <span>📷</span>
              <p>Click to upload</p>
            </div>
          </div>
          <div class="photo-info">
            <h4>Passport-Size Photograph</h4>
            <ul>
              <li>Recent photo (not older than 6 months)</li>
              <li>Plain white or light blue background</li>
              <li>Face clearly visible, no hats or sunglasses</li>
              <li>File format: JPG or PNG, max 2MB</li>
            </ul>
          </div>
        </div>
        <input type="file" id="photo-input" accept="image/*" style="display:none" onchange="handlePhoto(event)">

        <hr class="divider">
        <h4 style="font-size:13px; font-weight:600; color:var(--gray-700); margin-bottom:14px; text-transform:uppercase; letter-spacing:0.4px;">Emergency Contact</h4>
        <div class="grid-2">
          <div class="field">
            <label>Contact Person Name</label>
            <input type="text" id="emer-name" placeholder="Full name">
          </div>
          <div class="field">
            <label>Relationship</label>
            <select id="emer-rel">
              <option value="">— Select —</option>
              <option>Parent</option><option>Sibling</option><option>Spouse</option>
              <option>Guardian</option><option>Other</option>
            </select>
          </div>
          <div class="field col-span-2">
            <label>Contact Phone</label>
            <input type="tel" id="emer-phone" placeholder="+254 7XX XXX XXX">
          </div>
        </div>

        <hr class="divider">
        <div style="display:flex; flex-direction:column; gap:12px">
          <label class="check-label">
            <input type="checkbox" id="check-accurate">
            I confirm that all information provided in this application is true, accurate, and complete. I understand that providing false information may result in disqualification.
          </label>
          <label class="check-label">
            <input type="checkbox" id="check-terms">
            I have read and agree to the <a href="#" style="color:var(--teal)">Terms & Conditions</a> of KMTC application and admission process.
          </label>
        </div>

        <div class="btn-row">
          <button type="button" class="btn btn-outline" onclick="goTo(3)">← Back</button>
          <button type="button" class="btn btn-primary" onclick="goTo(5)">Continue to Payment →</button>
        </div>
      </div>
    </div>

    <!-- STEP 5: PAYMENT -->
    <div class="form-section" id="step-5">
      <div class="section-header">
        <div class="section-icon">💳</div>
        <div>
          <h2>Application Fee Payment</h2>
          <p>Pay via M-Pesa and submit your transaction confirmation</p>
        </div>
      </div>
      <div class="section-body">

        <div style="background:linear-gradient(135deg,#0b1f3a 0%,#0e4d3d 100%);border-radius:14px;padding:28px;color:white;margin-bottom:24px;position:relative;overflow:hidden;">
          <div style="position:absolute;right:-30px;top:-30px;width:160px;height:160px;border-radius:50%;background:rgba(255,255,255,0.04);"></div>
          <div style="display:flex;align-items:center;gap:10px;margin-bottom:20px;">
            <span style="font-size:28px;">📱</span>
            <div>
              <p style="font-size:11px;text-transform:uppercase;letter-spacing:0.6px;color:rgba(255,255,255,0.5);margin-bottom:2px;">M-Pesa Payment Instructions</p>
              <h3 style="font-family:'Playfair Display',serif;font-size:1.1rem;">How to Pay</h3>
            </div>
          </div>
          <ol style="padding-left:20px;line-height:2.4;font-size:14px;color:rgba(255,255,255,0.85);">
            <li>Go to <strong>M-Pesa</strong> on your phone</li>
            <li>Select <strong>Lipa na M-Pesa → Pay Bill</strong></li>
            <li>Enter Business Number: <span style="background:rgba(201,168,76,0.22);border:1px solid rgba(201,168,76,0.4);border-radius:6px;padding:2px 10px;font-weight:700;color:#e2c06b;font-size:16px;letter-spacing:1px;">3059051</span></li>
            <li>Account Number: <strong>Your National ID / Passport Number</strong></li>
            <li>Amount: <span style="background:rgba(14,124,123,0.3);border:1px solid rgba(14,124,123,0.5);border-radius:6px;padding:2px 10px;font-weight:700;color:#5de0df;font-size:16px;">KSh 2,000</span></li>
            <li>Enter your M-Pesa PIN and confirm</li>
          </ol>
          <div style="margin-top:18px;padding:12px 16px;background:rgba(201,168,76,0.12);border:1px solid rgba(201,168,76,0.25);border-radius:8px;font-size:12.5px;color:rgba(255,255,255,0.75);display:flex;gap:10px;align-items:flex-start;">
            <span style="font-size:15px;flex-shrink:0;">⚠️</span>
            <span>You will receive an <strong style="color:white;">M-Pesa SMS</strong> after payment. Copy and paste that entire message in the field below before submitting.</span>
          </div>
        </div>

        <!-- Quick Reference Tiles -->
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:24px;">
          <div style="background:white;border:1.5px solid #d0d5dd;border-radius:10px;padding:16px;text-align:center;">
            <p style="font-size:11px;text-transform:uppercase;letter-spacing:0.4px;color:#667085;margin-bottom:6px;">Paybill Number</p>
            <p style="font-size:2rem;font-family:'Playfair Display',serif;font-weight:700;color:#0b1f3a;letter-spacing:2px;">3059051</p>
          </div>
          <div style="background:white;border:1.5px solid #d0d5dd;border-radius:10px;padding:16px;text-align:center;">
            <p style="font-size:11px;text-transform:uppercase;letter-spacing:0.4px;color:#667085;margin-bottom:6px;">Application Fee</p>
            <p style="font-size:2rem;font-family:'Playfair Display',serif;font-weight:700;color:#0e7c7b;letter-spacing:1px;">KSh 2,000</p>
          </div>
        </div>

        <!-- Transaction Message -->
        <div class="field" id="mpesa-field" data-required>
          <label>M-Pesa Transaction Message <span class="req">*</span></label>
          <textarea id="mpesa-msg" rows="6" placeholder="Paste your M-Pesa confirmation SMS here...&#10;&#10;Example:&#10;RK5X2YZ1AB Confirmed. Ksh2,000.00 paid to KMTC APPLICATIONS 3059051 on 2/4/25 at 10:23 AM. New M-PESA balance is Ksh3,450.00."></textarea>
          <span class="err-msg">Please paste your M-Pesa confirmation message</span>
        </div>

        <div id="txn-preview" style="display:none;margin-top:12px;background:#f0faf9;border:1.5px solid #0e7c7b;border-radius:10px;padding:14px 18px;">
          <p style="font-size:11px;text-transform:uppercase;letter-spacing:0.4px;color:#0e7c7b;font-weight:600;margin-bottom:8px;">✅ Transaction Detected</p>
          <div style="display:flex;gap:24px;flex-wrap:wrap;">
            <div><span style="font-size:11px;color:#667085;">Transaction Code</span><br><strong id="txn-code" style="font-size:15px;color:#0b1f3a;letter-spacing:1.5px;"></strong></div>
            <div><span style="font-size:11px;color:#667085;">Amount Paid</span><br><strong id="txn-amount" style="font-size:15px;color:#0e7c7b;"></strong></div>
          </div>
        </div>

        <hr class="divider">

        <div class="btn-row">
          <button type="button" class="btn btn-outline" onclick="goTo(4)">← Back</button>
          <button type="button" class="btn btn-gold" onclick="submitForm()">✓ Submit Application</button>
        </div>
      </div>
    </div>

  </form>

  <!-- SUCCESS -->
  <div id="success-page">
    <div class="success-icon">✓</div>
    <h2>Application Submitted!</h2>
    <p>Your KMTC application has been successfully registered. Please save your reference number for tracking.</p>
    <div class="ref-card">
      <p>Application Reference Number</p>
      <h3 id="ref-number">KMTC-2024-000000</h3>
    </div>
    <p style="margin-top:22px; font-size:13px">You will receive a confirmation SMS and email within 24 hours.<br>Keep this reference number for follow-up.</p>
    <div class="btn-row" style="justify-content:center; margin-top:28px">
      <button class="btn btn-outline" onclick="printPage()">🖨 Print Confirmation</button>
      <button class="btn btn-primary" onclick="resetForm()">Register Another</button>
    </div>
  </div>
</main>

<footer>
  &copy; 2024 Kenya Medical Training College &nbsp;|&nbsp; Ministry of Health, Kenya &nbsp;|&nbsp; For technical support: itsupport@kmtc.ac.ke
</footer>

<script>
  let currentStep = 1;

  function goTo(step) {
    if (step > currentStep && !validateStep(currentStep)) return;

    document.getElementById(`step-${currentStep}`).classList.remove('visible');
    document.getElementById(`step-ind-${currentStep}`).classList.remove('active');
    document.getElementById(`step-ind-${currentStep}`).classList.add('done');

    if (step < currentStep) {
      // going back — un-done the current step ind
      document.getElementById(`step-ind-${currentStep}`).classList.remove('done');
      if (step < currentStep) {
        document.getElementById(`step-ind-${step}`).classList.remove('done');
      }
    }

    currentStep = step;
    document.getElementById(`step-${currentStep}`).classList.add('visible');
    document.getElementById(`step-ind-${currentStep}`).classList.remove('done');
    document.getElementById(`step-ind-${currentStep}`).classList.add('active');

    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function validateStep(step) {
    let valid = true;

    if (step === 1) {
      ['first-name','last-name','id-number','dob','phone','email','county'].forEach(id => {
        const el = document.getElementById(id);
        const field = el.closest('.field');
        if (!el.value.trim()) {
          field.classList.add('error');
          valid = false;
        } else {
          field.classList.remove('error');
        }
      });
      // email format
      const email = document.getElementById('email');
      if (email.value && !/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email.value)) {
        email.closest('.field').classList.add('error');
        valid = false;
      }
      // gender
      if (!document.querySelector('input[name="gender"]:checked')) {
        document.getElementById('gender-err').style.display = 'block';
        valid = false;
      } else {
        document.getElementById('gender-err').style.display = 'none';
      }
    }

    if (step === 2) {
      ['kcse-index','kcse-year','kcse-grade'].forEach(id => {
        const el = document.getElementById(id);
        const field = el.closest('.field');
        if (!el.value.trim()) {
          field.classList.add('error'); valid = false;
        } else {
          field.classList.remove('error');
        }
      });
    }

    if (step === 3) {
      ['prog-1','campus'].forEach(id => {
        const el = document.getElementById(id);
        const field = el.closest('.field');
        if (!el.value) {
          field.classList.add('error'); valid = false;
        } else {
          field.classList.remove('error');
        }
      });
    }

    if (step === 5) {
      const msg = document.getElementById('mpesa-msg').value.trim();
      const field = document.getElementById('mpesa-field');
      if (!msg) {
        field.classList.add('error'); valid = false;
      } else {
        field.classList.remove('error');
      }
    }

    return valid;
  }

  function submitForm() {
    if (!document.getElementById('check-accurate').checked) {
      alert('Please confirm that all information is accurate before submitting.');
      return;
    }
    if (!document.getElementById('check-terms').checked) {
      alert('Please agree to the Terms & Conditions to continue.');
      return;
    }

    // Generate reference number
    const year = new Date().getFullYear();
    const rand = Math.floor(100000 + Math.random() * 900000);
    document.getElementById('ref-number').textContent = `KMTC-${year}-${rand}`;

    document.getElementById('reg-form').style.display = 'none';
    document.querySelector('.progress-strip').style.display = 'none';
    document.getElementById('success-page').style.display = 'block';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function handlePhoto(e) {
    const file = e.target.files[0];
    if (!file) return;
    const reader = new FileReader();
    reader.onload = ev => {
      const img = document.getElementById('photo-img');
      img.src = ev.target.result;
      img.style.display = 'block';
      document.querySelector('.photo-placeholder').style.display = 'none';
    };
    reader.readAsDataURL(file);
  }

  function printPage() {
    window.print();
  }

  function resetForm() {
    document.getElementById('reg-form').reset();
    document.getElementById('reg-form').style.display = 'block';
    document.querySelector('.progress-strip').style.display = 'flex';
    document.getElementById('success-page').style.display = 'none';

    // Reset steps
    for (let i = 1; i <= 5; i++) {
      document.getElementById(`step-${i}`).classList.remove('visible');
      document.getElementById(`step-ind-${i}`).classList.remove('active','done');
    }
    currentStep = 1;
    document.getElementById('step-1').classList.add('visible');
    document.getElementById('step-ind-1').classList.add('active');

    document.getElementById('photo-img').style.display = 'none';
    document.querySelector('.photo-placeholder').style.display = 'flex';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // M-Pesa message parser
  document.getElementById('mpesa-msg').addEventListener('input', function() {
    const text = this.value;
    // Extract transaction code (e.g. RK5X2YZ1AB)
    const codeMatch = text.match(/^([A-Z0-9]{10})\s/m) || text.match(/([A-Z0-9]{10})\s+Confirmed/i);
    // Extract amount
    const amountMatch = text.match(/Ksh\s*([\d,]+\.?\d*)/i);
    const preview = document.getElementById('txn-preview');
    if (codeMatch && amountMatch) {
      document.getElementById('txn-code').textContent = codeMatch[1];
      document.getElementById('txn-amount').textContent = 'KSh ' + amountMatch[1];
      preview.style.display = 'block';
    } else {
      preview.style.display = 'none';
    }
    document.getElementById('mpesa-field').classList.remove('error');
  });

  // Live validation on blur
  document.querySelectorAll('input, select').forEach(el => {
    el.addEventListener('blur', () => {
      const field = el.closest('.field');
      if (field && field.hasAttribute('data-required') && !el.value.trim()) {
        field.classList.add('error');
      } else if (field) {
        field.classList.remove('error');
      }
    });
    el.addEventListener('input', () => {
      el.closest('.field')?.classList.remove('error');
    });
  });
</script>

</body>
</html>
