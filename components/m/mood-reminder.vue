<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u-cunt61y"/><path class="dx87l4b8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-reminder" /></template>
<style>
.dx87l4b8k {
  d: path("M13.75 5.969a3.5 3.5 0 0 1 0 6.062");
}

.u-cunt61y {
  d: path("M12 2.5V4M6 16v-6a6 6 0 0 1 12 0v6l1.5 2h-15Zm4.25 5h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
