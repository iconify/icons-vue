<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="w8985q_4s"/><path class="vwe4p5b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:user-gear-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vwe4p5b8a {
  d: path("M144 157.68a68 68 0 1 0-71.9 0c-20.65 6.76-39.23 19.39-54.17 37.17a8 8 0 1 0 12.24 10.3C50.25 181.19 77.91 168 108 168s57.75 13.19 77.87 37.15a8 8 0 0 0 12.26-10.3c-14.95-17.78-33.53-30.41-54.13-37.17M56 100a52 52 0 1 1 52 52a52.06 52.06 0 0 1-52-52m196.25 43.07l-4.66-2.69a23.6 23.6 0 0 0 0-8.76l4.66-2.69a8 8 0 1 0-8-13.86l-4.67 2.7a23.9 23.9 0 0 0-7.58-4.39V108a8 8 0 0 0-16 0v5.38a23.9 23.9 0 0 0-7.58 4.39l-4.67-2.7a8 8 0 1 0-8 13.86l4.66 2.69a23.6 23.6 0 0 0 0 8.76l-4.66 2.69a8 8 0 0 0 8 13.86l4.67-2.7a23.9 23.9 0 0 0 7.58 4.39V164a8 8 0 0 0 16 0v-5.38a23.9 23.9 0 0 0 7.58-4.39l4.67 2.7a7.9 7.9 0 0 0 4 1.07a8 8 0 0 0 4-14.93M224 144a8 8 0 1 1 8-8a8 8 0 0 1-8 8");
}

.w8985q_4s {
  d: path("M168 100a60 60 0 1 1-60-60a60 60 0 0 1 60 60");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
