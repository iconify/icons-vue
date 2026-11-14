<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9wq4_wxt"/><path class="v33t3u-yv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voicemail-new" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v33t3u-yv {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.x9wq4_wxt {
  d: path("M5 3.5h3L9.75 8L7.5 9.75c1.25 2.5 4.25 5.5 6.75 6.75L16 14.25L20.5 16v3a2 2 0 0 1-2 2c-8-.5-15-7.5-15.5-15.5a2 2 0 0 1 2-2Z");
}

</style>
