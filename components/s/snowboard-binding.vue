<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lpo2rabuz"/><path class="ozkuhdbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowboard-binding" /></template>
<style>
.lpo2rabuz {
  d: path("M5.25 7Q12 8.5 18.75 7a2.75 2.75 0 0 1 2.75 2.75v4.5A2.75 2.75 0 0 1 18.75 17Q12 15.5 5.25 17a2.75 2.75 0 0 1-2.75-2.75v-4.5A2.75 2.75 0 0 1 5.25 7Z");
}

.ozkuhdbye {
  d: path("M6.5 5H10v14H6.5ZM14 5h3.5v14H14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
