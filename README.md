samples({
test: ['Screaming%20Marmot.wav'],
goat: ['Goat.wav'],
fein: ['Fein.wav'],
}, 'https://raw.githubusercontent.com/vthevozspotify-dot/strudel-sounds/main/');

$:s('fein').slow(6).gain(0.075)
