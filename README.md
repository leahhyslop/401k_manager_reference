[401k_manager_reference.html](https://github.com/user-attachments/files/28812094/401k_manager_reference.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>401(k) Manager Reference — Jetson</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Inter', sans-serif;
    background: #F7F6F2;
    color: #1A1A18;
    font-size: 15px;
    line-height: 1.6;
    min-height: 100vh;
  }

  .header {
    background: #1A1A18;
    color: #F7F6F2;
    padding: 2.5rem 2rem 2rem;
  }

  .header-inner {
    max-width: 820px;
    margin: 0 auto;
  }

  .header-eyebrow {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #8ABA47;
    margin-bottom: 0.5rem;
  }

  .header h1 {
    font-size: 26px;
    font-weight: 600;
    line-height: 1.25;
    margin-bottom: 0.5rem;
  }

  .header p {
    font-size: 14px;
    color: #A8A89E;
  }

  .main {
    max-width: 820px;
    margin: 0 auto;
    padding: 2rem;
  }

  .card {
    background: #fff;
    border: 1px solid #E5E4DF;
    border-radius: 10px;
    padding: 1.5rem;
    margin-bottom: 1.25rem;
  }

  .card-label {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #8ABA47;
    margin-bottom: 1rem;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 13.5px;
  }

  thead th {
    text-align: left;
    font-weight: 500;
    color: #777770;
    padding: 6px 10px;
    border-bottom: 1px solid #E5E4DF;
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 0.04em;
  }

  tbody td {
    padding: 10px 10px;
    border-bottom: 1px solid #F0EFE9;
    vertical-align: top;
    color: #1A1A18;
  }

  tbody tr:last-child td { border-bottom: none; }

  .tag {
    display: inline-block;
    font-size: 11px;
    font-weight: 600;
    padding: 3px 9px;
    border-radius: 20px;
    margin-bottom: 4px;
  }

  .tag-new { background: #EAF4D3; color: #3B6D11; }
  .tag-existing { background: #DFF0FB; color: #185FA5; }

  .sub { font-size: 11.5px; color: #888882; margin-top: 2px; }

  .faq-item { margin-bottom: 1.25rem; }
  .faq-item:last-child { margin-bottom: 0; }

  .faq-q {
    font-weight: 500;
    font-size: 14px;
    margin-bottom: 0.3rem;
    color: #1A1A18;
  }

  .faq-a {
    font-size: 13.5px;
    color: #444440;
    line-height: 1.6;
  }

  .doc-links {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 0.25rem;
  }

  .doc-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 13px;
    color: #185FA5;
    text-decoration: none;
    background: #F0F7FD;
    border: 1px solid #C6DDEF;
    border-radius: 6px;
    padding: 6px 12px;
    transition: background 0.15s;
  }

  .doc-link:hover { background: #DFF0FB; }

  .doc-link svg {
    width: 14px;
    height: 14px;
    flex-shrink: 0;
  }

  .notion-links {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .notion-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 13px;
    color: #1A1A18;
    text-decoration: none;
    background: #F7F6F2;
    border: 1px solid #E5E4DF;
    border-radius: 6px;
    padding: 8px 14px;
    font-weight: 500;
    transition: background 0.15s;
  }

  .notion-link:hover { background: #EDECEA; }

  .callout {
    background: #F7F6F2;
    border-left: 3px solid #8ABA47;
    padding: 0.9rem 1.1rem;
    border-radius: 0 6px 6px 0;
    font-size: 13.5px;
    color: #444440;
    margin-top: 0.75rem;
  }

  .callout strong { color: #1A1A18; }

  .contact-pill {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: #EAF4D3;
    color: #3B6D11;
    border-radius: 20px;
    padding: 4px 12px;
    font-size: 13px;
    font-weight: 500;
  }

  .footer {
    max-width: 820px;
    margin: 0 auto;
    padding: 0 2rem 3rem;
    font-size: 12px;
    color: #AAAA9E;
  }

  @media (max-width: 600px) {
    .main { padding: 1.25rem; }
    .header { padding: 1.75rem 1.25rem 1.5rem; }
    table { font-size: 12.5px; }
    thead th { font-size: 11px; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="header-inner">
    <div class="header-eyebrow">Jetson — HR Reference</div>
    <h1>401(k) Plan — Manager Quick Reference</h1>
    <p>Use this page when employees come to you with questions about the 401(k) plan.</p>
  </div>
</div>

<div class="main">

  <!-- At a glance -->
  <div class="card">
    <div class="card-label">At a glance</div>
    <table>
      <thead>
        <tr>
          <th>Employee group</th>
          <th>Eligibility</th>
          <th>Deadline to opt out / make changes</th>
          <th>Auto-enroll rate</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <span class="tag tag-new">New hires</span>
            <div class="sub">Started after June 1, 2026</div>
          </td>
          <td>After 90 days of employment</td>
          <td>30 days from eligibility date</td>
          <td>3% of pay</td>
        </tr>
        <tr>
          <td>
            <span class="tag tag-existing">Existing employees</span>
            <div class="sub">Started before June 1, 2026</div>
          </td>
          <td>Already eligible</td>
          <td>August 1, 2026</td>
          <td>3% of pay</td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- New hire timeline -->
  <div class="card">
    <div class="card-label"><span class="tag tag-new" style="margin-right:6px;">New hires</span> Timeline</div>
    <table>
      <thead>
        <tr><th>Milestone</th><th>When</th></tr>
      </thead>
      <tbody>
        <tr><td>Enrollment info sent</td><td>After their first pay with ADP</td></tr>
        <tr><td>Eligibility letter &amp; login credentials</td><td>30 days before their eligibility date (90-day mark)</td></tr>
        <tr><td>Window to opt out or make changes</td><td>30 days from eligibility date</td></tr>
        <tr><td>Auto-enrollment takes effect</td><td>If no action taken after the 30-day window</td></tr>
      </tbody>
    </table>
  </div>

  <!-- Existing employee timeline -->
  <div class="card">
    <div class="card-label"><span class="tag tag-existing" style="margin-right:6px;">Existing employees</span> Timeline</div>
    <table>
      <thead>
        <tr><th>Milestone</th><th>When</th></tr>
      </thead>
      <tbody>
        <tr><td>Enrollment info sent</td><td>After first pay in June — mailed to home address</td></tr>
        <tr><td>Window to opt out or make changes</td><td>Until August 1, 2026</td></tr>
        <tr><td>Auto-enrollment takes effect</td><td>If no action taken by August 1, 2026</td></tr>
      </tbody>
    </table>
  </div>

  <!-- FAQs -->
  <div class="card">
    <div class="card-label">Common employee questions</div>

    <div class="faq-item">
      <div class="faq-q">Will I be automatically enrolled?</div>
      <div class="faq-a">Yes — if no action is taken, employees are enrolled at 3% of their pay. They must actively opt out before their deadline.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">When will I get my enrollment info?</div>
      <div class="faq-a">New hires receive their information after their first ADP pay. Existing employees received (or will receive) their letter by mail to their home address.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">How do I opt out or change my contribution rate?</div>
      <div class="faq-a">Employees log into the Plan Resource Center using the credentials in their eligibility letter. If they haven't received their letter yet, they should watch for it by mail.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">What if I missed the deadline?</div>
      <div class="faq-a">Direct them to HR — Sophia is the point of contact.</div>
    </div>

    <div class="callout">
      <strong>Notices:</strong> Initial notices are mailed to the employee's home address. All future notices are sent by email. Remind employees to keep their mailing address and email on file up to date.
    </div>
  </div>

  <!-- Key documents -->
  <div class="card">
    <div class="card-label">Key documents</div>
    <div class="doc-links">
      <a class="doc-link" href="https://cms.adpretirementmarketing.com/asset/pdf/99-6054-P_Enrollment_Tools_Flyer.pdf/955/" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
        Enrollment flyer
      </a>
      <a class="doc-link" href="https://cms.adpretirementmarketing.com/asset/pdf/99-6301-P_Auto_Enroll_New_Plans.pdf/401/" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
        Auto-enroll guide
      </a>
      <a class="doc-link" href="https://pod.spire.net/adprs/CustomPdfPreviewADP.aspx?urlkey=59a5f326-4a00-4d05-8ac0-556f644c95d7" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/></svg>
        Plan document
      </a>
    </div>
  </div>

  <!-- Notion pages -->
  <div class="card">
    <div class="card-label">Full employee Notion pages</div>
    <div class="notion-links">
      <a class="notion-link" href="https://app.notion.com/p/36fe76c43c5181f6b4f0c5363652136f" target="_blank">
        🌱 New hires (post June 1, 2026)
      </a>
      <a class="notion-link" href="https://app.notion.com/p/36fe76c43c51810ba988c43e752f9475" target="_blank">
        💰 Existing employees (pre-June 1, 2026)
      </a>
    </div>
  </div>

  <!-- Contact -->
  <div class="card">
    <div class="card-label">Questions? Contact HR</div>
    <p style="font-size:13.5px; color:#444440; margin-bottom:0.75rem;">For anything beyond this guide, direct employees (or yourself) to:</p>
    <span class="contact-pill">Sophia — HR</span>
  </div>

</div>

<div class="footer">
  For internal use only. Last updated June 2026.
</div>

</body>
</html>
