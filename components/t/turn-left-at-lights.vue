<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vp9egfbng"/><path class="kewwskp-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turn-left-at-lights" /></template>
<style>
.kewwskp-c {
  d: path("M5.75 7.25L3 10l2.75 2.75M15 2.5h6V15h-6Zm3 3h.01M18 8.75h.01M18 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vp9egfbng {
  d: path("M11 21.5v-8A3.5 3.5 0 0 0 7.5 10H3");
}

</style>
