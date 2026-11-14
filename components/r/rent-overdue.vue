<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a8apebqot"/><path class="xu_socbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rent-overdue" /></template>
<style>
.a8apebqot {
  d: path("M12.5 19h-10V7.5h17v3.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu_socbow {
  d: path("M5 7.5V5h16.5v10.1M5 16.5h.01M17 10h.01M6.25 13.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0H15m-2.25 0v2m2.25-2v.8m-.75 7.7l3.75-7.5l3.75 7.5ZM18 17.5v2");
}

</style>
