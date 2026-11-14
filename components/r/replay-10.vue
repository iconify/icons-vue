<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghtz8h6wm"/><path class="z8jmw9n4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:replay-10" /></template>
<style>
.ghtz8h6wm {
  d: path("M12 5.5a7.5 7.5 0 1 1-6.495 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8jmw9n4u {
  d: path("m15 2.5l-3 3l3 3m-6.5 3l1-1v5m3-5H16v5h-3.5Z");
}

</style>
