<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o58757jpd"/><path class="ov-jvtb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:metaverse" /></template>
<style>
.o58757jpd {
  d: path("M6.5 6.5h11A2.5 2.5 0 0 1 20 9v6a2.5 2.5 0 0 1-2.5 2.5h-2l-2.5-2h-2l-2.5 2h-2A2.5 2.5 0 0 1 4 15V9a2.5 2.5 0 0 1 2.5-2.5Z");
}

.ov-jvtb9l {
  d: path("M6.75 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4 9.5H2.5v5H4m16-5h1.5v5H20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
