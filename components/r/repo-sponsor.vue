<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bt8u5dbee"/><path class="wil2nci7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-sponsor" /></template>
<style>
.bt8u5dbee {
  d: path("m3 8.5l2.5-5h11l2.5 5M12.1 19H3V8.5h16V12m-8-8.5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wil2nci7a {
  d: path("M18.25 21.75C15 19.5 14.5 18 14.5 16.75s1-2 2-2c.75 0 1.5.5 1.75 1.25c.25-.75 1-1.25 1.75-1.25c1 0 2 .75 2 2s-.5 2.75-3.75 5Z");
}

</style>
