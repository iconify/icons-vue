<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rsh-9mbyd"/><path class="t-63w7aub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sabbatical" /></template>
<style>
.rsh-9mbyd {
  d: path("M5.5 21.5V13a6.5 5 0 0 1 13 0v8.5Z");
}

.t-63w7aub {
  d: path("M5 4h14v4H5Zm3.5 11h7v3.75h-7Zm-3-2.5c-2.5.25-3 2.5-3 4.5v2.5c0 1.25 1 2 3 2m13-9c2.5.25 3 2.5 3 4.5v2.5c0 1.25-1 2-3 2M9 4v4m6-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
