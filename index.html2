<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>מדריך ליווי סטודנטים - עתידים</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #6c5ce7 0%, #74b9ff 100%);
            min-height: 100vh;
            padding: 10px;
        }
        
        .container {
            max-width: 400px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #6c5ce7, #a29bfe);
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
        }
        
        .logo {
            width: 40px;
            height: 40px;
            position: absolute;
            top: 15px;
            left: 20px;
            background: white;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .logo svg {
            width: 30px;
            height: 30px;
            fill: #6c5ce7;
        }
        
        .header h1 {
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        
        .header p {
            font-size: 0.85em;
            opacity: 0.9;
        }
        
        .nav-tabs {
            display: flex;
            background: #f8f9fa;
            border-bottom: 1px solid #dee2e6;
            overflow-x: auto;
        }
        
        .nav-tab {
            flex: 1;
            padding: 10px 6px;
            text-align: center;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 0.75em;
            font-weight: 500;
            color: #6c757d;
            transition: all 0.3s;
            white-space: nowrap;
            min-width: 80px;
        }
        
        .nav-tab.active {
            background: white;
            color: #6c5ce7;
            border-bottom: 3px solid #6c5ce7;
        }
        
        .tab-content {
            display: none;
            padding: 20px;
            max-height: 70vh;
            overflow-y: auto;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .section {
            margin-bottom: 20px;
        }
        
        .section-title {
            font-size: 1.1em;
            font-weight: bold;
            color: #343a40;
            margin-bottom: 10px;
            padding-bottom: 5px;
            border-bottom: 2px solid #6c5ce7;
        }
        
        .contact-item, .requirement-item, .population-item, .service-item {
            background: #f8f9fa;
            border: 1px solid #e9ecef;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 10px;
            transition: transform 0.2s;
        }
        
        .contact-item:hover, .population-item:hover, .service-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(108, 92, 231, 0.2);
        }
        
        .contact-name, .population-name, .service-name {
            font-weight: bold;
            color: #495057;
            margin-bottom: 5px;
        }
        
        .contact-details, .population-details, .service-details {
            font-size: 0.9em;
            color: #6c757d;
        }
        
        .phone-link, .service-link {
            color: #6c5ce7;
            text-decoration: none;
            font-weight: 500;
        }
        
        .phone-link:hover, .service-link:hover {
            text-decoration: underline;
        }
        
        .emergency-btn {
            background: linear-gradient(135deg, #e84393, #fd79a8);
            color: white;
            border: none;
            padding: 15px;
            border-radius: 10px;
            width: 100%;
            font-size: 1em;
            font-weight: bold;
            margin-bottom: 15px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .emergency-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(232, 67, 147, 0.4);
        }
        
        .tips-item {
            background: linear-gradient(135deg, #e8f4fd, #f0f0ff);
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border-right: 4px solid #6c5ce7;
        }
        
        .tips-title {
            font-weight: bold;
            color: #6c5ce7;
            margin-bottom: 8px;
        }
        
        .tips-content {
            color: #636e72;
            font-size: 0.9em;
            line-height: 1.4;
        }
        
        .checklist-item {
            display: flex;
            align-items: center;
            padding: 10px;
            margin-bottom: 8px;
            background: #f8f9fa;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s;
        }
        
        .checklist-item:hover {
            background: #e9ecef;
        }
        
        .checklist-checkbox {
            margin-left: 10px;
            transform: scale(1.2);
        }
        
        .year-selector {
            display: flex;
            margin-bottom: 20px;
            background: #f8f9fa;
            border-radius: 10px;
            padding: 5px;
        }
        
        .year-btn {
            flex: 1;
            padding: 8px;
            background: none;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.9em;
            transition: all 0.3s;
        }
        
        .year-btn.active {
            background: #6c5ce7;
            color: white;
        }
        
        .resource-link {
            display: block;
            background: #e8f4fd;
            border: 1px solid #74b9ff;
            border-radius: 8px;
            padding: 12px;
            margin-bottom: 10px;
            text-decoration: none;
            color: #0984e3;
            transition: all 0.3s;
        }
        
        .resource-link:hover {
            background: #74b9ff;
            color: white;
            transform: translateX(-5px);
        }
        
        .urgent-notice {
            background: linear-gradient(135deg, #ffeaa7, #fab1a0);
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border-right: 4px solid #e17055;
        }
        
        .search-box {
            width: 100%;
            padding: 12px;
            border: 1px solid #dee2e6;
            border-radius: 10px;
            margin-bottom: 15px;
            font-size: 0.9em;
        }
        
        .gantt-chart {
            background: white;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border: 1px solid #dee2e6;
        }
        
        .gantt-row {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
            font-size: 0.85em;
        }
        
        .gantt-label {
            width: 100px;
            font-weight: 500;
            color: #495057;
        }
        
        .gantt-bar {
            flex: 1;
            height: 20px;
            background: #e9ecef;
            border-radius: 10px;
            overflow: hidden;
            position: relative;
        }
        
        .gantt-progress {
            height: 100%;
            background: linear-gradient(135deg, #6c5ce7, #74b9ff);
            border-radius: 10px;
            transition: width 0.3s;
        }
        
        .requirement-check {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 12px;
            margin-bottom: 8px;
            background: #f8f9fa;
            border-radius: 8px;
            border-right: 4px solid #dee2e6;
        }
        
        .requirement-check.completed {
            background: #d4edda;
            border-right-color: #28a745;
        }
        
        .requirement-check.pending {
            background: #fff3cd;
            border-right-color: #ffc107;
        }
        
        .requirement-text {
            flex: 1;
            font-size: 0.9em;
        }
        
        .requirement-status {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.8em;
            font-weight: bold;
        }
        
        .status-completed {
            background: #28a745;
            color: white;
        }
        
        .status-pending {
            background: #ffc107;
            color: white;
        }
        
        .status-missing {
            background: #dc3545;
            color: white;
        }
        
        .step-item {
            display: flex;
            align-items: center;
            padding: 15px;
            margin-bottom: 10px;
            background: #f8f9fa;
            border-radius: 10px;
            border-right: 4px solid #6c5ce7;
        }
        
        .step-number {
            width: 30px;
            height: 30px;
            background: #6c5ce7;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-left: 15px;
            flex-shrink: 0;
        }
        
        .step-content {
            flex: 1;
        }
        
        .step-title {
            font-weight: bold;
            color: #6c5ce7;
            margin-bottom: 5px;
        }
        
        .step-description {
            font-size: 0.9em;
            color: #6c757d;
            line-height: 1.4;
        }
        
        .whatsapp-link {
            background: linear-gradient(135deg, #25D366, #128C7E);
            color: white;
        }
        
        .telegram-link {
            background: linear-gradient(135deg, #0088cc, #229ED9);
            color: white;
        }
        
        .linkedin-link {
            background: linear-gradient(135deg, #0077B5, #00A0DC);
            color: white;
        }
        
        .free-service {
            background: #d4edda;
            border-color: #28a745;
        }
        
        .paid-service {
            background: #fff3cd;
            border-color: #ffc107;
        }
        
        .cost-tag {
            display: inline-block;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 0.8em;
            font-weight: bold;
            margin-top: 5px;
        }
        
        .cost-free {
            background: #28a745;
            color: white;
        }
        
        .cost-paid {
            background: #ffc107;
            color: black;
        }
        
        .cost-subsidized {
            background: #17a2b8;
            color: white;
        }
        
        .urgent-btn {
            background: linear-gradient(135deg, #dc3545, #c82333);
            color: white;
            border: none;
            padding: 12px;
            border-radius: 8px;
            width: 100%;
            font-size: 0.9em;
            font-weight: bold;
            margin-bottom: 10px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .tools-section {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border: 1px solid #dee2e6;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo">
                <svg viewBox="0 0 100 100">
                    <path d="M20,80 L50,20 L80,80 Z" fill="#6c5ce7"/>
                    <circle cx="50" cy="60" r="8" fill="white"/>
                </svg>
            </div>
            <h1>🎓 מדריך ליווי סטודנטים</h1>
            <p>עתידים לתעשייה ולהייטק</p>
        </div>
        
        <div class="nav-tabs">
            <button class="nav-tab active" onclick="showTab('emergency')">חירום</button>
            <button class="nav-tab" onclick="showTab('contacts')">אנשי קשר</button>
            <button class="nav-tab" onclick="showTab('populations')">אוכלוסיות</button>
            <button class="nav-tab" onclick="showTab('mental-health')">בריאות נפש</button>
            <button class="nav-tab" onclick="showTab('requirements')">דרישות</button>
            <button class="nav-tab" onclick="showTab('jobs')">משרות</button>
            <button class="nav-tab" onclick="showTab('tools')">כלים</button>
            <button class="nav-tab" onclick="showTab('placement')">השמה</button>
        </div>
        
        <!-- טאב חירום -->
        <div id="emergency" class="tab-content active">
            <button class="emergency-btn" onclick="call('1201')">
                🚨 ער"ן - עזרה ראשונה נפשית<br>
                <small>*1201 - זמין 24/7</small>
            </button>
            
            <button class="emergency-btn" onclick="window.open('https://sahar.org.il/help/', '_blank')" style="background: linear-gradient(135deg, #6c5ce7, #a29bfe);">
                💬 סהר - סיוע והקשבה ברשת<br>
                <small>צ'אט ווואטסאפ אנונימי</small>
            </button>
            
            <div class="section">
                <div class="section-title">📞 מספרי חירום נוספים</div>
                
                <div class="contact-item">
                    <div class="contact-name">מוקד נפגעי תקיפה מינית</div>
                    <div class="contact-details">
                        <a href="tel:1202" class="phone-link">*1202</a> - זמין 24/7
                    </div>
                </div>
                
                <div class="contact-item">
                    <div class="contact-name">קו סיוע לנוער במצוקה</div>
                    <div class="contact-details">
                        <a href="tel:1201" class="phone-link">*1201</a> שלוחה 3
                    </div>
                </div>
                
                <div class="contact-item">
                    <div class="contact-name">7+ מעגלים של תקווה</div>
                    <div class="contact-details">
                        בעקבות אירועי 7 באוקטובר<br>
                        <a href="https://seven-plus.org.il" class="phone-link">seven-plus.org.il</a><br>
                        ילדים, מבוגרים ומשפחות נפגעי מלחמה
                    </div>
                </div>
            </div>
            
            <div class="urgent-notice">
                <strong>⚠️ חשוב לזכור:</strong><br>
                אם סטודנט נמצא בסכנה מיידית - התקשרו למשטרה 100 או למד"א 101
            </div>
        </div>
        
        <!-- טאב אנשי קשר -->
        <div id="contacts" class="tab-content">
            <input type="text" class="search-box" placeholder="חיפוש אנשי קשר..." onkeyup="searchContacts(this.value)">
            
            <div class="section">
                <div class="section-title">👥 צוות עתידים</div>
                
                <div class="contact-item" data-search="מורן רוזנברג צפון טכניון בראודה">
                    <div class="contact-name">מורן רוזנברג - אזור צפון</div>
                    <div class="contact-details">
                        טכניון/בראודה<br>
                        <a href="tel:0505999551" class="phone-link">050-5999551</a><br>
                        <a href="mailto:northstudent@atidim.org.il" class="phone-link">northstudent@atidim.org.il</a>
                    </div>
                </div>
                
                <div class="contact-item" data-search="מעיין גלס מרכז">
                    <div class="contact-name">מעיין גלס - אזור מרכז</div>
                    <div class="contact-details">
                        מוסדות אקדמיים במרכז<br>
                        <a href="tel:0545696973" class="phone-link">054-5696973</a><br>
                        <a href="mailto:maayang@atidim.org.il" class="phone-link">maayang@atidim.org.il</a>
                    </div>
                </div>
                
                <div class="contact-item" data-search="ליאן סלמה דרום ירושלים">
                    <div class="contact-name">ליאן סלמה - דרום וירושלים</div>
                    <div class="contact-details">
                        אזור דרום וירושלים<br>
                        <a href="tel:0547774273" class="phone-link">054-7774273</a><br>
                        <a href="mailto:daromstudent@atidim.org.il" class="phone-link">daromstudent@atidim.org.il</a>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🏛️ סיוע אקדמי</div>
                
                <div class="contact-item" data-search="דיקן סטודנטים">
                    <div class="contact-name">דיקן הסטודנטים</div>
                    <div class="contact-details">
                        לפי המוסד - יש לחפש באתר המוסד<br>
                        בדרך כלל: dean.students@[university].ac.il<br>
                        טיפול פסיכולוגי מסובסד
                    </div>
                </div>
                
                <div class="contact-item" data-search="קופות חולים">
                    <div class="contact-name">קופות החולים</div>
                    <div class="contact-details">
                        טיפול פסיכולוגי בקופ"ח<br>
                        בחלק ללא עלות למספר מועט של מפגשים<br>
                        בחלקן בעלות מסובסדת
                    </div>
                </div>
            </div>
        </div>
        
        <!-- טאב אוכלוסיות -->
        <div id="populations" class="tab-content">
            <div class="section">
                <div class="section-title">🌍 עולים חדשים</div>
                
                <div class="population-item">
                    <div class="population-name">המינהל לסטודנטים עולים</div>
                    <div class="population-details">
                        מלגות, ייעוץ מקצועי, מדריך אישי-חברתי<br>
                        קורסי עברית/אנגלית ל"פטור"<br>
                        <a href="mailto:info@mahar.gov.il" class="phone-link">info@mahar.gov.il</a><br>
                        <a href="tel:026289580" class="phone-link">02-628-9580</a><br>
                        <a href="https://www.gov.il/he/departments/ministry_of_aliyah_and_integration" class="phone-link">אתר המשרד</a>
                    </div>
                </div>
                
                <div class="population-item">
                    <div class="population-name">תכניות קליטה נוספות</div>
                    <div class="population-details">
                        • הכנה לאקדמיה<br>
                        • מנהיגות עולה באקדמיה<br>
                        • חיבור ישראלי<br>
                        • ליווי עובדים סוציאליים<br>
                        • פעילות חברתית וטיולים<br>
                        • שח"ק - שירות חברתי קהילתי
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">👨‍🎓 בוגרי חינוך חרדי</div>
                
                <div class="population-item">
                    <div class="population-name">מלגת טנא</div>
                    <div class="population-details">
                        7,000 ש"ח לתואר ראשון, 9,800 ש"ח לתואר שני<br>
                        <a href="https://www.tenne-aluma.org.il" class="phone-link">tenne-aluma.org.il</a><br>
                        תכנית זרקור - ליווי וייעוץ חובה<br>
                        עדיפות לבעלי מספר נפשות רב במשפחה
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🇪🇹 ישראלים ממוצא אתיופי</div>
                
                <div class="population-item">
                    <div class="population-name">מלגות ייעודיות</div>
                    <div class="population-details">
                        קרנות מלגות מיוחדות<br>
                        ליווי אקדמי וחברתי<br>
                        תכניות העצמה קהילתיות
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🪖 משרתי מילואים</div>
                
                <div class="population-item">
                    <div class="population-name">תכנית עמית</div>
                    <div class="population-details">
                        מינימום 30 ימי שירות במילואים<br>
                        ספורט, רפואה משלימה, הפחתת לחץ וחרדה<br>
                        טיפול פסיכולוגי<br>
                        <a href="https://www.hachvana.mod.gov.il/ConsultationAndDirection/Pages/amit-program.aspx" class="phone-link">תכנית עמית</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
                
                <div class="population-item">
                    <div class="population-name">שבים - חזרה לשיגרה</div>
                    <div class="population-details">
                        8 מפגשים פעם בשבוע, מקסימום 15 משתתפים<br>
                        מילואים ובני משפחותיהם<br>
                        <a href="https://www.shavimback.com" class="phone-link">shavimback.com</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🎖️ חיילים בודדים</div>
                
                <div class="population-item">
                    <div class="population-name">קרן הישג</div>
                    <div class="population-details">
                        לסטודנטים שהוכרו כחיילים בודדים במהלך השירות<br>
                        תמיכה כלכלית ואקדמית<br>
                        מלגות לימודים מיוחדות
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🏔️ בני העדה הדרוזית</div>
                
                <div class="population-item">
                    <div class="population-name">מלגות מיוחדות</div>
                    <div class="population-details">
                        קרנות ייעודיות לעדה הדרוזית<br>
                        ליווי אקדמי וחברתי מותאם<br>
                        תכניות העצמה קהילתיות
                    </div>
                </div>
            </div>
        </div>
        
        <!-- טאב בריאות נפש -->
        <div id="mental-health" class="tab-content">
            <div class="section">
                <div class="section-title">🆘 טיפול מיידי</div>
                
                <div class="service-item free-service">
                    <div class="service-name">ער"ן - עזרה ראשונה נפשית</div>
                    <div class="service-details">
                        <a href="tel:1201" class="phone-link">*1201</a> - 24 שעות ביממה<br>
                        מענה טלפוני מיידי
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
                
                <div class="service-item free-service">
                    <div class="service-name">סהר - סיוע והקשבה ברשת</div>
                    <div class="service-details">
                        <a href="https://sahar.org.il/help/" class="service-link">sahar.org.il/help</a><br>
                        צ'אט ווואטסאפ אנונימי<br>
                        תמיכה מקוונת לבריאות נפשית
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🏥 טיפול מקצועי</div>
                
                <div class="service-item free-service">
                    <div class="service-name">הדספייס</div>
                    <div class="service-details">
                        עד 15 טיפולים עד גיל 25<br>
                        <a href="https://www.headspace.org.il/צור-קשר/" class="service-link">headspace.org.il</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
                
                <div class="service-item free-service">
                    <div class="service-name">הדספייס דלת פתוחה</div>
                    <div class="service-details">
                        פגישה חד פעמית 30 דקות<br>
                        <a href="tel:0509693460" class="phone-link">050-969-3460</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
                
                <div class="service-item paid-service">
                    <div class="service-name">דיקאנט הסטודנטים</div>
                    <div class="service-details">
                        באתר מוסד הלימוד > דיקאנט הסטודנטים > ייעוץ פסיכולוגי<br>
                        לפי מוסד הלימודים
                        <span class="cost-tag cost-subsidized">מסובסד</span>
                    </div>
                </div>
                
                <div class="service-item paid-service">
                    <div class="service-name">במחלקות לפסיכולוגיה</div>
                    <div class="service-details">
                        סטאג'רים במחלקות לפסיכולוגיה נותנים טיפול<br>
                        לבדוק לפי מוסד לימודים
                        <span class="cost-tag cost-subsidized">מסובסד</span>
                    </div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">קופות החולים</div>
                    <div class="service-details">
                        באתר קופ"ח > טיפול פסיכולוגי<br>
                        בחלק מהקופות ללא עלות למספר מועט של מפגשים<br>
                        ובחלקן בעלות מסובסדת
                        <span class="cost-tag cost-subsidized">חלקית ללא עלות</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🪖 טיפול למילואים</div>
                
                <div class="service-item free-service">
                    <div class="service-name">תכנית עמית</div>
                    <div class="service-details">
                        מינימום 30 ימי שירות<br>
                        ספורט, רפואה משלימה, הפחתת לחץ וחרדה, טיפול פסיכולוגי<br>
                        <a href="https://www.hachvana.mod.gov.il/ConsultationAndDirection/Pages/amit-program.aspx" class="service-link">hachvana.mod.gov.il</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
                
                <div class="service-item free-service">
                    <div class="service-name">שבים</div>
                    <div class="service-details">
                        8 מפגשים פעם בשבוע, מקסימום 15 משתתפים בקבוצה<br>
                        עזרה בחזרה לשיגרה<br>
                        מילואים ובני משפחותיהם<br>
                        <a href="https://www.shavimback.com/" class="service-link">shavimback.com</a>
                        <span class="cost-tag cost-free">ללא עלות</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <div class="section-title">🩺 טיפול מיוחד</div>
                
                <div class="service-item">
                    <div class="service-name">נט"ל - נפגעי טראומה על רקע לאומי</div>
                    <div class="service-details">
                        <a href="https://www.natal.org.il/תמיכה-וטיפול-נפשי/" class="service-link">natal.org.il</a><br>
                        טיפול קליני, קבוצתי, יוגה מודעת טראומה<br>
                        טיפול באומנות, בתנועה ועוד
                        <span class="cost-tag cost-paid">תלוי מענה טיפולי</span>
                    </div>
                </div>
                
                <div class="service-item">
                    <div class="service-name">7+ מעגלים של תקווה</div>
                    <div class="service-details">
                        בעקבות אירועי 7 באוקטובר<br>
                        <a href="https://seven-plus.org.il/הפרויקט/" class="service-link">seven-plus.org.il</a><br>
                        ילדים, מבוגרים ומשפחות נפגעי מלחמה
                        <span class="cost-tag cost-paid">מחיר סמלי</span>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- טאב דרישות -->
        <div id="requirements" class="tab-content">
            <div class="section">
                <div class="section-title">📋 דרישות התכנית</div>
                
                <div class="requirement-check completed">
                    <div class="requirement-text">
                        <strong>ממוצע 75 ומעלה</strong><br>
                        <small>נדרש להמשך בתכנית</small>
                    </div>
                    <div class="requirement-status status-completed">✓</div>
                </div>
                
                <div class="requirement-check pending">
                    <div class="requirement-text">
                        <strong>העלאת גליון ציונים</strong><br>
                        <small>אחרי כל סמסטר - חובה!</small>
                    </div>
                    <div class="requirement-status status-pending">!</div>
                </div>
                
                <div class="requirement-check completed">
                    <div class="requirement-text">
                        <strong>60 שעות התנדבות בשנה</strong><br>
                        <small>פעילות חברתית מאושרת</small>
                    </div>
                    <div class="requirement-status status-completed">✓</div>
                </div>
                
                <div class="requirement-check pending">
                    <div class="requirement-text">
                        <strong>קורות חיים מעודכנים</strong><br>
                        <small>חובה מתחילת השנה</small>
                    </div>
                    <div class="requirement-status status-pending">!</div>
                </div>
                
                <div class="requirement-check" id="linkedin-req">
                    <div class="requirement-text">
                        <strong>פרופיל LinkedIn</strong><br>
                        <small>חובה משנה ב' ומעלה</small>
                    </div>
                    <div class="requirement-status status-pending">!</div>
                </div>
                
                <div class="requirement-check completed">
                    <div class="requirement-text">
                        <strong>השתתפות בסדנאות</strong><br>
                        <small>סדנאות חובה לפי שנת הלימוד</small>
                    </div>
                    <div class="requirement-status status-completed">✓</div>
                </div>
            </div>
            
            <div class="tips-item">
                <div class="tips-title">💡 טיפ חשוב</div>
                <div class="tips-content">
                    עדכנו את הרכזת שלכם בכל שינוי בסטטוס הדרישות. זה עוזר לנו לעקוב אחר ההתקדמות ולתת תמיכה מותאמת.
                </div>
            </div>
        </div>
        
        <!-- טאב משרות -->
        <div id="jobs" class="tab-content">
            <div class="section">
                <div class="section-title">📱 קבוצות משרות</div>
                
                <a href="https://chat.whatsapp.com/ItCs15Io5I76f5A88qKWgk" class="resource-link whatsapp-link" target="_blank">
                    📱 קבוצת WhatsApp עתידים - משרות
                </a>
                
                <a href="https://lnkd.in/drtspfPV" class="resource-link linkedin-link" target="_blank">
                    💼 קבוצת LinkedIn - משרות לסטודנטים
                </a>
                
                <a href="https://t.me/HiTech_Jobs_In_Israel" class="resource-link telegram-link" target="_blank">
                    🔵 Telegram - משרות הייטק בישראל
                </a>
            </div>
            
            <div class="section">
                <div class="section-title">💼 אתרי חיפוש עבודה</div>
                
                <a href="https://www.jobmaster.co.il" class="resource-link" target="_blank">
                    🔍 JobMaster - משרות סטודנטים
                </a>
                
                <a href="https://www.drushim.co.il" class="resource-link" target="_blank">
                    💼 דרושים - אתר דרושים מוביל
                </a>
                
                <a href="https://www.alljobs.co.il" class="resource-link" target="_blank">
                    🎯 AllJobs - משרות בהייטק
                </a>
                
                <a href="https://www.linkedin.com/jobs" class="resource-link" target="_blank">
                    🌐 LinkedIn Jobs
                </a>
            </div>
            
            <div class="section">
                <div class="section-title">📋 דיווח על הגשה למשרה</div>
                
                <a href="https://forms.gle/6Qd5eJgChFxx1VWk9" class="resource-link" target="_blank" style="background: linear-gradient(135deg, #4285f4, #34a853);">
                    📝 טופס דיווח הגשה למשרה
                </a>
            </div>
            
            <div class="tips-item">
                <div class="tips-title">⚠️ חשוב!</div>
                <div class="tips-content">
                    יש לדווח לרכזת על כל הגשה למשרה דרך הטופס. זה עוזר לנו לעקוב אחר ההתקדמות ולתת ליווי מותאם.
                </div>
            </div>
        </div>
        
        <!-- טאב כלים -->
        <div id="tools" class="tab-content">
            <div class="tools-section">
                <div class="section-title">📝 כלי עזר לקורות חיים ולינקדאין</div>
                
                <a href="https://chatgpt.com/g/g-687d225e8adc81919aff5e893c7a12ee-shahar-s-cv-optimizer-pro" class="resource-link" target="_blank">
                    🤖 ChatGPT - CV Optimizer Pro
                </a>
                
                <a href="https://chatgpt.com/g/g-68174f18a84c8191a7440046caf72b02-svkn-qvrvt-khyym-tydym-lt-shyyh" class="resource-link" target="_blank">
                    💼 ChatGPT - סקירת קורות חיים עתידים
                </a>
                
                <a href="https://drive.google.com/drive/folders/1E4P65PcBVg-jnnhX1Wu0P9gvJNsdpK4i" class="resource-link" target="_blank">
                    📁 Google Drive - תבניות וכלים
                </a>
            </div>
            
            <div class="tools-section">
                <div class="section-title">🎯 הכנה לראיונות</div>
                
                <a href="https://chatgpt.com/g/g-681769d0bebc81919d665ed837fcbeb7-mmn-lryvnvt-bvdh-tydym-lt-shyyh" class="resource-link" target="_blank">
                    🤖 ChatGPT - מומן לראיונות בעבודה עתידים
                </a>
                
                <a href="https://docs.google.com/document/d/1KWoLtu32z0youjMnpu_jdRxTq3BXglE7LzEGq3Wluv8/edit" class="resource-link" target="_blank">
                    📄 מדריך הכנה לראיונות טכניים
                </a>
            </div>
            
            <div class="tools-section">
                <div class="section-title">📄 מסמכים וחוזים</div>
                
                <a href="https://docs.google.com/document/d/1-rc2DSYQp36pYTqwrJcn4n6MWnJwuGDH0dTv8iR0kzQ/edit" class="resource-link" target="_blank">
                    📋 סיוע עם חוזי עבודה
                </a>
            </div>
            
            <div class="section">
                <div class="section-title">💰 מלגות ומימונים</div>
                
                <a href="https://milgapo.co.il" class="resource-link" target="_blank">
                    🎓 מלגהפה - מעל 1000 מלגות
                </a>
                
                <a href="https://www.tenne-aluma.org.il" class="resource-link" target="_blank">
                    📚 טנא - מלגות למגזר החרדי
                </a>
                
                <a href="https://www.study.co.il/P32473" class="resource-link" target="_blank">
                    💡 לימודים בישראל - מאגר מלגות
                </a>
            </div>
            
            <div class="section">
                <div class="section-title">📚 משאבי למידה</div>
                
                <a href="https://www.coursera.org" class="resource-link" target="_blank">
                    🎓 Coursera - קורסים אונליין
                </a>
                
                <a href="https://www.codecademy.com" class="resource-link" target="_blank">
                    💻 Codecademy - לימוד תכנות
                </a>
                
                <a href="https://github.com" class="resource-link" target="_blank">
                    🔧 GitHub - ניהול קוד ופרויקטים
                </a>
                
                <a href="https://stackoverflow.com" class="resource-link" target="_blank">
                    ❓ Stack Overflow - שאלות ותשובות טכניות
                </a>
            </div>
            
            <div class="section">
                <div class="section-title">🤝 הטבות לסטודנטים</div>
                
                <a href="https://www.istudent.co.il" class="resource-link" target="_blank">
                    🎁 iStudent - הנחות לסטודנטים
                </a>
                
                <a href="https://education.github.com/pack" class="resource-link" target="_blank">
                    📦 GitHub Student Pack
                </a>
                
                <a href="https://azure.microsoft.com/en-us/free/students" class="resource-link" target="_blank">
                    ☁️ Azure for Students
                </a>
            </div>
        </div>
        
        <!-- טאב מעקב השמה -->
        <div id="placement" class="tab-content">
            <div class="section">
                <div class="section-title">🎯 8 שלבים למציאת עבודה</div>
                
                <div class="step-item">
                    <div class="step-number">1</div>
                    <div class="step-content">
                        <div class="step-title">מציאת שדה</div>
                        <div class="step-description">איתור והכרת הזדמנויות בסטארט אפ או מקום עבודה מוכר/חדש</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">2</div>
                    <div class="step-content">
                        <div class="step-title">בדיקת שטח</div>
                        <div class="step-description">לחקור ולהכיר תחומי ענין וכיוונים למיפוי כללי שימושי</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">3</div>
                    <div class="step-content">
                        <div class="step-title">הכנת יעדים קטנים</div>
                        <div class="step-description">הגדרת מועד ומטרות ליצירת הקשר עד זמן הכנת הכלל</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">4</div>
                    <div class="step-content">
                        <div class="step-title">שיחת הכנה</div>
                        <div class="step-description">קיום שיחה והכנה לראיון כולל הכנת מסמכים ותיאומים</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">5</div>
                    <div class="step-content">
                        <div class="step-title">עידכון סטטוס</div>
                        <div class="step-description">עידכון סטטוס אחרי קבלת ראיון</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">6</div>
                    <div class="step-content">
                        <div class="step-title">קבלת תשובות</div>
                        <div class="step-description">קבלת תשובות והחברה הבינלאומית להתקדמות</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">7</div>
                    <div class="step-content">
                        <div class="step-title">עידכון מעמדות עובדים</div>
                        <div class="step-description">העמקה והערכה עם טיוב החברים והתחברות בתהליכים</div>
                    </div>
                </div>
                
                <div class="step-item">
                    <div class="step-number">8</div>
                    <div class="step-content">
                        <div class="step-title">סיכום יום הראיון</div>
                        <div class="step-description">היועצת מסכמת עם הסטודנט את תהליך הראיון והמשך הצעדים</div>
                    </div>
                </div>
            </div>
            
            <div class="tips-item">
                <div class="tips-title">🎯 המטרה שלנו</div>
                <div class="tips-content">
                    ליווי מלא במציאת משרת סטודנט איכותית שתקדם אתכם לעבודה מלאה אחרי הסיום. כל שלב חשוב ומותאם אישית לכל סטודנט.
                </div>
            </div>
            
            <div class="urgent-notice">
                <strong>📋 חשוב לזכור:</strong><br>
                יש למלא את טופס דיווח ההגשה למשרה בכל פעם שמגישים מועמדות!
            </div>
        </div>
    </div>
    
    <script>
        function showTab(tabId) {
            // Hide all tabs
            const tabs = document.querySelectorAll('.tab-content');
            tabs.forEach(tab => tab.classList.remove('active'));
            
            // Remove active class from all nav tabs
            const navTabs = document.querySelectorAll('.nav-tab');
            navTabs.forEach(tab => tab.classList.remove('active'));
            
            // Show selected tab
            document.getElementById(tabId).classList.add('active');
            event.target.classList.add('active');
        }
        
        function showYear(yearNum) {
            // Hide all year contents
            const yearContents = document.querySelectorAll('.year-content');
            yearContents.forEach(content => content.style.display = 'none');
            
            // Remove active class from all year buttons
            const yearBtns = document.querySelectorAll('.year-btn');
            yearBtns.forEach(btn => btn.classList.remove('active'));
            
            // Show selected year
            document.getElementById('year' + yearNum).style.display = 'block';
            event.target.classList.add('active');
            
            // Save selected year
            localStorage.setItem('selectedYear', yearNum.toString());
        }
        
        function toggleCheck(item) {
            const checkbox = item.querySelector('.checklist-checkbox');
            checkbox.checked = !checkbox.checked;
            
            if (checkbox.checked) {
                item.style.background = '#d4edda';
                item.style.borderRight = '4px solid #28a745';
            } else {
                item.style.background = '#f8f9fa';
                item.style.borderRight = 'none';
            }
        }
        
        function searchContacts(query) {
            const contacts = document.querySelectorAll('.contact-item[data-search]');
            const searchTerm = query.toLowerCase();
            
            contacts.forEach(contact => {
                const searchData = contact.getAttribute('data-search').toLowerCase();
                const contactText = contact.textContent.toLowerCase();
                
                if (searchData.includes(searchTerm) || contactText.includes(searchTerm)) {
                    contact.style.display = 'block';
                } else {
                    contact.style.display = 'none';
                }
            });
        }
        
        function call(number) {
            window.location.href = 'tel:' + number;
        }
        
        // Save checkbox states in localStorage
        document.addEventListener('DOMContentLoaded', function() {
            const checkboxes = document.querySelectorAll('.checklist-checkbox');
            checkboxes.forEach((checkbox, index) => {
                const saved = localStorage.getItem('checkbox_' + index);
                if (saved === 'true') {
                    checkbox.checked = true;
                    const item = checkbox.closest('.checklist-item');
                    item.style.background = '#d4edda';
                    item.style.borderRight = '4px solid #28a745';
                }
                
                checkbox.addEventListener('change', function() {
                    localStorage.setItem('checkbox_' + index, checkbox.checked);
                });
            });
            
            // Show LinkedIn requirement for year 2 and above
            const currentYear = localStorage.getItem('selectedYear') || '1';
            const linkedinReq = document.getElementById('linkedin-req');
            if (parseInt(currentYear) >= 2) {
                linkedinReq.style.display = 'flex';
            } else {
                linkedinReq.style.display = 'none';
            }
        });
    </script>
</body>
</html>
