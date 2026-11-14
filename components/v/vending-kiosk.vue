<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="koytlfb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vending-kiosk" /></template>
<style>
.koytlfb1l {
  d: path("M5.75 4.75h9v12.5h-9Zm4.5 0v12.5m-4.5-8.5h9m-9 4.25h9m3-6.5h.01M16.75 10h2M6.5 19.5H14");
}

.oeucrxbku {
  d: path("M3.5 2.5h17v19h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
