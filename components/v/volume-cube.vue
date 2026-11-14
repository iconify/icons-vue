<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ysktjc-qn"/><path class="znd7msbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volume-cube" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysktjc-qn {
  d: path("m12 2.5l8.5 4.75v9.5L12 21.5l-8.5-4.75v-9.5Z");
}

.znd7msbjk {
  d: path("M3.5 7.25L12 12l8.5-4.75M12 12v9.5");
}

</style>
