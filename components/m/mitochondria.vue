<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g183kpbvl"/><path class="odu_9qkoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mitochondria" /></template>
<style>
.g183kpbvl {
  d: path("M2.5 12c0-3.5 4.25-6.5 9.5-6.5s9.5 3 9.5 6.5s-4.25 6.5-9.5 6.5s-9.5-3-9.5-6.5Z");
}

.odu_9qkoh {
  d: path("m5.25 14l3-5l3 6l3-6l3 6l1.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
