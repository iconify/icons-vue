<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nasyt3bce"/><path class="hyiitqbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:release-paused" /></template>
<style>
.hyiitqbus {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10m4.75-5.75v5.75m3.5-5.75v5.75");
}

.nasyt3bce {
  d: path("M13.976 20.454L12 21.5L3.5 17V7L12 2.5L20.5 7v5.982");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
