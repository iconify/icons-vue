<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tbno81aod"/><path class="obgz74uxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:remit-receive-abroad" /></template>
<style>
.obgz74uxe {
  d: path("m14.5 16l3.75-2c.85-.45 1.85-.1 2.25.75c.2.7-.15 1.45-.75 1.75l-5.5 3.75c-.75.5-1.65.75-2.5.75H2.5M5 7.5l12.5-4l-5 7.5l-2.25-1.75Zm5.25 1.75L17.5 3.5");
}

.tbno81aod {
  d: path("M2.5 14.5H6c1.5 0 2.5-.75 4-.75h3c.8 0 1.5.65 1.5 1.5s-.7 1.5-1.5 1.5h-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
