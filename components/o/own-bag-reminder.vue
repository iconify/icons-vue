<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m8x-8byko"/><path class="qi-_nrrxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:own-bag-reminder" /></template>
<style>
.m8x-8byko {
  d: path("M12.5 21.5h-10V10h14v1.6M4 10c0-7 6.5-7 6.5 0");
}

.qi-_nrrxq {
  d: path("M8.5 10c0-7 6.5-7 6.5 0M2.5 15h9.7m2.05 3a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM18 16v2m0 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
