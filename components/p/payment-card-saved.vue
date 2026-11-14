<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eaq1klboq"/><path class="g12ve7gdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payment-card-saved" /></template>
<style>
.eaq1klboq {
  d: path("M12.6 19H2.5V5h19v8m-19-3.5h19m-19 0h19M6 15h2.5");
}

.g12ve7gdn {
  d: path("M18 21c-1.5-1-3-2.25-3-4c0-1 .75-1.75 1.75-1.75c.65 0 1.05.35 1.25.75c.2-.4.6-.75 1.25-.75c.95 0 1.75.75 1.75 1.75c0 1.75-1.5 3-3 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
