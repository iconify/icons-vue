<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i7a142y6o"/><path class="d9xz6_bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-sparkle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d9xz6_bkx {
  d: path("m14.986 5l.003-.001c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L17 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L19 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 7a1 1 0 0 1 0-2M3 5h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6 0h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M3 17h8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m18 0a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

.i7a142y6o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m6 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
