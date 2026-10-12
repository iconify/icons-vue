<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lxqglyb3j"/><path class="umtymsyts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spear-phishing-sharp" /></template>
<style>
.lxqglyb3j {
  d: path("M2.75 4.25h18.5v16H2.75z");
}

.umtymsyts {
  d: path("M2.75 5.75L12 11.5l9.25-5.75M12 11.5v3.25a2.25 2.25 0 0 1-4.5 0v-1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
