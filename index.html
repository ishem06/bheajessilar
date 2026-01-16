<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matcha Delivery</title>
    <style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
    }

    .container {
        position: relative;
        width: 100%;
        max-width: 500px;
        height: 600px;
        perspective: 1000px;
    }

    /* Delivery Man */
    .delivery-man {
        position: absolute;
        left: -200px;
        top: 50%;
        transform: translateY(-50%);
        width: 150px;
        height: 150px;
        background: #FFE5B4;
        border-radius: 50% 50% 40% 40%;
        transition: all 2s ease-in-out;
        z-index: 10;
        opacity: 0;
    }

    .delivery-man.moving {
        left: 50%;
        transform: translate(-50%, -50%);
        opacity: 1;
    }

    .delivery-man.exit {
        left: 120%;
        opacity: 0;
        transform: translate(-50%, -50%) scale(0.5);
    }

    .delivery-man::before {
        content: '🚴';
        font-size: 100px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    /* Order Button */
    .order-btn {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        padding: 20px 40px;
        font-size: 24px;
        background: linear-gradient(135deg, #88cc88 0%, #5d9c5d 100%);
        color: white;
        border: none;
        border-radius: 50px;
        cursor: pointer;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        transition: all 0.3s ease;
        z-index: 5;
    }

    .order-btn:hover {
        transform: translate(-50%, -50%) scale(1.1);
        box-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
    }

    .order-btn.hidden {
        opacity: 0;
        pointer-events: none;
    }

    /* Matcha Cup */
    .matcha-container {
        position: absolute;
        top: 50%;
        right: -300px;
        transform: translateY(-50%) scale(0);
        opacity: 0;
        transition: all 0.8s ease;
        z-index: 3;
        pointer-events: none;
    }

    .matcha-container.show {
        right: 80px;
        transform: translateY(-50%) scale(1);
        opacity: 1;
        pointer-events: auto;
    }

    .matcha-cup {
        width: 200px;
        height: 250px;
        background: linear-gradient(180deg, #f5f5dc 0%, #e8e8d0 100%);
        border-radius: 20px 20px 40px 40px;
        position: relative;
        box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        cursor: grab;
    }

    .matcha-cup.dragging {
        cursor: grabbing;
    }

    .matcha-lid {
        width: 220px;
        height: 30px;
        background: linear-gradient(180deg, #8B7355 0%, #6F5D4E 100%);
        border-radius: 50%;
        position: absolute;
        top: -10px;
        left: -10px;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }

    .matcha-liquid {
        width: 180px;
        height: 180px;
        background: linear-gradient(180deg, #a8d5a8 0%, #7fb77f 100%);
        position: absolute;
        bottom: 20px;
        left: 10px;
        border-radius: 10px 10px 30px 30px;
        animation: bubble 2s infinite;
    }

    @keyframes bubble {

        0%,
        100% {
            transform: translateY(0);
        }

        50% {
            transform: translateY(-5px);
        }
    }

    .straw {
        width: 8px;
        height: 150px;
        background: linear-gradient(180deg, #ff6b6b 0%, #ee5555 100%);
        position: absolute;
        top: -30px;
        left: 50%;
        transform: translateX(-50%) rotate(-5deg);
        border-radius: 10px;
    }

    /* Sticky Note with Poem */
    .sticky-note {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) rotate(-3deg) scale(0);
        width: 320px;
        background: #feff9c;
        padding: 25px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        font-family: 'Courier New', monospace;
        font-size: 14px;
        line-height: 1.8;
        color: #333;
        border-radius: 3px;
        opacity: 0;
        transition: all 0.8s ease;
        z-index: 10;
        cursor: pointer;
    }

    .sticky-note.show {
        transform: translate(-50%, -50%) rotate(-3deg) scale(1);
        opacity: 1;
    }

    .sticky-note::before {
        content: '';
        position: absolute;
        top: -10px;
        left: 50%;
        transform: translateX(-50%);
        width: 60px;
        height: 20px;
        background: rgba(0, 0, 0, 0.1);
        border-radius: 5px;
    }

    .poem-text {
        text-align: left;
        font-size: 13px;
    }

    /* Receive Button */
    .receive-btn {
        position: absolute;
        bottom: 50px;
        left: 50%;
        transform: translateX(-50%) scale(0);
        padding: 15px 35px;
        font-size: 18px;
        background: linear-gradient(135deg, #ff6b6b 0%, #ee5555 100%);
        color: white;
        border: none;
        border-radius: 50px;
        cursor: pointer;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        transition: all 0.3s ease;
        opacity: 0;
        z-index: 5;
    }

    .receive-btn.show {
        transform: translateX(-50%) scale(1);
        opacity: 1;
    }

    .receive-btn:hover {
        transform: translateX(-50%) scale(1.1);
        box-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
    }

    /* Thank You Message */
    .thank-you {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(0);
        opacity: 0;
        text-align: center;
        color: white;
        font-size: 36px;
        font-weight: bold;
        text-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
        transition: all 0.8s ease;
        z-index: 15;
        cursor: pointer;
    }

    .thank-you.show {
        transform: translate(-50%, -50%) scale(1);
        opacity: 1;
    }

    .heart {
        font-size: 48px;
        animation: heartbeat 1.5s infinite;
    }

    @keyframes heartbeat {

        0%,
        100% {
            transform: scale(1);
        }

        50% {
            transform: scale(1.2);
        }
    }
    </style>
</head>

<body>
    <div class="container">
        <!-- Order Button -->
        <button class="order-btn" id="orderBtn">Order Matcha 🍵</button>

        <!-- Delivery Man -->
        <div class="delivery-man" id="deliveryMan"></div>

        <!-- Matcha with Poem -->
        <div class="sticky-note" id="stickyNote">
            <div class="poem-text">
                Ten months move like a steady tide,<br>
                Nothing forced, just you by my side.<br>
                Days unfold, simple and true,<br>
                Finding their rhythm just being with you.<br>
                I never get tired of reminding you this—<br>
                That you are beautiful, always, without a miss.<br>
                Not just to say it, but to show it each day,<br>
                In quiet ways words don't always say.<br>
                And I'm proud of you, more than it shows,<br>
                For how you stand, for how you grow.<br>
                If time keeps asking what comes next,<br>
                My answer stays easy—I'd choose you again.
            </div>
        </div>

        <div class="matcha-container" id="matchaContainer">
            <div class="matcha-cup">
                <div class="matcha-lid"></div>
                <div class="straw"></div>
                <div class="matcha-liquid"></div>
            </div>
        </div>

        <!-- Receive Button -->
        <button class="receive-btn" id="receiveBtn">Receive Order 💚</button>

        <!-- Thank You Message -->
        <div class="thank-you" id="thankYou">
            <div class="heart">💚</div>
            <div>Happy 10th Matcharry Prettiest</div>
            <div style="font-size: 18px; margin-top: 10px; font-weight: normal;">(sorry virtual matcha muna for now
                bahite pa kasi)</div>
        </div>
    </div>

    <script>
    const orderBtn = document.getElementById('orderBtn');
    const deliveryMan = document.getElementById('deliveryMan');
    const matchaContainer = document.getElementById('matchaContainer');
    const stickyNote = document.getElementById('stickyNote');
    const receiveBtn = document.getElementById('receiveBtn');
    const thankYou = document.getElementById('thankYou');

    let isDragging = false;
    let currentX;
    let currentY;
    let initialX;
    let initialY;
    let xOffset = 0;
    let yOffset = 0;

    orderBtn.addEventListener('click', () => {
        // Hide order button
        orderBtn.classList.add('hidden');

        // Delivery man arrives
        deliveryMan.classList.add('moving');

        // After delivery man arrives, show matcha
        setTimeout(() => {
            matchaContainer.classList.add('show');
            receiveBtn.classList.add('show');
        }, 2000);
    });

    receiveBtn.addEventListener('click', () => {
        // Hide receive button
        receiveBtn.style.opacity = '0';
        receiveBtn.style.pointerEvents = 'none';

        // Delivery man exits immediately
        deliveryMan.classList.add('exit');

        // Show sticky note with poem
        setTimeout(() => {
            stickyNote.classList.add('show');
        }, 500);
    });

    // Click sticky note to dismiss and show anniversary message
    stickyNote.addEventListener('click', () => {
        stickyNote.classList.remove('show');

        // Show anniversary message
        setTimeout(() => {
            thankYou.classList.add('show');
        }, 500);
    });

    // Click anniversary message to dismiss and enable dragging
    thankYou.addEventListener('click', () => {
        thankYou.classList.remove('show');

        setTimeout(() => {
            matchaContainer.style.cursor = 'grab';
            enableDragging();
        }, 500);
    });

    function enableDragging() {
        matchaContainer.addEventListener('mousedown', dragStart);
        matchaContainer.addEventListener('touchstart', dragStart);
        document.addEventListener('mousemove', drag);
        document.addEventListener('touchmove', drag);
        document.addEventListener('mouseup', dragEnd);
        document.addEventListener('touchend', dragEnd);
    }

    function dragStart(e) {
        if (e.type === 'touchstart') {
            initialX = e.touches[0].clientX - xOffset;
            initialY = e.touches[0].clientY - yOffset;
        } else {
            initialX = e.clientX - xOffset;
            initialY = e.clientY - yOffset;
        }

        if (e.target === matchaContainer || matchaContainer.contains(e.target)) {
            isDragging = true;
            matchaContainer.style.cursor = 'grabbing';
        }
    }

    function drag(e) {
        if (isDragging) {
            e.preventDefault();

            if (e.type === 'touchmove') {
                currentX = e.touches[0].clientX - initialX;
                currentY = e.touches[0].clientY - initialY;
            } else {
                currentX = e.clientX - initialX;
                currentY = e.clientY - initialY;
            }

            xOffset = currentX;
            yOffset = currentY;

            setTranslate(currentX, currentY, matchaContainer);
        }
    }

    function dragEnd(e) {
        initialX = currentX;
        initialY = currentY;
        isDragging = false;
        matchaContainer.style.cursor = 'grab';
    }

    function setTranslate(xPos, yPos, el) {
        el.style.transform = `translate(calc(-50% + ${xPos}px), calc(-50% + ${yPos}px)) scale(1)`;
    }
    </script>
</body>

</html>
