<template>
  <div class="min-h-screen">
    <header>
      <div class="text-center py-4">
        <h1 class="font-bold text-2xl">GLOXINIA Sites Sample</h1>
        <p>GLOXINIA の Web サイト制作のサンプルです。</p>
      </div>
    </header>
    <main>
      <div class="w-full max-w-3xl mx-auto">
        <slot />
      </div>
    </main>
    <footer>
      <div class="text-center text-sm py-4">
        <p>FOOTER</p>
      </div>
    </footer>
  </div>
</template>
