<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Envelope + Letter (Open/Close on Click)</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class="container">
        <div class="envelope-wrapper">
            <div class="envelope">
                <div class="letter">
                    <div class="text">
                        <strong>happy birthday parth.</strong>
                        <p>
                            ok, idk much about coding but this one is for you,
                            i'll pray that you'll always be happy & achieve everything and become successful.
                            I Love you in every universe and miss you🥺, lastly, a very happy birthday🧿❤
                        </p>
                    </div>
                </div>
            </div>
            <div class="heart"></div>
        </div>
    </div>
    <script>
        const envelope = document.querySelector('.envelope-wrapper');
        envelope.addEventListener('click', () => {
            envelope.classList.toggle('flap');
        });
    </script>
</body>
</html>

