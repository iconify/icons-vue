<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s0a--vbdv"/><path class="y7av6_o7b"/><path class="pvep3lb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-ltv" /></template>
<style>
.pvep3lb8r {
  d: path("M18 14.5V18h3.5");
}

.s0a--vbdv {
  d: path("M12.16 20.5H4v-10l8-7l8 7v1.24");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7av6_o7b {
  d: path("M16 7V4h2v4.75M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
