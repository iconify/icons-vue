<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sqg0lo97q"/><path class="chf2bbc5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:push-pin-simple-slash-duotone" /></template>
<style>
.chf2bbc5m {
  d: path("M83.25 40a8 8 0 0 1 8-8H192a8 8 0 0 1 0 16h-6.46l18.75 106.3a8 8 0 0 1-6.48 9.26a7.5 7.5 0 0 1-1.4.13a8 8 0 0 1-7.87-6.61L169.29 48h-78a8 8 0 0 1-8.04-8m130.13 181.92a8 8 0 0 1-11.3-.54L168.1 184H136v56a8 8 0 0 1-16 0v-56H40a8 8 0 0 1 0-16h9.29l16.95-96l-24.16-26.62a8 8 0 1 1 11.84-10.76l160 176a8 8 0 0 1-.54 11.3M153.55 168L79.84 86.92L65.54 168Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sqg0lo97q {
  d: path("M190.46 176H56L78.83 46.61A8 8 0 0 1 86.71 40H176l22.34 126.61a8 8 0 0 1-7.88 9.39");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
