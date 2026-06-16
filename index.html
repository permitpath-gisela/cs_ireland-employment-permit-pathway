<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSEP Workflow | PermitPath</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: #f5f3f0;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 50px;
        }

        .logo-section {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 15px;
        }

        .logo-box {
            width: 50px;
            height: 50px;
            background: #26585E;
            border-radius: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #CAA679;
            font-size: 32px;
            font-weight: 700;
        }

        .header h1 {
            font-size: 32px;
            color: #26585E;
            font-weight: 700;
        }

        .header p {
            color: #CAA679;
            font-size: 14px;
            letter-spacing: 1px;
            margin-top: 5px;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
        }

        /* WORKFLOW GRID */
        .workflow {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px;
            margin-bottom: 60px;
            flex-wrap: wrap;
        }

        .phase {
            flex: 1;
            min-width: 200px;
            position: relative;
        }

        /* Arrow between phases */
        .phase::after {
            content: '';
            position: absolute;
            right: -30px;
            top: 80px;
            width: 30px;
            height: 3px;
            background: #CAA679;
        }

        .phase:last-child::after {
            display: none;
        }

        /* Phase card */
        .phase-card {
            background: white;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(38,88,94,0.08);
            border: 2px solid transparent;
            transition: all 0.3s;
            position: relative;
            min-height: 280px;
            display: flex;
            flex-direction: column;
        }

        .phase-card:hover {
            border-color: #CAA679;
            box-shadow: 0 4px 16px rgba(38,88,94,0.15);
        }

        /* Phase number circle */
        .phase-num {
            width: 50px;
            height: 50px;
            background: #26585E;
            color: #CAA679;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            font-weight: 700;
            margin: 0 auto 15px;
        }

        .phase-title {
            font-size: 16px;
            font-weight: 700;
            color: #26585E;
            margin-bottom: 8px;
        }

        .phase-duration {
            font-size: 11px;
            color: #999;
            margin-bottom: 15px;
            padding: 8px;
            background: #EFECE5;
            border-radius: 4px;
        }

        .phase-tasks {
            flex-grow: 1;
            font-size: 12px;
            color: #666;
            line-height: 1.5;
            margin-bottom: 15px;
            text-align: left;
        }

        .phase-tasks li {
            margin-left: 15px;
            margin-bottom: 6px;
        }

        /* PermitPath badge */
        .permitpath-badge {
            background: linear-gradient(135deg, rgba(38,88,94,0.05), rgba(202,166,121,0.1));
            border: 1px solid #CAA679;
            padding: 10px;
            border-radius: 4px;
            font-size: 11px;
            color: #26585E;
            font-weight: 600;
            margin-top: auto;
        }

        .permitpath-badge strong {
            color: #26585E;
            display: block;
            margin-bottom: 5px;
        }

        /* MOBILE RESPONSIVE */
        @media (max-width: 1200px) {
            .phase::after {
                display: none;
            }

            .workflow {
                flex-direction: column;
                gap: 30px;
            }

            .phase {
                width: 100%;
            }

            .phase-card {
                min-height: auto;
            }
        }

        /* SECTION DIVIDERS */
        .section {
            margin-bottom: 80px;
        }

        .section-title {
            font-size: 20px;
            font-weight: 700;
            color: #26585E;
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 15px;
            border-bottom: 3px solid #CAA679;
        }

        /* KEY REQUIREMENTS */
        .requirements {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .req-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(38,88,94,0.08);
            border-top: 4px solid #CAA679;
        }

        .req-icon {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .req-card h4 {
            font-size: 13px;
            font-weight: 700;
            color: #26585E;
            margin-bottom: 8px;
        }

        .req-card p {
            font-size: 11px;
            color: #666;
            line-height: 1.5;
        }

        /* STATS SECTION */
        .stats {
            background: linear-gradient(135deg, #26585E 0%, #1A3F45 100%);
            padding: 40px;
            border-radius: 8px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 30px;
            text-align: center;
            margin-bottom: 40px;
        }

        .stat {
            color: white;
        }

        .stat-number {
            font-size: 36px;
            font-weight: 700;
            color: #CAA679;
        }

        .stat-label {
            font-size: 12px;
            color: #DDD;
            margin-top: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* CTA */
        .cta-section {
            background: white;
            padding: 40px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(38,88,94,0.1);
            border: 2px solid #CAA679;
        }

        .cta-section h2 {
            font-size: 24px;
            color: #26585E;
            font-weight: 700;
            margin-bottom: 15px;
        }

        .cta-section p {
            font-size: 13px;
            color: #666;
            margin-bottom: 20px;
        }

        .cta-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 28px;
            border: none;
            border-radius: 4px;
            font-size: 13px;
            font-weight: 600;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s;
            display: inline-block;
        }

        .btn-primary {
            background: #26585E;
            color: #CAA679;
        }

        .btn-primary:hover {
            background: #1A3F45;
        }

        .btn-secondary {
            background: #CAA679;
            color: #26585E;
        }

        .btn-secondary:hover {
            background: #B89560;
        }

        /* FOOTER */
        footer {
            text-align: center;
            padding: 40px 20px;
            color: #26585E;
            font-size: 12px;
            border-top: 1px solid #E0D5C7;
            margin-top: 60px;
        }

        footer a {
            color: #26585E;
            text-decoration: none;
            font-weight: 600;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* TIMELINE VISUAL */
        .timeline-visual {
            background: white;
            padding: 40px;
            border-radius: 8px;
            margin-bottom: 40px;
            position: relative;
        }

        .timeline-bar {
            height: 80px;
            background: linear-gradient(90deg, #26585E 0%, #CAA679 50%, #26585E 100%);
            border-radius: 40px;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 40px;
            margin-bottom: 20px;
        }

        .timeline-marker {
            width: 30px;
            height: 30px;
            background: white;
            border: 3px solid #26585E;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: 700;
            color: #26585E;
            position: relative;
            z-index: 10;
        }

        .timeline-marker span {
            font-size: 11px;
        }

        .timeline-label {
            text-align: center;
            font-size: 11px;
            color: #666;
            margin-top: 10px;
            font-weight: 500;
        }

        .timeline-labels {
            display: flex;
            justify-content: space-between;
            padding: 0 40px;
        }

        .timeline-label-item {
            text-align: center;
            width: 60px;
        }

        .timeline-label-item strong {
            display: block;
            color: #26585E;
            font-size: 12px;
            font-weight: 700;
        }

        .timeline-label-item span {
            display: block;
            color: #999;
            font-size: 10px;
            margin-top: 3px;
        }
    </style>
</head>
<body>
    <!-- HEADER -->
    <div class="header">
        <div class="logo-section">
            <div class="logo-box">P</div>
            <div>
                <h1>Critical Skills Employment Permit</h1>
                <p>JOB SEARCH TO PERMIT APPROVAL</p>
            </div>
        </div>
    </div>

    <div class="container">
        <!-- STATS BAR -->
        <div class="stats">
            <div class="stat">
                <div class="stat-number">5–7</div>
                <div class="stat-label">Processing Weeks</div>
            </div>
            <div class="stat">
                <div class="stat-number">65–75%</div>
                <div class="stat-label">Job Placement Rate</div>
            </div>
            <div class="stat">
                <div class="stat-number">€40,904+</div>
                <div class="stat-label">Min. Salary (2026)</div>
            </div>
            <div class="stat">
                <div class="stat-number">3–4</div>
                <div class="stat-label">Months End-to-End</div>
            </div>
        </div>

        <!-- PHASE 1: JOB SEARCH -->
        <div class="section">
            <div class="section-title">Phase 1: Job Search & Application</div>
            <div class="workflow">
                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">1</div>
                        <div class="phase-title">Research</div>
                        <div class="phase-duration">Week 1–2</div>
                        <ul class="phase-tasks">
                            <li>Check Critical Skills List</li>
                            <li>Identify target roles</li>
                            <li>Research employers</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Employment Strategy Report
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">2</div>
                        <div class="phase-title">Prepare Profile</div>
                        <div class="phase-duration">Week 2–4</div>
                        <ul class="phase-tasks">
                            <li>Optimize CV</li>
                            <li>Polish LinkedIn</li>
                            <li>Gather references</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            CV & LinkedIn Optimization
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">3</div>
                        <div class="phase-title">Apply & Interview</div>
                        <div class="phase-duration">Week 4–8</div>
                        <ul class="phase-tasks">
                            <li>Submit applications</li>
                            <li>Attend interviews</li>
                            <li>Negotiate offer</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Interview Coaching (3–4 sessions)
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">4</div>
                        <div class="phase-title">Secure Offer</div>
                        <div class="phase-duration">Ongoing</div>
                        <ul class="phase-tasks">
                            <li>Accept offer</li>
                            <li>Confirm start date</li>
                            <li>Get signed contract</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Salary & Offer Negotiation
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- PHASE 2: PERMIT APPLICATION -->
        <div class="section">
            <div class="section-title">Phase 2: Permit Application & Processing</div>
            <div class="workflow">
                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">5</div>
                        <div class="phase-title">Eligibility Check</div>
                        <div class="phase-duration">1 Week</div>
                        <ul class="phase-tasks">
                            <li>Verify CSOL eligibility</li>
                            <li>Check salary thresholds</li>
                            <li>Review qualifications</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Eligibility Assessment
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">6</div>
                        <div class="phase-title">Prepare Documents</div>
                        <div class="phase-duration">1–2 Weeks</div>
                        <ul class="phase-tasks">
                            <li>Gather all documents</li>
                            <li>Format PDFs</li>
                            <li>Verify completeness</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Document Assembly & Review
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">7</div>
                        <div class="phase-title">Submit via EPOS</div>
                        <div class="phase-duration">1 Day</div>
                        <ul class="phase-tasks">
                            <li>Create EPOS account</li>
                            <li>Submit application</li>
                            <li>Pay €1,000 fee</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            EPOS Submission & Fee Guidance
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">8</div>
                        <div class="phase-title">DETE Review</div>
                        <div class="phase-duration">5–7 Weeks</div>
                        <ul class="phase-tasks">
                            <li>DETE assesses</li>
                            <li>Background checks</li>
                            <li>Verification process</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Status Tracking (every 10 days)
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- PHASE 3: DECISION & RELOCATION -->
        <div class="section">
            <div class="section-title">Phase 3: Decision, Visa & Relocation</div>
            <div class="workflow">
                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">9</div>
                        <div class="phase-title">Receive Decision</div>
                        <div class="phase-duration">Week 5–7</div>
                        <ul class="phase-tasks">
                            <li>✓ Approved</li>
                            <li>✗ Refused (rare)</li>
                            <li>ℹ More Info Needed</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Decision Notification & Appeal Support
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">10</div>
                        <div class="phase-title">Apply for D Visa</div>
                        <div class="phase-duration">2–4 Weeks</div>
                        <ul class="phase-tasks">
                            <li>Check visa requirement</li>
                            <li>Prepare documents</li>
                            <li>Apply at embassy</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Visa & Immigration Guidance (€350)
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">11</div>
                        <div class="phase-title">Relocate to Ireland</div>
                        <div class="phase-duration">Concurrent</div>
                        <ul class="phase-tasks">
                            <li>Book flights</li>
                            <li>Find accommodation</li>
                            <li>Arrange logistics</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Relocation & Settlement Support
                        </div>
                    </div>
                </div>

                <div class="phase">
                    <div class="phase-card">
                        <div class="phase-num">12</div>
                        <div class="phase-title">Start Employment</div>
                        <div class="phase-duration">Ongoing</div>
                        <ul class="phase-tasks">
                            <li>Begin work</li>
                            <li>Register with INIS</li>
                            <li>Open bank account</li>
                        </ul>
                        <div class="permitpath-badge">
                            <strong>PermitPath</strong>
                            Ongoing Support (4–8 weeks)
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- TIMELINE VISUAL -->
        <div class="section">
            <div class="section-title">Total Timeline</div>
            <div class="timeline-visual">
                <div class="timeline-bar">
                    <div class="timeline-marker"><span>1</span></div>
                    <div class="timeline-marker"><span>2</span></div>
                    <div class="timeline-marker"><span>3</span></div>
                    <div class="timeline-marker"><span>4</span></div>
                </div>
                <div class="timeline-labels">
                    <div class="timeline-label-item">
                        <strong>Search & Apply</strong>
                        <span>4–8 weeks</span>
                    </div>
                    <div class="timeline-label-item">
                        <strong>Permit Process</strong>
                        <span>2–3 weeks prep</span>
                    </div>
                    <div class="timeline-label-item">
                        <strong>DETE Review</strong>
                        <span>5–7 weeks</span>
                    </div>
                    <div class="timeline-label-item">
                        <strong>Visa & Start</strong>
                        <span>2–4 weeks</span>
                    </div>
                </div>
            </div>
            <div style="text-align: center; font-size: 18px; font-weight: 700; color: #26585E; margin-top: 20px;">
                ↓ TOTAL: 3–4 MONTHS ↓
            </div>
        </div>

        <!-- KEY REQUIREMENTS -->
        <div class="section">
            <div class="section-title">Requirements at a Glance</div>
            <div class="requirements">
                <div class="req-card">
                    <div class="req-icon">📋</div>
                    <h4>Role on CSOL</h4>
                    <p>Job must be on Critical Skills Occupational List</p>
                </div>
                <div class="req-card">
                    <div class="req-icon">💰</div>
                    <h4>Min. Salary (2026)</h4>
                    <p>€40,904+ (with relevant degree) or €68,911+ (without degree)</p>
                </div>
                <div class="req-card">
                    <div class="req-icon">🎓</div>
                    <h4>Qualifications</h4>
                    <p>Degree or equivalent experience</p>
                </div>
                <div class="req-card">
                    <div class="req-icon">🏢</div>
                    <h4>Employer Legit</h4>
                    <p>Compliant Irish business</p>
                </div>
                <div class="req-card">
                    <div class="req-icon">📄</div>
                    <h4>Full Documents</h4>
                    <p>Complete, authentic, properly formatted</p>
                </div>
                <div class="req-card">
                    <div class="req-icon">✓</div>
                    <h4>2-Year Validity</h4>
                    <p>Permit lasts 2 years; renewable</p>
                </div>
            </div>
        </div>

        <!-- CTA -->
        <div class="cta-section">
            <h2>Ready to Hire or Work in Ireland?</h2>
            <p>PermitPath guides you through every step—from strategy to approval.</p>
            <div class="cta-buttons">
                <a href="https://calendar.app.google/nVmfwbWG1ANBNXJE7" class="btn btn-primary" target="_blank">Book Consultation</a>
                <a href="mailto:gisela@permitpath.ie" class="btn btn-secondary">Email Gisela</a>
            </div>
        </div>
    </div>

    <!-- FOOTER -->
    <footer>
        <p><strong>PermitPath</strong> – Ireland's Employment Permit Experts</p>
        <p>📧 <a href="mailto:gisela@permitpath.ie">gisela@permitpath.ie</a> | 🌐 <a href="https://www.permitpath.ie" target="_blank">www.permitpath.ie</a> | 📅 <a href="https://calendar.app.google/nVmfwbWG1ANBNXJE7" target="_blank">Book Consultation</a></p>
        <p style="margin-top: 15px; color: #CAA679; font-weight: 600;">Your path to working in Ireland</p>
    </footer>
</body>
</html>
