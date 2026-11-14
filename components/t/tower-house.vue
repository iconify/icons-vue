<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b6o45zayg"/><path class="bvig7hbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tower-house" /></template>
<style>
.b6o45zayg {
  d: path("m12 2.5l5.5 6v13h-11v-13Z");
}

.bvig7hbee {
  d: path("M10.5 10.5h3v3h-3Zm0 11V18a1.5 1.5 0 0 1 3 0v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
