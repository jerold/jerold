# Hi there, I'm Jerold! 👋

## Welcome to my GitHub profile!

I am a Senior Software Engineer with 15+ years of experience in tech. I possess a proven ability to deliver across full-stack development, encompassing Web (Dart, TypeScript), Mobile (Flutter, Swift, Kotlin), and Server-side (Java, Kotlin, Go) technologies. My expertise is in responsive ui construction, state management, as well as API design and versioning, with robust testing (Golden Toolkit, Puppeteer) and observability practices (Firebase Crashlytics, Splunk, OpenTelemetry, NewRelic, Grafana).

## I work in stacks that use these languages and frameworks
<p align="center">
      <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="55" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="java" width="65" height="65"/> 
      <img src="https://www.vectorlogo.zone/logos/java/java-icon.svg" alt="java" width="65" height="65"/> 
      <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="55" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="azure" width="55" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/swift/swift-icon.svg" alt="java" width="65" height="65"/> 
      <img src="https://www.vectorlogo.zone/logos/nodejs/nodejs-icon.svg" alt="Nodejs" width="55" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="GIT" width="55" height="55"/> 
      <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="55" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/docker/docker-official.svg" alt="docker" width="60" height="50"/>
      <img src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="mysql" width="45" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" alt="mysql" width="45" height="55"/>
      <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="python" width="55" height="55"/>
</p>

## Featured Personal Projects

### [Eve Online 3D Map](https://jerold.cc/)
I wrote the 3D renderer for this in Javascript, and scraped Eve Online’s public api for the map data. It was an exercise in coding some of my Linear Algebra lessons. Instead of using a 3D canvas, it works out how to translate and render the 3D data to a 2D viewport. I’ve since iterated on this renderer to display LIDAR .ply files, and it can also render animated polygons, but I’ve always liked the way this map turned out, so this is the one I keep hosted.

### [Retro Arcade Game](https://jerold.github.io/retro-arcade-game/#/c1)
I originally set out with the goal of training an ANFIS that could play Tetris indefinitely. I coded the game up to follow the “bag system” tetroid-generation rules introduced in 1999. I then set to work writing an agent that would play the game moderately well, to produce training data for a neural network.

I never quite got the neural network to a point where it could beat its predecessor. But the original agent I wrote is kind of unstoppable. It works by looking ahead through weighted permutations of the current and 3 subsequent board states (one for each visible piece in the queue) and picks moves by trying to maximize score while minimizing the number of voids it creates.

You can change the url parameters for “p1” to play the game yourself (arrows + enter to drop), “pvp” to play with a friend (a/s/d/f + space), or “pvc” to play against the computer, good luck! + and - increase and decrease the AI’s play speed.

### [Retroboard](https://retroboard.net/)
This is my most popular personal project. I wrote it to help proctor team retrospectives, but my partner and I use it for a collaborative shopping list. I use it as a personal Now-Next-Near-Never planning board. And it has active users from all over the world.

### [Wordle Helper](https://jerold.github.io/wordle/#/play)
I built this after watching the 3Blue1Brown Information Theory video about Wordle. It applies the principles from that video to suggest words that provide the greatest amount of information per turn. Or at least it does if you remove the “play” url parameter. Otherwise it just lets you play Wordle indefinitely.

### [Sudoku Helper](https://jerold.github.io/sudoku/)
You might be noticing a trend… When I get into a puzzle game I tend to want to write a “helper” that ultimately ends up playing the game for me. This Helper will randomly load a pre-programmed sudoku and start offering suggestions for solving it. You can clear the board and enter the state of one you might be noodling on personally and it will provide suggestions. The next arrow will apply those suggestions and repeat. The color coding indicates the strategy used to remove candidates or make logical selections. Someday I’ll provide a key for the colors.

### [Catan Helper](https://jerold.github.io/Catan)
Yup, another Helper. Although it generates a random board when loaded, you can reset the board to one you might be about to play, and this helper will take into account the odds of a resource tile being rolled during the game and suggest some possibly fortuitous starting locations for your first two buildings.

## Contributions on my other github account: [jeroldalbertson-wf](https://github.com/jeroldalbertson-wf)
[![jeroldalbertson-wf Contributions](https://ghchart.rshah.org/jeroldalbertson-wf)](https://github.com/jeroldalbertson-wf)

Feel free to reach out if you have any questions or would like to collaborate!
