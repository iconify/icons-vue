<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mr324tbut"/><path class="u0tfz3bae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sink-fill" /></template>
<style>
.mr324tbut {
  fill: currentColor;
  d: path("M22 13C22.552 13 23 13.448 23 14C23 14.552 22.552 15 22 15H21V19C21 21.209 19.2092 23 17 23H7C4.7908 23 3 21.209 3 19V15H2C1.4477 15 1 14.552 1 14C1 13.448 1.4477 13 2 13H22Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0tfz3bae {
  d: path("M12 14V5C12 3.343 13.3431 2 15 2C16.6569 2 18 3.343 18 5V6M16 14V11C16 10.448 16.4477 10 17 10H20M8 14V11C8 10.448 7.5523 10 7 10H4");
}

</style>
