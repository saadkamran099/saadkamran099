body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}

.doll {
    position: relative;
    width: 100px;
    height: 200px;
    animation: dance 1s infinite;
}

.head, .body, .left-arm, .right-arm, .left-leg, .right-leg {
    position: absolute;
    background-color: #ffcc00;
    border: 2px solid #333;
}

.head {
    width: 50px;
    height: 50px;
    top: 0;
    left: 25px;
    border-radius: 50%;
}

.body {
    width: 70px;
    height: 100px;
    top: 50px;
    left: 15px;
}

.left-arm {
    width: 20px;
    height: 70px;
    top: 50px;
    left: -20px;
    transform-origin: top right;
    animation: arm-move 1s infinite alternate;
}

.right-arm {
    width: 20px;
    height: 70px;
    top: 50px;
    left: 100px;
    transform-origin: top left;
    animation: arm-move 1s infinite alternate;
}

.left-leg {
    width: 20px;
    height: 70px;
    top: 150px;
    left: 20px;
    transform-origin: top right;
    animation: leg-move 1s infinite alternate;
}

.right-leg {
    width: 20px;
    height: 70px;
    top: 150px;
    left