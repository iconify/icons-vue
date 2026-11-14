<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ayc178dru"/><path class="r3843ibrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rain-drop" /></template>
<style>
.ayc178dru {
  d: path("M12 2.5s-7 8-7 12.5a7 7 0 0 0 14 0c0-4.5-7-12.5-7-12.5Z");
}

.r3843ibrj {
  d: path("M8.5 15.5A3.5 3.5 0 0 0 12 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
