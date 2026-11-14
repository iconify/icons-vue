<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ed3omfe0o"/><path class="gkol7ubwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouth" /></template>
<style>
.ed3omfe0o {
  d: path("M2.5 12C5 8.5 8 7 10.25 7.75L12 8.5l1.75-.75C16 7 19 8.5 21.5 12c-2.5 3.75-6 5.5-9.5 5.5S5 15.75 2.5 12Z");
}

.gkol7ubwa {
  d: path("M2.5 12c4.5 1 14.5 1 19 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
