# Flash-Vue
Learn anything from anywhere, anytime.


# Introduction
Flash-Vue is an educational progress web application (PWA). The main goal of Flash-Vue is to provide a resource for those needing to memorize, learn or study anything from anywhere at anytime, regarless of their internet connection (thanks to current web technologies).

## TODO:
[] - Fix, altering readonly attribute not compatible on IE
[] - Add birth year field on registration
[] - Make quick how to video for family to see / know how to use
[] - Send 'introductory' email with a '2 things you'd change + your favorite thing'.
[] - Have 3 points menu items open vertically instead of horizontally. Make flex direction column
[] - When mini menu is shown move progress bar as border
[] - Make all stacks (even user's) public. Private stacks will be paid version.
[] - Put laravel in production mode. Can see errors rn (https://flash-vue.com/sdfsdfs)
[] - Remove die() stmts in controllers
[] - Fix shuffle cards. Cannot add, remove correctly after shuffle. On mobile show spinner or something cause you don't know it's shuffling
[] - Joyride or some sort of introduction feature (Sai + how to video)
[] - Google business account (before May 20th).
[] - Test on IE Edge (14+)
[] - Make business cards
[] - Forgot password page, <hr> line not as thick
[] - Remove green border on forms unless you're actually going to have some validation (implement http://vee-validate.logaretm.com/)
[] - Remember to cache AJAX routes (look for axios calls). (may need to use something else besides UpUp since it may not had an array of urls to cache)
[] - WebPack / Gzip: https://forum-archive.vuejs.org/topic/4059/adding-gzip-to-webpack-using-compression-plugin/6
[] - May 19th (soft launch). Before schools starts = real launch.
[/] - Create lots of stacks (aim for 100 before May 20th)
[?] - Show number of cards complete 57/120 - ?
[?] - (User Account) Change category page to not show card, instead show line with [+ (cards)];
[?] - (User Account) Remove play button [autosave instead (on blur)]
[?] - Just like the login prompt on homepage, make one for search (with red dashed border)
[?] - System fonts: https://css-tricks.com/snippets/css/system-font-stack/

## Version 0.7
[x] - Polyfill vuex i need to use for IE 11
[x] - No card animation on night mode (no bounce_leave) [should it be swipe right left styles?]
[x] - Create 404 page (... There's nothing to learn here. Go Back.)
[x] - Show link to study incorrect? Is there a way we are storing incorrect right now?
[x] - Fix border under mini_menu and background when bg is in night mode
[x] - User/public score is a large decimal number. Make sure to round to whole number
[x] - Add order to public stacks so that you can order them w/ something other than asc/desc create date
[x] - Shrink text a tad on desktop if chars > ??. Shrink even more on mobile if chars > ??
[x] - After resetting password sending user to https://flash-vue.com/home still maybe this?(return $this->to($this->generator->route('home'), $status);)

## Version 0.5 - Quiz Mode!
[x] - Start quiz / Quiz Mode toggle. Send toggle answer to controller, wrapper query in if(quizMode = true)
[x] - Card correct (animate slide left). Incorrect (Animate slide right). Really think, maybe talk to ppl about this

## Version 0.4
[x] - V-model.trim on textarea and v-models
[x] - Get tab / enter working (tab press enter on save for example)
[X] - Get menu working!
[X] - Stub in 'no results', instructions how to add cards / stacks
[X] - Get public menu working (look in email for code)

## Version 0.3
[x] - Text is mispelled on HP. Login to create "your" own
[x] - Touch textarea on stack -> go to cards. touch card flip to other side
[x] - No loader on card view only when clicking from stack view (only when refreshing on card view...)
[x] - Remove being able to click on textarea public/user cards. Turn cards on touch instead
[x] - On user cards, set textarea to readonly unless edit icon is clicked. Only allow edit on cards via the edit icon
[x] - Forgot password link not working

## VERSION 0.25
[x] - On md/sm devices set .column_no_pad_lr {padding: 0.75rem}
[x] - User login count in DB (user_login_total++)
[x] - Email admin after a registration is made
[x] - After registering send user to welcome page, thanks for signing up, get started by creating a stack. - Just like the login prompt on homepage, make one for new registrations page. (with red dashed border). Also have a thanks for registering
[x] - Add your running ToDo: list to Asana
[x] - Add a message saying Coming May 20th, but you can use
[x] - Get email on registration working (need to add the new columns for login_count to user table)
[x] - Remove border around 'login' / 'registraion' form


## VERSION 0.2
[x] - Move app icons (shuffle, add, share) a bit further out. can see them on iPad
[x] - Answers first mode
[x] - On night mode, set all questions to display:inherit. Or all answers depending on toggle setting (- Display inherit / display question on night mode toggle (some cards are not being shown now))
[x] - Make toggle buttons bigger. Hard to touch on mobile
[x] - On load, check textarea character length. Only working on keydown right. (make regular, small, tiny font)
[x] - Active, focus buttons on public stacks are color: black? Should be the grey like on public-cards
[x] - Spread out submenu buttons on cards. Almost clicking delete when I trying to click share

## VERSION 0.1
[x] - Web manifest file
[x] - Progress bar on Public-Cards is not working correctly
[x] - Shorten the time from when user click "check" and card = display none. There's an obvious pause on mobile
[x] - Display inline toggles
[x] - Change check mark to happy face / X to sad face
[x] - Progress bar not working on public-cards
[x] - On the logo link remove './' and add '/' instead. right now if clicked it goes to that domain level

## VERSION 0.0
[x] - Clone current droplet
[x] - On register, send to user-stacks page (going to home rn)
[x] - Move search icon in menu down (there's a gap)
[x] - Set up Forge account
[x] - Get intend link to click not icon (search for: // remove save add edit icon) - Need get link not icon so you may have to change ElementById stmt
[x] - Check if element has class (search for: // NEED TO FIX - RIGHT NOW CARD SPINS
[x] - And search for "component.$store.dispatch('editCardName', card);")
[x] - Search for: // SHOULD ALSO FIND BY CAT_ID TO NOT OVERRIDDE ANOTHER BY ACCIDENT
[x] - Search for: let focusCard = component.$store.state; - This is not working on add card

