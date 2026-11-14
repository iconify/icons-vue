<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i3z7hwj_o"/><path class="dl7i3cc7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:schedule-repeat" /></template>
<style>
.dl7i3cc7n {
  d: path("M13.75 19.5L15 18.25l1.25 1.25");
}

.i3z7hwj_o {
  d: path("M10.8 20.5H3.5V5h17v8M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 10h17M7 13.75h2.75M7 17.25h2.75m8.25-2a3 3 0 1 1-3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
