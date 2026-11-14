<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zpc0mrzbr"/><path class="nasrfzbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moon-crescent" /></template>
<style>
.nasrfzbjy {
  d: path("M9.25 3.5A9.5 9.5 0 0 0 20.5 14.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpc0mrzbr {
  d: path("M20.5 14.75A9.25 9.25 0 1 1 9.25 3.5");
}

</style>
