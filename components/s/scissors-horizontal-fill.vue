<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eu0_cqzeq"/><path class="x7eo_40-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scissors-horizontal-fill" /></template>
<style>
.eu0_cqzeq {
  fill: currentColor;
  d: path("M10 6C10 8.2091 8.2091 10 6 10C3.7909 10 2 8.2091 2 6C2 3.7909 3.7909 2 6 2C8.2091 2 10 3.7909 10 6ZM8 6C8 4.8954 7.1046 4 6 4C4.8954 4 4 4.8954 4 6C4 7.1046 4.8954 8 6 8C7.1046 8 8 7.1046 8 6ZM10 18C10 20.2091 8.2091 22 6 22C3.7909 22 2 20.2091 2 18C2 15.7909 3.7909 14 6 14C8.2091 14 10 15.7909 10 18ZM8 18C8 16.8954 7.1046 16 6 16C4.8954 16 4 16.8954 4 18C4 19.1046 4.8954 20 6 20C7.1046 20 8 19.1046 8 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x7eo_40-h {
  d: path("M8.1213 8.1213L21 17M8.1213 15.8787L13.7474 12M17.271 9.5708L21 7");
}

</style>
