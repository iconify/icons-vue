<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7ek65bgo"/><path class="hp5g1ymeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:new-build" /></template>
<style>
.hp5g1ymeh {
  d: path("M6.5 21.5V18h3v3.5");
}

.t7ek65bgo {
  d: path("m3 15l5-4.5l5 4.5v6.5H3Zm15.5 6.5v-19m-14 3h17M8 5.5v2m8.5 14h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
