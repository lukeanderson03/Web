---
layout: layouts/base.njk
title: Home
---

<main class="py-16">
  <div class="max-w-4xl mx-auto text-left">
    <h1 class="text-4xl font-bold max-w-100">Elevating websites one line at a time</h1>
    <p class="mt-4 text-gray-600 max-w-80">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque at veniam autem consectetur numquam animi. Odio vel nostrum delectus quibusdam, dicta id tempora impedit! Quod odio ducimus modi praesentium veniam.</p>
    <div class="mt-6 space-x-4">
      <a href="#projects" class="bg-blue-600 text-white px-4 py-2 rounded">Projects</a>
      <a href="#contact" class="bg-blue-600 text-white px-4 py-2 rounded">Contact</a>
    </div>
  </div>
</main>

<section>

</section>

<section id="contact" class="py-16">

  <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
    <div>
      <h2 class="text-2xl font-semibold mb-4">Contact Me</h2>
      <form class="space-y-4">
        <div class="grid grid-cols-2 gap-4">
          <input type="text" placeholder="First Name" class="border p-2 w-full" />
          <input type="text" placeholder="Last Name" class="border p-2 w-full" />
        </div>
        <input type="email" placeholder="Email Address" class="border p-2 w-full" />
        <textarea placeholder="Message" class="border p-2 w-full h-32"></textarea>
        <button class="bg-blue-600 text-white px-4 py-2 rounded" type="submit">Send</button>
      </form>
    </div>
    <div class="bg-gray-200 h-64 md:h-auto"></div>
  </div>
</section>
