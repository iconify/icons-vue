<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_zvs3q8k"/><path class="usqhzfceh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-cross-shield" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.usqhzfceh {
  d: path("M10.5 7h3v3h3v3h-3v3h-3v-3h-3v-3h3Z");
}

.x_zvs3q8k {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.75-7.5 10.5C8 19.75 4.5 16 4.5 11V5.5Z");
}

</style>
