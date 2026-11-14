<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8kb57buq"/><path class="ukyvtbcnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-clearance" /></template>
<style>
.l8kb57buq {
  d: path("M4.575 4.575h7.071l10.253 10.253l-7.071 7.071L4.575 11.646Z");
}

.ukyvtbcnk {
  d: path("M6.788 8.288a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.267 4.949l6.188-.176");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
