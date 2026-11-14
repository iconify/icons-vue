<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ucry3ebqs"/><path class="yq93jtbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:part-time-job" /></template>
<style>
.ucry3ebqs {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM12 2.5v1.75M21.5 12h-1.75M12 21.5v-1.75M2.5 12h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yq93jtbsv {
  d: path("M12 12V6.25A5.75 5.75 0 0 1 17.75 12Zm0-3.5l3.5 3.5");
}

</style>
