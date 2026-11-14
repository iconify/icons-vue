<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="te_8rybox"/><path class="z2jqbg-ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:peephole" /></template>
<style>
.te_8rybox {
  d: path("M5.5 21.5V4A1.5 1.5 0 0 1 7 2.5h10A1.5 1.5 0 0 1 18.5 4v17.5M3 21.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2jqbg-ei {
  d: path("M9.25 8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm2.75 0h.01M15.5 13v2.5");
}

</style>
