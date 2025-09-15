<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./src/style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adam Keyes Portfolio</title>
  </head>
  <body class="min-h-screen flex flex-col items-center" style="background: var(--clr-gray-900); color: var(--clr-white);">
    <!-- Header -->
    <header class="w-full flex flex-col items-center pt-6">
      <span class="font-bold text-lg mb-4">adamkeyes</span>
      <div class="flex gap-4 mb-4">
        <a href="#" aria-label="GitHub"><img src="github.svg" alt="" class="w-5 h-5"></a>
        <a href="#" aria-label="LinkedIn"><img src="linkedin.svg" alt="" class="w-5 h-5"></a>
        <a href="#" aria-label="Twitter"><img src="twitter.svg" alt="" class="w-5 h-5"></a>
      </div>
      <img src="profile.jpg" alt="Adam Keyes" class="w-40 h-40 object-cover rounded mb-6 grayscale" />
    </header>

    <!-- Hero -->
    <section class="w-full flex flex-col items-center px-4">
      <h1 class="text-2xl font-bold text-center mb-2" style="color: var(--clr-white);">
        Nice to meet you!<br />I’m Adam Keyes.
      </h1>
      <p class="text-center text-sm mb-4" style="color: var(--clr-gray-300); max-width: 300px;">
        Based in the UK, I’m a front-end developer passionate about building accessible web apps that users love.
      </p>
      <a href="#contact" class="px-4 py-1 rounded text-xs font-semibold mt-2 mb-6" style="background: var(--clr-green); color: var(--clr-gray-900);">
        CONTACT ME
      </a>
    </section>

    <!-- Skills -->
    <hr class="w-4/5 my-6 border-t" style="border-color: var(--clr-gray-800);" />
    <section class="w-full flex flex-col items-center px-4">
      <div class="flex flex-col gap-4 w-full max-w-xs">
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">HTML</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">4 Years Experience</div>
        </div>
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">CSS</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">4 Years Experience</div>
        </div>
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">JavaScript</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">4 Years Experience</div>
        </div>
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">Accessibility</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">4 Years Experience</div>
        </div>
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">TailwindCss</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">3 Years Experience</div>
        </div>
        <div class="text-center">
          <span class="font-bold" style="color: var(--clr-white);">Sass</span>
          <div class="text-xs" style="color: var(--clr-gray-400);">3 Years Experience</div>
        </div>
      </div>
    </section>
    <hr class="w-4/5 my-6 border-t" style="border-color: var(--clr-gray-800);" />

    <!-- Projects -->
    <section class="w-full flex flex-col items-center px-4">
      <div class="flex flex-col items-center w-full">
        <h2 class="text-xl font-bold mb-2" style="color: var(--clr-white);">Projects</h2>
        <a href="#contact" class="px-4 py-1 rounded text-xs font-semibold mb-4" style="background: var(--clr-green); color: var(--clr-gray-900);">
          CONTACT ME
        </a>
      </div>
      <div class="flex flex-col gap-6 w-full max-w-xs">
        <!-- Project 1 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project1.jpg" alt="Design Portfolio" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">DESIGN PORTFOLIO</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project2.jpg" alt="E-Learning Landing Page" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">E-LEARNING LANDING PAGE</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project3.jpg" alt="Todo Web App" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">TODO WEB APP</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS JAVASCRIPT</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
        <!-- Project 4 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project4.jpg" alt="Entertainment Web App" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">ENTERTAINMENT WEB APP</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS JAVASCRIPT</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
        <!-- Project 5 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project5.jpg" alt="Memory Game" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">MEMORY GAME</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS JAVASCRIPT</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
        <!-- Project 6 -->
        <div class="rounded overflow-hidden" style="background: var(--clr-gray-800);">
          <img src="project6.jpg" alt="Art Gallery Showcase" class="w-full h-32 object-cover" />
          <div class="p-3">
            <h3 class="font-bold text-base mb-1" style="color: var(--clr-white);">ART GALLERY SHOWCASE</h3>
            <div class="text-xs mb-2" style="color: var(--clr-gray-400);">HTML CSS JAVASCRIPT</div>
            <div class="flex gap-2">
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW PROJECT</a>
              <a href="#" class="text-xs font-semibold underline" style="color: var(--clr-green);">VIEW CODE</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="w-full mt-10 px-4 py-8" style="background: var(--clr-gray-800);">
      <h2 class="text-xl font-bold mb-4" style="color: var(--clr-white);">Contact</h2>
      <p class="mb-4 text-sm" style="color: var(--clr-gray-300); max-width: 350px;">
        I would love to hear about your project and how I could help. Please fill in the form, and I’ll get back to you as soon as possible.
      </p>
      <form class="flex flex-col gap-4 max-w-xs">
        <input type="text" placeholder="NAME" class="bg-transparent border-b py-2 px-1 text-sm focus:outline-none" style="border-color: var(--clr-gray-400); color: var(--clr-white);" />
        <input type="email" placeholder="EMAIL" class="bg-transparent border-b py-2 px-1 text-sm focus:outline-none" style="border-color: var(--clr-gray-400); color: var(--clr-white);" />
        <textarea placeholder="MESSAGE" class="bg-transparent border-b py-2 px-1 text-sm focus:outline-none" style="border-color: var(--clr-gray-400); color: var(--clr-white);"></textarea>
        <button type="submit" class="self-end px-4 py-1 rounded text-xs font-semibold mt-2" style="background: var(--clr-green); color: var(--clr-gray-900);">
          SEND MESSAGE
        </button>
      </form>
    </section>

    <!-- Footer -->
    <footer class="w-full flex flex-col items-center py-4" style="background: var(--clr-gray-900);">
      <span class="font-bold text-lg mb-2">adamkeyes</span>
      <div class="flex gap-4">
        <a href="#" aria-label="GitHub"><img src="github.svg" alt="" class="w-5 h-5"></a>
        <a href="#" aria-label="LinkedIn"><img src="linkedin.svg" alt="" class="w-5 h-5"></a>
        <a href="#" aria-label="Twitter"><img src="twitter.svg" alt="" class="w-5 h-5"></a>
      </div>
    </footer>
  </body>
</html>