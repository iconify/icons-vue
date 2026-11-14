<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="igixmxb1p"/><path class="k-4movitg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newspaper-kiosk" /></template>
<style>
.igixmxb1p {
  d: path("m2.5 7.5l19-4.75M4.5 7v14h15V3.25M4.5 14h15");
}

.k-4movitg {
  d: path("M8.5 14v-3.5l3.5 1l3.5-1V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
