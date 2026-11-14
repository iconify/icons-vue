<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n253icclv"/><path class="evqivv0mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vitamin-drops" /></template>
<style>
.evqivv0mh {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-3v6m-2.5-4.5l5 3m-5 0l5-3");
}

.n253icclv {
  d: path("M6.5 10h11v11.5h-11Zm4-2V5c0-2 3-2 3 0v3M8.75 8h6.5v2h-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
