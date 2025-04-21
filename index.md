---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<!-- Hero Section - Updated to match example -->
<section class="min-h-fit pt-32 flex flex-col justify-center items-center text-center px-4">
  <div class="mb-12 max-w-4xl">
    <svg class="w-20 h-20 mx-auto mb-8" viewBox="0 0 24 24" fill="none" xmlns="http:/ www.w3.org/2000/svg">
      <path
        d="M3 8L7.89 10.26C11.9 12.1 12.1 12.1 16.11 10.26L21 8M3 8L12 12M3 8V16L12 20M12 12V20M12 12L21 8M12 20L21 16V8"
        stroke="#a855f7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
    </svg>
    <h1 class="text-6xl font-bold mb-6">
      <span class="text-white">Hello</span>
      <span class="text-accent-500">People</span>...
    </h1>
    <h2 class="text-6xl font-bold mb-10">
      <span class="text-white">meet</span>
      <span class="text-primary-400">Jusondac</span>!
    </h2>
    <p class="text-xl text-gray-400 max-w-2xl mx-auto mb-8">Full-stack Ruby on Rails Developer crafting elegant,
      efficient web solutions</p>

    <div class="flex justify-center gap-4 mb-10">
      <span class="bg-gray-700 px-3 py-1 rounded text-sm font-medium">
        <span class="text-gray-400">experience</span>
        <span class="text-white ml-1">5+ years</span>
      </span>
      <span class="bg-blue-900 px-3 py-1 rounded text-sm font-medium">
        <span class="text-blue-400">speciality</span>
        <span class="text-white ml-1">Rails</span>
      </span>
      <span class="bg-purple-900 px-3 py-1 rounded text-sm font-medium">
        <span class="text-purple-400">projects</span>
        <span class="text-white ml-1">15+</span>
      </span>
    </div>

    {% include button_nav.html %}
  </div>

</section>