Hacking Panda the Bear's Resume

1a $('.profile').attr('src','https://placebear.com/400/400')
1b $('#left-image > img').attr('src', 'https://placebear.com/325/225')
2 $('h1.highlight').text('Nick DAndrea')
3 $('h3.info-title')[1].innerHTML = " Places I've Napped"
4 $('.bar-default')[2].remove()
5 $('body').css('background-color', 'orange')
6 $('.highlight').css('color', 'purple')
7
8 $('.action-icon-bg').css('background-color', 'orange')
9 $('form > input[name="name"]').attr('placeholder', 'identify yourself')
10 $('textarea').attr('placeholder','state your business')
11 $('form > input[name="name"]').attr('value', 'your nemesis')
12 $('form > input[name="email"]').attr('value','koalathebear@gmail.com')
13 $('form > input[type="submit"]').attr('value', 'En garde!')

Adding Elements to the DOM

1 $('#right-image > img').clone().insertAfter('form')
2 for (var i=0; i<10; i++) { $('#right-image > img').clone().insertAfter('form') }
