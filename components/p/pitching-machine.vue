<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="omyyn-bmy"/><path class="b1dv66uvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pitching-machine" /></template>
<style>
.b1dv66uvl {
  d: path("M6.25 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.25-.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.omyyn-bmy {
  d: path("M3 9a5.25 5.25 0 1 0 10.5 0A5.25 5.25 0 1 0 3 9Zm5.25 5.25L4 21.5m4.25-7.25l4.25 7.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
