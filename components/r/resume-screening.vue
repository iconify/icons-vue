<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="smxqastlt"/><path class="vuvzlubjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:resume-screening" /></template>
<style>
.smxqastlt {
  d: path("M14.4 21.5H4.5v-19h15v9.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vuvzlubjq {
  d: path("M8 6h4.5v4.5H8Zm0 7.5h2.1M8 17h3.5m3.25-2h6.5l-2.5 3.25v3.25l-1.5-.75v-2.5Z");
}

</style>
