<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z431fbcen"/><path class="l2od_-b7c"/><path class="hp-9o5-ku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:velocity" /></template>
<style>
.hp-9o5-ku {
  d: path("m17.5 3l3 3l-3 3");
}

.l2od_-b7c {
  d: path("M4.5 16.5c0-6 5.5-10.5 16-10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z431fbcen {
  d: path("M2.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
